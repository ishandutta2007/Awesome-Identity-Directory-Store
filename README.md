# Awesome-Identity-Directory-Store

# Top Identity Directory Store Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Identity Stores, Directory Services & Self-Hosted IAM Platforms*
**Last updated: October 2026**

This repository tracks notable **commercial identity directory platforms** and **open-source projects** that store and manage user identities, groups, and organizational hierarchies — powering authentication, authorization, and single sign-on across enterprise and customer-facing applications.

**Examples** include AWS Identity Store, Azure AD B2C, Okta Universal Directory, PingDirectory, JumpCloud Directory, OneLogin Cloud Directory, Frontegg, WorkOS, Authentik, and FusionAuth (the category leaders).

**Open-source emphasis**: Identity directory stores are a strong open-source domain. **OpenDJ** leads as the most mature LDAPv3-compliant directory service with multi-master replication and REST/JSON access . **Kubidm** brings a modern, feature-rich identity provider with passkeys, OAuth2/OIDC, and SSH key distribution . **Apache Syncope** delivers enterprise-grade identity management with workflow engine and provisioning connectors . **Logto** provides a developer-friendly Auth0 alternative with OIDC, multi-tenancy, and RBAC . **Hanko** focuses on passkey-era authentication with a small footprint . **UNITY** and **Perun** serve federated research and academic environments . **Nubus** offers a modular, sovereign IAM solution for public sector and regulated industries . This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[AWS Identity Store](https://aws.amazon.com/identity-store/)**  
  **AWS's managed identity store** — part of AWS IAM Identity Center for workforce identity management. **Stores users, groups, and group memberships** for AWS applications and integrated SaaS. **Best for AWS-centric organizations**.

- **[Azure AD B2C](https://azure.microsoft.com/en-us/services/active-directory-b2c/)**  
  **Microsoft's customer identity access management (CIAM) platform** — white-label authentication for consumer-facing applications. **Supports social login, MFA, and custom policies**. **Best for customer-facing applications on Azure**.

- **[Okta Universal Directory](https://www.okta.com/products/universal-directory/)**  
  **The market-leading independent directory** — multi-tenant user store with profile mastering, attribute mapping, and app integration. **Best for enterprise identity**.

- **[PingDirectory](https://www.pingidentity.com/)**  
  **High-performance LDAP directory** — millions of entries with sub-millisecond latency. **Best for large-scale enterprise directories**.

- **[JumpCloud Directory](https://jumpcloud.com/)**  
  **The cloud directory platform** — unified directory, SSO, device management, and LDAP. **Free for up to 10 users**. **Best for SMBs wanting cloud directory**.

- **[OneLogin Cloud Directory](https://www.onelogin.com/)**  
  **Workforce identity** — directory, SSO, and MFA. **Best for mid-market enterprises**.

- **[Frontegg](https://frontegg.com/)**  
  **Customer identity platform** — multi-tenant SSO, RBAC, and user management for B2B SaaS. **Best for product-led SaaS**.

- **[WorkOS](https://workos.com/)**  
  **Enterprise SSO and directory sync** — SCIM, SSO, and audit logs for B2B SaaS. **Best for B2B SaaS companies**.

## Open-Source GitHub Projects

### LDAP Directory Servers

- **[OpenDJ](https://github.com/OpenIdentityPlatform/OpenDJ)**  
  **LDAPv3-compliant directory service written in Java**, CDDL licensed with **416+ GitHub stars** . **High performance with millisecond response times and tens of thousands of read/write operations per second** . **Multi-master replication for high availability** . **REST/JSON access to directory data over HTTP** — convenient for web and phone apps . **Stores LDAPv3 database in SQL JDBC database or NoSQL Cassandra/Scylla cluster** . **Available as DEB, RPM, MSI, ZIP, and Docker images** . **Best for enterprise LDAP directory services**.

- **[Apache Syncope](https://github.com/apache/syncope)**  
  **Open-source identity and access management platform**, Apache-2.0 licensed . **Full user lifecycle management with provisioning and de-provisioning** across heterogeneous systems . **Workflow engine with BPMN 2.0 support via Flowable** . **Admin UI and End-user UI** for self-registration, self-service, and password reset . **Scales to a million entities** with PostgreSQL, MySQL, MariaDB, or Oracle . **Fine-grained entitlements for delegated administration** . **Best for enterprise identity governance with workflow automation**.

- **[Kubidm](https://github.com/pando85/kubidm)**  
  **Simple, secure, and fast identity management platform** — fork of Kanidm with enterprise-grade features . **Passkeys (WebAuthn) for cryptographic authentication**, including attested passkeys for high-security environments . **OAuth2/OIDC authentication provider for SSO** . **Linux/Unix integration with TPM protected offline authentication** and **SSH key distribution** . **RADIUS for network and VPN authentication** . **Read-only LDAPS gateway for legacy systems** . **Two-node high availability with database replication** . **Complete CLI tooling** with Web UI for user self-service . **Best for modern, feature-rich self-hosted identity provider**.

### CIAM & Developer-Focused Identity Platforms

- **[Logto](https://github.com/logto-io/logto)**  
  **Open-source identity and access management platform** — Auth0 alternative for developers . **OIDC-based authentication with SDKs for multiple platforms and languages** . **Passwordless login, social login (Google, Facebook, GitHub, Apple), and email/SMS options** . **Role-based access control (RBAC) for scalable authorization** . **Audit logs for tracking identity-related activities** . **Single sign-on (SSO) and multi-factor authentication (MFA) without minimal coding** . **Organizations for multi-tenant applications** . **Best for developer-friendly CIAM and B2B SaaS**.

- **[Hanko](https://github.com/teamhanko/hanko)**  
  **Open-source authentication and user management solution for the passkey era**, open-source . **Supports all modern authentication methods**: passkeys, social logins, SAML SSO, passwords, and passcodes . **Highly flexible configuration** — optional/user-deletable passwords, passkey-only, OAuth-only . **Hanko Elements web components** for embeddable login/registration and account profile . **API-first, small footprint, cloud-native** . **Self-hosting and Hanko Cloud available** . **Best for passkey-first authentication**.

- **[Nubus](https://github.com/univention/nubus)**  
  **Modular open-source solution for centralized Identity & Access Management (IAM)**, AGPL-3.0-or-later licensed . **Central web portal for user management and access control** . **Integrated Single Sign-On (SSO)** for connected systems . **Self-service functions** for password changes and profile updates . **Prebuilt integrations for common systems and services** . **Scalable architecture** for cloud, on-premises, and hybrid environments . **Designed for data protection-sensitive environments** — used by ZenDiS GmbH, Orange S.A., and German state education ministries . **Best for sovereign IAM in public sector and regulated industries**.

### Federated & Research Identity Management

- **[UNITY](https://github.com/unity-idm/unity)**  
  **Open-source group, identity, and federation management solution**, BSD licensed . **Acts as a hub or proxy between identity federations and web/cloud services** . **Supports SAML2 (IdP and SP), OAuth 2.0, OIDC, and X.509** . **Management of groups and group hierarchies** with internal authorization . **Registration and user form management** for enrolment of new users . **Attribute aggregation and account linking** . **REST API and Java API** . **Deployed in Human Brain Project (HBP), PLGrid, and EUDAT2020** . **Best for federated research and academic environments**.

- **[Perun](https://github.com/CESNET/Perun)**  
  **Identity and access management system covering the whole user life cycle**, FreeBSD licensed . **Virtual organisation management, user and group management, resource management, and service management** . **Designed for distributed and federated environments** . **Identity consolidation (account linking)** and **provisioning/de-provisioning of user rights on services** . **Enrolment management with customisable application forms** . **Web GUI, CLI, REST-like API, and libraries in PHP, Perl, JavaScript, and Java** . **Production deployments in Czech e-Infrastructure (CESNET), Masaryk University, ELIXIR, and EGI** . **Best for research infrastructure and federated identity management**.

### Additional Strong Open-Source Options

- **LLDAP** — Lightweight LDAP server with web admin portal. Simpler than Kubidm but requires external portal like Keycloak for OAuth2/OIDC .
- **389 Directory Server** — Enterprise-class LDAP server from Red Hat .
- **OpenLDAP** — The standard open-source LDAP directory .
- **FreeIPA** — Comprehensive identity management for Linux/Unix with LDAP, Kerberos, DNS, and CA .
- **Keycloak** — OIDC/OAuth2/SAML provider that can layer WebAuthn authentication on existing IDM systems .
- **ldap-rest** — Lightweight, plugin-based directory manager exposing LDAP through REST API with system synchronization .

**Frameworks for building custom identity directory store solutions**: Combine **OpenDJ** for enterprise LDAP directory services with multi-master replication and REST access . Use **Kubidm** for modern identity provider with passkeys, OAuth2/OIDC, and SSH key distribution . Deploy **Apache Syncope** for full identity governance with workflow automation and provisioning connectors . Choose **Logto** for developer-friendly CIAM with multi-tenancy and RBAC . Integrate **Hanko** for passkey-first authentication with embeddable web components . Use **UNITY** or **Perun** for federated research environments . Choose **Nubus** for sovereign IAM in public sector and regulated industries . Note that true enterprise identity directory stores with global infrastructure, managed scaling, and vendor-supported SLAs (Okta Universal Directory, PingDirectory, Azure AD B2C) remain primarily commercial territory; open-source stacks provide strong LDAP directories, CIAM platforms, and federated identity foundations that require integration for complete identity management.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Identity directory stores handle sensitive authentication data and access controls. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations.
- **License considerations**: OpenDJ uses CDDL , Apache Syncope uses Apache-2.0 , Kubidm is a fork of Kanidm (MPL-2.0) , Logto uses MPL-2.0 , Hanko is open-source , UNITY uses BSD , Perun uses FreeBSD , and Nubus uses AGPL-3.0-or-later . Verify licensing against your use case before committing.
- **Identity store choice depends on requirements** — LDAP for legacy compatibility, OIDC/OAuth2 for modern applications, SAML for enterprise SSO, and passkeys for passwordless authentication .
- The open-source ecosystem provides strong LDAP directories, CIAM platforms, and federated identity foundations, but **global infrastructure, managed scaling, and vendor-supported SLAs** remain primarily commercial offerings.

---

**Made for identity architects, platform engineers, and organizations seeking identity directory store sovereignty.**
Let's make identity directory stores more open, transparent, and secure.
