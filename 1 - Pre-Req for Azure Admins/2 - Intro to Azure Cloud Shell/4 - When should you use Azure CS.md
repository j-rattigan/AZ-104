# 4 - When to use Azure Cloud Shell

## 🎯 Goal:
Understand the scenarios where Azure Cloud Shell is beneficial and recognize its limitations.

## 🧠 1. Break it Down

### ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) **Important**
- **Session Timeout:** Azure Cloud Shell sessions automatically disconnect after 20 minutes of inactivity, leading to loss of the current state.
- **Single Instance:** Only one Cloud Shell instance can be active per user, preventing concurrent sessions across multiple subscriptions or tenants.

### ![#c5f015](https://placehold.co/15x15/c5f015/c5f015.png) **Key Features**
- **Browser-Based Access:** Secure command-line sessions can be initiated from any device with a browser.
- **No Installation Required:** Manage Azure resources without installing plugins or add-ons.
- **File Persistence:** Option to persist files between sessions for later use.
- **Shell Choice:** Use either Bash or PowerShell to manage Azure resources.
- **Integrated Editor:** Edit files, such as scripts, directly within the Cloud Shell environment.

### ![#f0e15d](https://placehold.co/15x15/f0e15d/f0e15d.png) **Supporting Details/Examples**
- **Limitations:**
  - **Long-Running Tasks:** Not suitable for tasks exceeding 20 minutes due to session timeout.
  - **Administrative Privileges:** Lacks admin permissions like `sudo` access.
  - **Custom Tool Installation:** Limited environment restricts installation of unsupported tools; a custom VM or container may be necessary.
  - **Regional Storage Constraints:** Storage is allocated to a single region, requiring backup and synchronization for multi-region needs.

## 🔍 2. Summary
Azure Cloud Shell is a convenient, browser-based tool for managing Azure resources without local installations, ideal for short, interactive tasks but not for prolonged or admin-level operations.

## 🔥 3. Analogy
Think of Azure Cloud Shell like a public library computer: readily accessible for quick tasks but not designed for prolonged, intensive work or installing personal software.
