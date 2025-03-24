# 🎯 Goal:
Understand the key differences between Microsoft Entra ID and Active Directory Domain Services (AD DS) and their use cases.

## 🧠 1. Important

### What's this about?
This section compares Microsoft Entra ID (a cloud-based identity service) with Active Directory Domain Services (AD DS), which is used for managing domain networks on-premises.

### Key Features
- **AD DS**: Hierarchical directory service, uses Kerberos for authentication, relies on DNS for resource locating, and supports LDAP.
- **Microsoft Entra ID**: Multi-tenant cloud service, uses HTTP/HTTPS, employs protocols like SAML and OAuth for authentication, and does not use LDAP.

### Extra Details
AD DS can be deployed on Azure, but this doesn’t integrate with Microsoft Entra ID. Entra ID is more suited for internet-based, cloud applications.

## 🔍 2. Simplified Explanation & Analogy
### One-Sentence Summary:  
Microsoft Entra ID is designed for cloud and web applications, while AD DS is for managing on-premises networks and resources.

### Analogy:  
Entra ID is like a modern, cloud-based membership system for accessing services online, while AD DS is like an old-school office directory system used for managing resources in a company building.