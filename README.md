# Keirran's Content Management System (KeiCMS)
![GITHUB](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)
![RELEASE](https://img.shields.io/github/v/release/KeiBlackley/KeiCMS) ![LICENCE](https://img.shields.io/github/license/KeiBlackley/KeiCMS.svg) ![ISSUES](https://img.shields.io/github/issues/KeiBlackley/KeiCMS.svg)

Coded based CMS ('Content Management System') designed in PHP.
> Frequent development since 2012.

## Table of Contents
- [About](#about)
- [Users Access](https://keirranblackley.com)
- [Security](#security)
	- [Sensitive Data](#sensitive-data)
	- [Multi-Factor Authentication](multi-factor-authentication)
	- [reCAPTCHA](#recaptcha)
	- [API Usage](#api-usage)
- [Account](#account)
	- [Settings](#settings)
	- [Features](#features)
- [Licence](./LICENCE)
- [Support](#support)

<hr/>

### About
KeiCMS ("Keirran's Content Management System") has been in constant development since 2011 with a start inspiration from RevCMS for Habbo Retro servers and is developed in PHP.

It uses the use of an `index` router, which directs traffic to a single page and dynamically displays content depending on a set of unique paramaters defined by the site.

While coming from an open-source beginning, the Project ("KeiCMS") has closed off it's access to backend code due to security impacts and the publishment of [keirranblackley.com](keirranblackley.com) as a main hub for live projects designed and created by Keirran Blackley.

*Not all elements of KeiCMS may be in this Documentation. Feel free to keep updated by checking back to this file.*

<hr/>

### Users Access
[![WEBSITE](https://img.shields.io/badge/website-000000?style=for-the-badge&logo=About.me&logoColor=white)](https://keirranblackley.com)

<hr/>

### Security
- [Encryption](#encryption)
- [Multi-Factor Authentication](#multi-factor-authentication)

#### Sensitive Data
Sensitive Data is stored with a Government Grade AES-256-GCM Encryption. Authenticated in a 256-bit, encrypted and split key that's unreadable without each message.. used for confidentiality and security.

#### Multi-Factor Authentication
| Method | Explination |
| ------ | ----------- |
| Email  | 6 digit numeric code is sent to your account email address after username and password validation is successful. |
| Authentication App | Compatible with TOTP ('Time-based One-Time Password') Applications such as Google Authenticator. Scan a one-time QR or enter unique code manually to setup. |

#### reCAPTCHA
Uses Google reCAPTCHA to present challenges to distinguish between human users and automated bots. Helps protect against spam, abuse, and automated attacks by blocking suspicious or automated traffic.

#### API Usage
By having configured an API, we prevent unauthorized cross-origin requests and reduce the risk of data leaks or attacks from other websites.

<hr/>

### Account
> Here is an outline of your account with KeiCMS.

#### Settings
- **Password:** Update password with our [Encryption](#encryption) methods.
- **Email Address:** Update your email address ([See what it's used for](#email))
- **Delete Account:** Permanently deletes all account data stored on the KeiCMS server.

#### Features
- **Image Upload:** Currently for looks, not publicly displayedanywhere.
- **Support Contact:** Form access to contact support if any issues with your account (all access)

<hr/>

### Support
> Show your support with a donation to the project.

[![PAYPAL](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)](https://paypal.me/KeiBlackley)









