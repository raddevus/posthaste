### Purpose
PostHaste uses JS Fetch API to retrieve API endpoints.<br>
Yes, you can consider this your PostMan replacement.  🤓

### Remembers Your URLs
It stores the URLs that you retrieve in localStorage so you can select them from the dropdown list.

### User Interface : Enter Your URL & Go
<img width="602" height="431" alt="postHasteMainScreen" src="https://github.com/user-attachments/assets/b5272104-d207-429c-a67e-b52defd5aa87" />

### Built Using ElectronJS
Here's how you get started:
1. clone this project
2. npm install
3. npm start

##### Chrome Sandbox Issue
You may see a warning that states:
```
[14167:1119/095917.066518:FATAL:sandbox/linux/suid/client/setuid_sandbox_host.cc:166] The SUID sandbox helper binary was found,
but is not configured correctly.
Rather than run without sandboxing I'm aborting now.
You need to make sure that /home/<user-name>/<your-path>/ is owned by root and has mode 4755.
```
###### Fix Sandbox Issue
You can run the following commands:
```
sudo chown root:root /home/<user-name>/<your-path>/
sudo chmod 4755 /home/<user-name>/<your-path>/
```
After that, you will be able to run `npm start` and the app will start properly.
