---
title: "Zapier, Make or n8n: which automation tool to choose?"
translationKey: "zapier-make-n8n"
date: 2026-10-28T08:00:00+01:00
lastmod: 2026-10-28T08:00:00+01:00
description: "Zapier vs Make vs n8n: prices, billing units, data hosting and code compared to choose the right automation tool."
categories: ["AI and Automation"]
tags: ["Zapier", "Make", "n8n", "automation", "no-code", "comparison"]
author: "thomas-durand"
image: "/images/blog/zapier-make-ou-n8n.jpg"
imageAlt: "Hand drawing a workflow diagram on a tablet, in front of a screen showing code"
imageCredit: "Photo: Jakub Żerdzicki, Unsplash (cropped)"
faq:
  - question: "Zapier, Make or n8n: which automation tool should you choose?"
    answer: "It depends on the profile. Based on the pricing pages checked on 27 October 2026, Zapier advertises the largest catalogue (more than 10,387 apps) and a free plan with 100 tasks per month. Make shows the lowest entry price for a given volume: $11 per month for 10,000 credits with the Core plan. n8n stands out with a free self-hosted edition, cloud hosting in Frankfurt and billing per execution regardless of workflow complexity, from €20 per month billed annually."
  - question: "Which automation tool is the cheapest?"
    answer: "All three tools offer free access: 100 tasks per month with Zapier, 1,000 credits per month with Make, and n8n's self-hosted Community edition. For paid plans, the units differ (task, credit, execution), which prevents a direct comparison. A workflow made of one trigger and ten actions counts as ten tasks in Zapier, around ten credits in Make, but a single execution in n8n."
  - question: "Which automation tool hosts data in Europe?"
    answer: "Among the three tools compared, n8n is the only one whose pricing page states a hosting location: cloud plans store data in the European Union, on servers located in Frankfurt, Germany. The self-hosted edition also lets you choose your own server. The Zapier and Make pricing pages checked on 27 October 2026 do not specify this."
  - question: "Do you need to code to use n8n?"
    answer: "Not for simple cases: n8n offers a visual editor and more than 2,000 integrations. Code becomes useful for advanced cases, as the Code node accepts JavaScript and Python. Self-hosting, however, requires technical skills, as the documentation describes installations with Docker or Node.js."
  - question: "Do these tools offer artificial intelligence features?"
    answer: "Yes. Zapier offers agents and chatbots, with basic access on all plans. Make states that some advanced features relying on its AI provider consume more credits. n8n's cloud trials include AI credits and assistant credits."
readingTime: true
---

> **In short:**
> 1. Zapier, Make and n8n are compared based on their pricing pages checked on 27 October 2026: Zapier bills per task, Make per credit, n8n per workflow execution.
> 2. n8n is the only one of the three to advertise cloud hosting in the European Union (Frankfurt) and a free self-hosted Community edition, with cloud plans from €20 per month billed annually for 2,500 executions.
> 3. Zapier claims the largest catalogue, more than 10,387 apps, with a free plan of 100 tasks per month and a Pro plan from $19.99 per month billed annually.
> 4. Make shows $11 per month for 10,000 credits with the Core plan and claims more than 3,500 apps.

## Comparison table: Zapier, Make and n8n

| Criterion | n8n | Zapier | Make |
|---|---|---|---|
| Billing unit | Workflow execution, regardless of complexity | Task (each successful action) | Credit (most actions use 1 credit) |
| Free access | Self-hosted Community edition | 100 tasks per month, two-step Zaps | 1,000 credits per month |
| First paid plan | Starter, €20 per month billed annually, 2,500 executions | Pro, $19.99 per month billed annually ($29.99 monthly), 750 tasks | Core, $11 per month for 10,000 credits |
| Apps advertised | More than 2,000 integrations | More than 10,387 apps | More than 3,500 apps |
| Code | JavaScript and Python (Code node) | Not noted on the pricing page | Not noted on the pricing page |
| Data hosting | EU, servers in Frankfurt (cloud), or server of your choice (self-hosted) | Not specified on the pricing page | Not specified on the pricing page |
| Trial | Starter and Pro without a credit card | 14 days of the Pro plan, no credit card | Free plan |
| Currency shown | Euro | Dollar | Dollar |
| **Verdict** | Most control over data and the cost of long workflows | Simplest, with the largest catalogue | Best entry price for a high volume of actions |

