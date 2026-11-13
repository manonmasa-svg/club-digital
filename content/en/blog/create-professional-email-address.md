---
title: "How do you create a professional email address?"
translationKey: "create-business-email-address"
date: 2026-11-14T08:00:00+01:00
lastmod: 2026-11-14T08:00:00+01:00
description: "Create a professional email address: domain name, choice of email service, DNS settings (MX, SPF, DKIM, DMARC) and prices checked."
categories: ["Cloud and Hosting"]
tags: ["professional email address", "domain name", "business email", "DNS", "small business"]
author: "thomas-durand"
image: "/images/blog/creer-adresse-email-professionnelle.jpg"
imageAlt: "White keyboard keys spelling the word EMAIL on a grey background"
imageCredit: "Photo: Miguel Ángel Padriñán Alba, Unsplash (cropped)"
faq:
  - question: "How do you create a professional email address?"
    answer: "You need three things: a domain name in the company's name, an email service that hosts the mailboxes, and DNS records that connect the two (MX to receive, SPF, DKIM and DMARC for authentication). According to the pages checked on 13 November 2026, a .fr domain costs €4.99 excl. VAT for the first year at OVHcloud, and a Zimbra Starter mailbox €0.30 excl. VAT per month. Google Workspace and Microsoft 365 also include a professional address, from €6.07 excl. VAT (Microsoft 365) and €6.80 (Google Workspace) per user per month with an annual commitment (checked on 9 November 2026)."
  - question: "Can you get a free professional email address?"
    answer: "An address in the company's name requires at least buying a domain name. At OVHcloud, the free hosting plan in the Eco range, included with every domain name purchased, comes with one email address (checked on 29 October 2026). An address on a free email domain, such as Gmail or Outlook.com, is not an address in the company's name."
  - question: "How much does a professional email address cost?"
    answer: "According to the checks made in November 2026: from €0.30 excl. VAT per month per account (OVHcloud Zimbra Starter, 15 GB) to €1.82 excl. VAT (Zimbra Pro, 50 GB), from €1.50 excl. VAT per month at Infomaniak (Service Mail, annual billing), and from €6.07 excl. VAT per user per month for Microsoft 365 Business Basic or €6.80 for Google Workspace Business Starter, which add an office suite. The domain name comes on top: €4.99 excl. VAT for the first year for a .fr at OVHcloud, then €7.79 excl. VAT."
  - question: "What are SPF, DKIM and DMARC records for?"
    answer: "They prove to recipients' mail servers that emails really come from the company's domain. SPF lists the servers allowed to send, DKIM signs each message, and DMARC tells recipients what to do with messages that fail these checks. Without them, emails are more likely to land in spam and the domain is easier to spoof."
  - question: "Which address should you choose: firstname.lastname@ or contact@?"
    answer: "The two are complementary. A personal address, such as firstname.lastname@company.com, is used for individual exchanges with clients. A generic address, such as contact@ or invoices@, can be shared, survives staff departures and is often set up as an alias forwarding to one or more mailboxes."
readingTime: true
---

> **In short:**
> 1. A **professional email address** relies on three things: a domain name in the company's name, an email service, and DNS records (MX, SPF, DKIM, DMARC) that connect the two.
> 2. The domain name costs €4.99 excl. VAT for the first year for a .fr at OVHcloud, then €7.79 excl. VAT on renewal (checked on 13 November 2026).
> 3. An email-only service costs from €0.30 excl. VAT per month per account (OVHcloud Zimbra Starter) to €1.82 excl. VAT (Zimbra Pro), or from €1.50 excl. VAT per month at Infomaniak.
> 4. Microsoft 365 Business Basic (€6.07 excl. VAT) and Google Workspace Business Starter (€6.80) add office apps and video calls, per user per month with an annual commitment (checked on 9 November 2026).

## Why create a professional email address

**Creating a professional email address** in the company's name, such as contact@company.com, changes how messages are perceived. A quote sent from a personal address on a free email service inspires less trust than a message sent from the company's domain.

A professional address also belongs to the company. When an employee leaves, their mailbox can be kept, forwarded or archived. Exchanges with clients do not disappear with a personal account.

Finally, the domain name is also used for the website. A single identity, the domain name, brings together the website and the email addresses.

## The three building blocks of a professional email address

