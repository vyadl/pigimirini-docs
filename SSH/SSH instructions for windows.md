## SSH instructions for windows

### Step 1
Install OpenSSH client.

Settings -> Apps -> Optional Features -> OpenSSH client


### Step 2

Open Terminal.

Or usual one:
1. Press the **Windows key**.
1. Type **_cmd_**.
1. Under _Best Match_, right-click **Command Prompt**.
1. Click **Run as Administrator**.

Or maybe more comfortable console emulator, for example [cmder](https://cmder.net/).

### Step 3
Generate keys.

type in terminal:
```
ssh-keygen
```

By default, the system will save the keys to **C:\Users\_your_username_/.ssh/id_rsa**.

You’ll be asked to **enter a passphrase.** Hit **Enter** to skip this step.

### Step 4
Find SSH keys



1. The system will generate the key pair, and display the **key fingerprint** and a **randomart image**.
1. Open your file browser.
1. Navigate to **C:\Users\_your_username_/.ssh**.
1. You should see two files. The identification is saved in the **id_rsa** file and the public key is labeled **id_rsa****.pub**. This is your SSH key pair.


