# How to Access All the Ports from VM

Due to the firewall, not all ports are open. We need to do port forwarding to access some of the ports which are closed by default.

## Manual port forwarding

### Step 1: Connect to VM by Specifying the Port Forward

Use the following command to connect to your VM:

```sh
ssh ubuntu@floating_IP -D 20000 -i ssh_key
```

20000 is a random port that is not used by any service available on your local machine and virtual machine.

### Step 2: Configure Network Settings

1. Go to your network settings.

2. Enable manual proxy.
   - In the SOCKS Proxy settings, select SOCKS v5.
   - Set the host to 127.0.0.1.
   - Set the port to 20000 (the port used in the first step).

### Step 3: Access the VM

Open your browser and type the private IP of the VM and the port number to check the access:

```text
http://192.168.1.25:8080
```

For example, with a VM having private IP 192.168.1.25 and wanting to access port 8080.

**Important Note:**
Once you kill the SSH session, make sure to remove the proxy settings; otherwise, you will not be able to access the internet from your machine. While still being connected with the port forwarding, you should get internet access.

## Using VSCode for Port Forwarding

1. Connect to the VM using VSCode
2. Open the Terminal for the VM
3. Tab next to the Terminal will be Ports, change the Tab and go to Ports Tab
4. Enable port forwarding -> VSCode will ask to authenticate using GitHub account. Login and approve the VSCode to use the GitHub. (This you have to do it only once, when you are tying for the first time or unless you have revoked the permissions)
5. Once everything is approved, you should be able to see the Forwarded Address in VSCode, if you click the link, it will ask to login to GitHub , to authenticate you have permission to access the page. (As the link visibility by default is Private)
6. If you want to to change the link visibility, go to VSCode ports Tab, go to the port which you want to access publicly, change the visibility from Private --> Public.

More details about the VSCode port forwarding is also available on their website [external site](https://code.visualstudio.com/docs/editor/port-forwarding).
