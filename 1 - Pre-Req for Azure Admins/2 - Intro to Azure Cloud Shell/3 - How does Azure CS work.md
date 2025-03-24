# 🎯 Goal:
Understand how Azure Cloud Shell works behind the scenes.

## 🧠 1. Important

### The Setup Process
When you first open Cloud Shell:
1 - Storage Setup: Azure automatically creates a storage account and file share (5GB).
2 - Environment Choice: Choose Bash or PowerShell — you can switch anytime.
3 - Shell Starts: A container with pre-installed tools spins up — ready to use.

### What Happens Under the Hood?
 - Runs in a container: Cloud Shell launches a temporary Docker container on Azure.
 - Your Files: Connected to your Azure file share for persistent storage (e.g., scripts, config files).
 - Timeouts: If idle for 20 minutes, the container shuts down — but your files are safe.

### Cost Considerations
💡 Cloud Shell itself is free, but the storage account it creates incurs a small cost (for the file share).
👉 Tip: It reuses the same storage every time, so you only pay for one.

## 🔍 2. My Own Words
Azure Cloud Shell spins up a temporary workspace using containers, saves your files to Azure storage, and keeps things running smoothly — but shuts off if you’re idle too long.

## 🔥 3. Analogy
It’s like a pop-up workshop: Azure builds a workspace on demand, keeps your tools (files) safe in a locker (storage), and packs it up when you leave.

## ✅ 4. One-Sentence Summary
Azure Cloud Shell works by running a temporary, cloud-hosted container linked to a persistent Azure file share — making it fast, portable, and ready on demand.