| Building block | Role | Example |
|---|---|---|
| Domain name | The company's identity online, the part after the @ | company.com |
| Email service | The server that stores mailboxes and sends messages | OVHcloud, Infomaniak, Google Workspace, Microsoft 365 |
| DNS records | The settings that say where to deliver emails and prove their authenticity | MX, SPF, DKIM, DMARC |

All three can be bought from the same provider, which simplifies setup. They can also be split: a domain at one registrar, email at another provider.

## Step 1: choose and buy a domain name

The domain name is the part after the @. It usually reflects the company or brand name, with an extension such as .com or .fr.

According to OVHcloud's .fr extension page, consulted on 13 November 2026, a .fr domain costs €4.99 excl. VAT for the first year, then €7.79 excl. VAT on renewal. A .com costs €8.49 excl. VAT, then €14.29 excl. VAT on renewal. These prices are annual.

A few rules for choosing:

- **Short and easy to spell**: it will be read out over the phone and typed by hand.
- **No hyphens or ambiguous numbers**, which cause typing errors.
- **Check existing trademarks** before buying, to avoid a conflict with a registered brand.
- **Turn on automatic renewal**: an expired domain takes down both the website and email.

## Step 2: choose the email service

Three families of offers can host professional addresses.

### Addresses included with web hosting

Many web hosts include mailboxes in their website hosting plans. The comparison of the [best web host for a business website]({{< relref "best-web-hosting-business.md" >}}) details, as of 29 October 2026, the number of mailboxes included in each plan. OVHcloud notably offers a free plan in its Eco range, included with every domain name, which comes with one email address.

### Dedicated professional email services

Dedicated offers host email only, with more storage and features.

| Plan checked | Price | Storage | Notable points |
|---|---|---|---|
| OVHcloud Zimbra Starter | €0.30 excl. VAT per month per account | 15 GB | Zimbra webmail, calendars, tasks and contacts |
| OVHcloud Zimbra Pro | €1.82 excl. VAT per month per account | 50 GB | ActiveSync sync, file storage, online office suite |
| Infomaniak Service Mail | From €1.50 excl. VAT per month (annual billing) | Unlimited mail storage | Email service developed and hosted in Switzerland |
| Infomaniak kSuite Standard | €1.58 excl. VAT per user per month (annual billing) | Unlimited mail storage, 50 GB of files | 2 addresses per user |

Prices checked on 13 November 2026. OVHcloud states that its email service is hosted in France. Infomaniak states that its data is located exclusively in Switzerland and that mailboxes are backed up in 2 datacentres, with data recoverable for 30 days.

### Office suites with email

Google Workspace and Microsoft 365 include a professional address within a wider package: office apps, storage, video calls and team chat. According to the checks made on 9 November 2026, Google Workspace Business Starter costs €6.80 per user per month with an annual commitment (introductory price for new customers), and Microsoft 365 Business Basic €6.07 excl. VAT per user per month billed annually.

These suites also include a team chat app, compared in the article [Slack, Microsoft Teams or Google Chat]({{< relref "slack-vs-teams-vs-google-chat.md" >}}).

## Step 3: set up the DNS records

Once the domain and the email service are chosen, they need to be connected. This happens in the domain's DNS zone, available at the registrar. When the domain and email are with the same provider, these settings are often created automatically.

| Record | What it does |
|---|---|
| MX | Tells the world which server receives email for the domain |
| SPF | Lists the servers allowed to send email on behalf of the domain |
| DKIM | Adds a signature to each message to prove it has not been altered |
| DMARC | Tells recipients what to do with a message that fails SPF and DKIM checks, and lets the domain owner receive reports |

Without SPF, DKIM and DMARC, emails are more likely to land in recipients' spam folders, and the domain is easier for fraudsters to spoof. Infomaniak, for example, mentions its SPF, DKIM and DMARC filters against spoofing on its Service Mail page.

The website and email share the same DNS zone. A change for one, such as switching web host, must not delete the records of the other. The different types of hosting are presented in the article [shared, VPS, dedicated or cloud hosting]({{< relref "shared-hosting-vps-cloud.md" >}}).

## Step 4: create mailboxes, aliases and rules

### Personal and generic addresses

Two types of addresses usually coexist:

- **Personal addresses**, such as firstname.lastname@company.com, for individual exchanges with clients and partners.
- **Generic addresses**, such as contact@, invoices@ or jobs@, which survive staff departures and can be handled by several people.