Method: prices, volumes and features come from the three vendors' pricing pages and n8n's documentation, consulted on 27 October 2026. Prices are shown as displayed, without currency conversion. A "not noted" or "not specified" cell means the information did not appear on the page consulted, not that the feature is missing.

## Why compare Zapier, Make and n8n

Zapier, Make and n8n are the three names that come up most often when a business wants to **automate repetitive tasks** without building every connection between its software by hand. All three rely on the same principle: a trigger launches a series of actions in other applications. This principle is covered in the guide on how to [automate repetitive tasks]({{< relref "automate-repetitive-tasks.md" >}}).

They mainly differ on three points: how they bill, where workflows run and how much freedom they give technical users.

### The criteria used for the comparison

- **The billing unit**, which determines the real cost of a workflow.
- **Free access** and the price of the first paid plan.
- **The number of apps** the vendor says can be connected.
- **The ability to write code** for cases that go beyond the visual editor.
- **Data hosting**, a sensitive point under the GDPR.

## Task, credit or execution: the real price criterion

Comparing displayed prices is not enough, because the three tools do not count the same thing. According to the pricing pages checked on 27 October 2026:

- **Zapier** counts tasks: according to its help centre, a task is any successful action. Triggers, filters and formatting steps are not counted.
- **Make** counts credits: most actions in a scenario use one credit, and some advanced features using its AI provider may use more.
- **n8n** counts workflow executions: the pricing page states that the price does not depend on workflow complexity.

In practice, a workflow made of one trigger and ten actions, run once, uses ten tasks in Zapier, around ten credits in Make, but a single execution in n8n. The longer the workflows, the more this gap weighs on the bill.

| Example: one trigger and 10 actions, run 100 times a month | Usage |
|---|---|
| Zapier | 1,000 tasks |
| Make | Around 1,000 credits |
| n8n | 100 executions |

This calculation illustrates the logic of each unit. It does not replace an estimate based on your own workflows, because some steps are excluded from the count depending on the tool: filters and formatting in Zapier, router and error-handling modules in Make.

## n8n: open automation, hosted in Europe or on your own server

