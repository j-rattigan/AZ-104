# 🎯 Goal:
Understand the key differences and similarities between Microsoft Entra ID and Active Directory Domain Services (AD DS).

## 🧠 1. Important

### What's this about?
The module compares Microsoft Entra ID with AD DS, highlighting differences in how they handle directory services, identity management, and authentication.

### Key Features

| **Feature**                  | **Microsoft Entra ID**                            | **Active Directory Domain Services (AD DS)**  |
|------------------------------|--------------------------------------------------|-----------------------------------------------|
| **Type**                      | Multi-tenant identity solution                   | Directory service with hierarchical structure |
| **Authentication Protocols**  | Uses SAML, WS-Federation, OpenID Connect         | Uses Kerberos for authentication             |
| **Access Method**             | Uses REST API over HTTP/HTTPS                    | Uses LDAP                                    |
| **Management**                | No OUs or GPOs, flat structure                   | Uses OUs and GPOs for management              |

### Extra Details
- Entra ID is cloud-based and ideal for internet-facing apps.
- AD DS works on-premises, relying on DNS and LDAP for access.
- AD DS supports Kerberos and uses trusts for delegation.

## 🔍 2. My Own Words
Entra ID is for managing online identities, while AD DS is more traditional, managing on-premises networks and resources.

## 🔥 3. Analogy
Think of Entra ID like a bouncer at a modern online event, only allowing access through a special link (HTTP/HTTPS). AD DS is like an old-school club bouncer who uses a guest list (Kerberos) and checks IDs at the door.

## ✅ 4. One-Sentence Summary
Microsoft Entra ID is a cloud-based identity management service, while AD DS is a traditional directory service for on-premises environments.