A generic address does not always need a paid mailbox: an **alias** forwards its messages to one or more existing mailboxes.

### Avoid the catch-all address

Some email services offer a "catch-all" address that receives every message sent to any address on the domain, even non-existent ones. It attracts a lot of spam and can receive messages not intended for the company. It is better to create each useful address explicitly.

### Set up devices

Professional email services can be used through webmail, in software such as Outlook or Thunderbird, and on mobile. OVHcloud states that ActiveSync synchronisation of emails, contacts and calendars comes with its Zimbra Pro plan (the Business plan being announced as "coming soon"), not with Zimbra Starter.

## Step 5: secure email accounts

The mailbox is the key to many other accounts: it receives password reset links. Protecting it is a priority.

1. **Enable two-factor authentication** when the service offers it.
2. **Use a unique password** for each mailbox, stored in a [business password manager]({{< relref "best-business-password-manager.md" >}}).
3. **Remove or reassign access** as soon as an employee leaves.
4. **Watch out for phishing emails** that imitate the company's email service.

These habits are part of the [small business cybersecurity best practices]({{< relref "small-business-cybersecurity-best-practices.md" >}}) that apply across the whole company.

## How much does a professional email address cost

| Need | Option checked | Indicative cost |
|---|---|---|
| A single address to get started | .fr domain + Zimbra Starter (OVHcloud) | €4.99 excl. VAT for the first year + €0.30 excl. VAT per month |
| Several mailboxes with mobile sync | Domain + Zimbra Pro (OVHcloud) | €1.82 excl. VAT per month per account, plus the domain |
| Email hosted in Switzerland | Infomaniak Service Mail | From €1.50 excl. VAT per month billed annually, plus the domain |
| Email, office apps and video calls | Microsoft 365 Business Basic | €6.07 excl. VAT per user per month billed annually |
| Email, office apps and video calls | Google Workspace Business Starter | €6.80 per user per month with an annual commitment (introductory price) |

Prices for email-only services and the domain were checked on 13 November 2026, those for Microsoft 365 and Google Workspace on 9 November 2026. They may change: the providers' pages prevail.

## Frequently asked questions

<details>
<summary>How do you create a professional email address?</summary>

You need three things: a domain name in the company's name, an email service that hosts the mailboxes, and DNS records that connect the two (MX to receive, SPF, DKIM and DMARC for authentication). According to the pages checked on 13 November 2026, a .fr domain costs €4.99 excl. VAT for the first year at OVHcloud, and a Zimbra Starter mailbox €0.30 excl. VAT per month. Google Workspace and Microsoft 365 also include a professional address, from €6.07 excl. VAT (Microsoft 365) and €6.80 (Google Workspace) per user per month with an annual commitment (checked on 9 November 2026).

</details>

<details>
<summary>Can you get a free professional email address?</summary>

An address in the company's name requires at least buying a domain name. At OVHcloud, the free hosting plan in the Eco range, included with every domain name purchased, comes with one email address (checked on 29 October 2026). An address on a free email domain, such as Gmail or Outlook.com, is not an address in the company's name.

</details>

<details>
<summary>How much does a professional email address cost?</summary>

According to the checks made in November 2026: from €0.30 excl. VAT per month per account (OVHcloud Zimbra Starter, 15 GB) to €1.82 excl. VAT (Zimbra Pro, 50 GB), from €1.50 excl. VAT per month at Infomaniak (Service Mail, annual billing), and from €6.07 excl. VAT per user per month for Microsoft 365 Business Basic or €6.80 for Google Workspace Business Starter, which add an office suite. The domain name comes on top: €4.99 excl. VAT for the first year for a .fr at OVHcloud, then €7.79 excl. VAT.

</details>

<details>
<summary>What are SPF, DKIM and DMARC records for?</summary>

They prove to recipients' mail servers that emails really come from the company's domain. SPF lists the servers allowed to send, DKIM signs each message, and DMARC tells recipients what to do with messages that fail these checks. Without them, emails are more likely to land in spam and the domain is easier to spoof.

</details>

<details>
<summary>Which address should you choose: firstname.lastname@ or contact@?</summary>

The two are complementary. A personal address, such as firstname.lastname@company.com, is used for individual exchanges with clients. A generic address, such as contact@ or invoices@, can be shared, survives staff departures and is often set up as an alias forwarding to one or more mailboxes.

</details>