n8n is a workflow automation tool that stands out for its two distribution modes: a cloud service run by the vendor, and a **Community edition** you install on your own server. The documentation states that without a licence key, n8n runs as this free edition. Plans and conditions are detailed on [n8n's pricing page](https://n8n.io/pricing/).

For cloud plans, the pricing page states that data is stored in the European Union, on servers located in Frankfurt, Germany. When self-hosted, data stays wherever the business installs n8n.

### n8n's key features

- **Starter**: €20 per month billed annually, 2,500 workflow executions.
- **Pro**: €50 per month billed annually, 10,000 executions.
- **Business**: €667 per month billed annually, 40,000 executions, self-hosted.
- **Enterprise**: on quote, cloud or self-hosted.
- **Trial**: no credit card for Starter and Pro, with 1,000 executions, AI credits and assistant credits.
- **Code**: the Code node accepts JavaScript and Python, and expressions accept JavaScript, according to the documentation.
- **Integrations**: more than 2,000 advertised on the dedicated page.

Self-hosting comes at a price: someone has to install, update and secure the server. The documentation describes installations with Docker or Node.js. Choosing suitable [web hosting]({{< relref "shared-hosting-vps-cloud.md" >}}), often a VPS, then becomes part of the project.

## Zapier and Make: the strengths of the other two tools

### Zapier, the largest app catalogue

Zapier says it connects more than 10,387 apps, with no code required. This is the main argument for a team that uses many different SaaS tools and wants to link them quickly.

Its pricing checked on 27 October 2026 is as follows: a Free plan with 100 tasks per month, limited to two-step Zaps and one user; a Pro plan from $19.99 per month billed annually ($29.99 monthly) for 750 tasks; a Team plan from $69 per month billed annually for 2,000 tasks and 25 users; and an Enterprise plan on quote. The Pro trial lasts 14 days, without a credit card.

On the artificial intelligence side, Zapier offers agents and chatbots, with basic access on all plans and paid options beyond that.

### Make, the visual builder with a low entry price

Make highlights a visual scenario editor and claims more than 3,500 apps. For 10,000 credits per month, its pricing page shows Core at $11, Pro at $20 and Teams at $36 per month. The FAQ states that annual payment is cheaper than monthly payment.

The Free plan includes 1,000 credits per month. The Core plan adds unlimited active scenarios and scheduling down to the minute. Make also offers a Start-up Plan for companies with fewer than 20 employees, with 50% off the Business plan, subject to eligibility.

## Who is it for? Recommendations by profile

### Technical team or web agency

n8n is the most consistent choice: JavaScript and Python code, billing that does not penalise long workflows, and the option to host the tool on your own server. It is also the tool that leaves the most freedom to plug AI models into a workflow.

### Business that cares about data location

n8n is the only one of the three to state, on its pricing page, hosting in the European Union. The data handled by a workflow ([CRM]({{< relref "what-is-a-crm.md" >}}) customer records, invoices, email addresses) is often personal: hosting location matters in a GDPR assessment.

### Small non-technical team

Zapier remains the easiest to learn and covers the most apps. Make suits those who prefer to see their scenarios visually and run high volumes of simple actions, thanks to its low entry price.

## How to choose your automation tool

1. **List the apps to connect** and check that they exist in each tool's catalogue.
2. **Estimate the real volume**: number of runs per month multiplied by the number of steps.
3. **Convert this volume into each tool's unit**: tasks, credits or executions.
4. **Check where data is hosted** and whether self-hosting is needed.
5. **Test on a real workflow** during the free plan or trial.

An automation tool holds access to several company accounts. [Cybersecurity best practices]({{< relref "small-business-cybersecurity-best-practices.md" >}}) fully apply: two-factor authentication, dedicated service accounts and permissions limited to what is strictly needed.

### Mistakes to avoid

1. Comparing displayed prices without taking the billing unit into account.
2. Underestimating the number of steps in a workflow, and therefore its usage.
3. Choosing self-hosting without anyone to maintain and secure the server.
4. Forgetting to check where the personal data being processed is stored.
5. Building all workflows on a personal account rather than a company account.

## Frequently asked questions

<details>
<summary>Zapier, Make or n8n: which automation tool should you choose?</summary>

It depends on the profile. Based on the pricing pages checked on 27 October 2026, Zapier advertises the largest catalogue (more than 10,387 apps) and a free plan with 100 tasks per month. Make shows the lowest entry price for a given volume: $11 per month for 10,000 credits with the Core plan. n8n stands out with a free self-hosted edition, cloud hosting in Frankfurt and billing per execution regardless of workflow complexity, from €20 per month billed annually.

</details>

<details>
<summary>Which automation tool is the cheapest?</summary>

All three tools offer free access: 100 tasks per month with Zapier, 1,000 credits per month with Make, and n8n's self-hosted Community edition. For paid plans, the units differ (task, credit, execution), which prevents a direct comparison. A workflow made of one trigger and ten actions counts as ten tasks in Zapier, around ten credits in Make, but a single execution in n8n.

</details>

<details>
<summary>Which automation tool hosts data in Europe?</summary>

Among the three tools compared, n8n is the only one whose pricing page states a hosting location: cloud plans store data in the European Union, on servers located in Frankfurt, Germany. The self-hosted edition also lets you choose your own server. The Zapier and Make pricing pages checked on 27 October 2026 do not specify this.

</details>

<details>
<summary>Do you need to code to use n8n?</summary>

Not for simple cases: n8n offers a visual editor and more than 2,000 integrations. Code becomes useful for advanced cases, as the Code node accepts JavaScript and Python. Self-hosting, however, requires technical skills, as the documentation describes installations with Docker or Node.js.

</details>

<details>
<summary>Do these tools offer artificial intelligence features?</summary>

Yes. Zapier offers agents and chatbots, with basic access on all plans. Make states that some advanced features relying on its AI provider consume more credits. n8n's cloud trials include AI credits and assistant credits.

</details>
