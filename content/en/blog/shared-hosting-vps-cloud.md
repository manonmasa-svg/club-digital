---
title: "Web hosting: shared, VPS, dedicated or cloud?"
translationKey: "web-hosting-types"
date: 2026-10-18
lastmod: 2026-10-27
description: "Shared web hosting, VPS, dedicated server or cloud: differences, benefits, limits and criteria for choosing the right option."
categories: ["Cloud and Hosting"]
tags: ["web hosting", "VPS", "cloud", "dedicated server", "website"]
author: "thomas-durand"
image: "/images/blog/hebergement-mutualise-vps-cloud.jpg"
imageAlt: "Server rack with orange network cables in a server room"
imageCredit: "Photo: Kevin Ache, Unsplash (cropped)"
faq:
  - question: "What is the difference between shared hosting, a VPS and the cloud?"
    answer: "With shared hosting, several websites share the resources of the same server. A VPS is a virtual server with reserved resources. The cloud spreads hosting across an infrastructure whose capacity can be adjusted to demand. A dedicated server, finally, reserves an entire machine for a single customer."
  - question: "Which hosting should you choose for a brochure website?"
    answer: "For a brochure site or a blog with moderate traffic, shared hosting is often enough. It is simple to manage and the host takes care of server maintenance."
  - question: "Do you need technical skills to manage a VPS?"
    answer: "Generally, yes. Unless the offer is managed, system administration, updates and VPS security are the customer's responsibility."
  - question: "What is managed hosting?"
    answer: "It is an option in which a provider handles server administration: updates, monitoring, backups, security. The customer keeps the benefits of a VPS or a dedicated server without having to manage the technical side."
  - question: "Can you change hosting without losing your website?"
    answer: "Yes. Migration consists of copying the files and database to the new hosting, testing the site, then changing the domain name's DNS. The switch is often made during a low-traffic period, with a full backup beforehand."
readingTime: true
---

> **In short:**
> 1. Shared hosting splits one server between several websites and suits simple projects.
> 2. A VPS reserves resources on a virtual server, with more control but more management.
> 3. A dedicated server gives an entire machine to a single customer.
> 4. The cloud lets capacity follow the load.

## The main types of web hosting

**Web hosting** is the service that stores a website's files and makes it accessible on the internet. Several options exist, which differ in the level of reserved resources and in how much management is left to the customer.

| Option | Principle | Suited to | Technical management |
|---|---|---|---|
| Shared | Several sites on the same server | Brochure site, blog | Handled by the host |
| VPS | Virtual server with reserved resources | Sites with steady traffic, applications | Often the customer's job |
| Dedicated | An entire machine for one customer | Demanding projects | Customer's job, unless managed |
| Cloud | Adjustable capacity on a distributed infrastructure | Variable traffic, applications | Depends on the service |

## Shared hosting

With shared hosting, many websites share the resources of the same server: processor, memory, disk space. The host manages everything related to the machine, and the customer only has to upload the site, often through a simple control panel.

- **Benefits**: easy to use, server maintenance included, simplified installation of common CMSs.
- **Limits**: shared resources, so performance can vary with the activity of neighbouring sites, and little configuration freedom.

This option suits most brochure sites, blogs and small shops with moderate traffic.

## The VPS

A VPS, or virtual private server, splits a physical server into several virtual machines. Each customer gets reserved resources and a system they administer as they wish.

- **Benefits**: more consistent performance, freedom to install the software needed, resources that can grow.
- **Limits**: system administration, updates and security are the customer's responsibility, unless the offer is managed.

A VPS is a common next step when a site outgrows shared hosting or when an application needs a specific configuration.

## The dedicated server

A dedicated server reserves an entire physical machine for a single customer. It offers maximum power and control, and suits demanding projects: high-traffic sites, business applications, large databases. In return, it requires solid administration skills or a managed service contract.

## The cloud

The cloud spreads hosting across a distributed infrastructure. Capacity can be increased or reduced according to the load, and billing often depends on actual usage. This flexibility suits variable traffic, such as an online shop with seasonal peaks, and applications that must stay available at all times. On the other hand, usage needs to be monitored to keep the bill under control.

## Criteria for choosing

- **Expected traffic** and how it may grow.
- **Available skills** to administer a server.
- **Data location**, important for some activities.
- **Backups** offered and how often they run.
- **Support** and its opening hours.

Data location deserves particular attention. Hosting within the European Union makes GDPR compliance simpler when the site processes personal data. It is worth checking the host's terms to see where servers and backups are located.

## Domain name and hosting: two separate services

Domain names and hosting are often confused, because many providers sell both together. They are nevertheless two different services. The domain name is the site's address, registered with a registrar. Hosting is the space where the files are stored. DNS records link the two by telling the address which server to point to. It is entirely possible to buy a domain name from one provider and host the site with another, which also makes a future change of host easier.

## Moving from one host to another

Changing host or plan is a common operation. It usually follows these steps:

1. **Back up** the entire site: files and database.
2. **Install** the site on the new hosting and test it on a temporary address.
3. **Change the DNS** of the domain name to point to the new hosting.
4. **Check** that the site, forms and email addresses linked to the domain work.
5. **Keep the old hosting** for a few days while the DNS change propagates.

## Security and operations

A site's security depends partly on the host and partly on its administrator: [cybersecurity best practices]({{< relref "small-business-cybersecurity-best-practices.md" >}}) remain essential. A server can also be used to [automate repetitive tasks]({{< relref "automate-repetitive-tasks.md" >}}) through scheduled scripts, and online [collaboration tools]({{< relref "team-collaboration-tools.md" >}}) themselves run on cloud infrastructure.

Whatever the option, an HTTPS certificate, regular updates of the CMS and its extensions, and tested backups remain the foundation of smooth operations.

## Frequently asked questions

<details>
<summary>What is the difference between shared hosting, a VPS and the cloud?</summary>

With shared hosting, several websites share the resources of the same server. A VPS is a virtual server with reserved resources. The cloud spreads hosting across an infrastructure whose capacity can be adjusted to demand. A dedicated server, finally, reserves an entire machine for a single customer.

</details>

<details>
<summary>Which hosting should you choose for a brochure website?</summary>

For a brochure site or a blog with moderate traffic, shared hosting is often enough. It is simple to manage and the host takes care of server maintenance.

</details>

<details>
<summary>Do you need technical skills to manage a VPS?</summary>

Generally, yes. Unless the offer is managed, system administration, updates and VPS security are the customer's responsibility.

</details>

<details>
<summary>What is managed hosting?</summary>

It is an option in which a provider handles server administration: updates, monitoring, backups, security. The customer keeps the benefits of a VPS or a dedicated server without having to manage the technical side.

</details>

<details>
<summary>Can you change hosting without losing your website?</summary>

Yes. Migration consists of copying the files and database to the new hosting, testing the site, then changing the domain name's DNS. The switch is often made during a low-traffic period, with a full backup beforehand.

</details>
