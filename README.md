# nginx-oidc-onelogin

Reference implementation of NGINX Plus as relying party for OpenID Connect authentication w/ Onelogin.

This repo provides the information of how to set up Onelogin, integrate with NGINX Plus, and locally test using a containerized NGINX Plus app, a frontend OIDC simulation tool, and a NGINX Dev Portal.

![](./docs/img/nginx-oidc-workflow.png)

- [Getting Started](#🏠-getting-started)
- [Troubleshooting](#🔧-troubleshooting)
- [References](#📚-references)

<br>

## 🏠 Getting Started

### Set up an identity provider (IdP)

- [Create and configure an app in Onelogin](./docs/01-IdP-Setup.md)

### Option 1. Set up and Test a SSO application via NGINX Plus

- [Configure NGINX Plus OIDC](./docs/02-NGINX-Plus-Setup.md)
- [Locally Test an SSO app in a container ](./docs/03-Container-Test.md)

### Option 2. Set up and Test a SSO application via NGINX ACM/DevPortal

- [Install, configure, and test OIDC via NGINX ACM/DevPortal](./docs/04-NGINX-DevPortal-Test.md)

<br>

## 🔧 Troubleshooting

- [Common Troubleshooting for NGINX Plus OIDC](https://github.com/nginx-openid-connect/nginx-oidc-troubleshooting#-common-troubleshooting-for-nginx-oidc-and-all-idps)
- [Troubleshooting for NGINX Plus OIDC and Onelogin](https://github.com/nginx-openid-connect/nginx-oidc-troubleshooting#troubleshooting-for-nginx-plus-oidc-and-onelogin)

<br>

## 📚 References

- [NGINX OIDC Core v1.0: Forked from NGINX GitHub](https://github.com/nginx-openid-connect/nginx-oidc-core-v1)
- [NGINX OIDC Core v2.0: Forked from NGINX GitHub](https://github.com/nginx-openid-connect/nginx-oidc-core)
- [NGINX Plus: Single Sign-On With Onelogin](https://docs.nginx.com/nginx/deployment-guides/single-sign-on/onelogin/#config-onelogin)
- [NGINX Management Suite](https://docs.nginx.com/nginx-management-suite/)
- [NGINX API Connectivity Manager](https://docs.nginx.com/nginx-management-suite/acm/)
