# Team API template

A template for defining a Team API. Based on some of the ideas in the book _Team Topologies_ by Matthew Skelton [@matthewskelton](https://github.com/matthewskelton) and Manuel Pais [@manupaisable](https://github.com/manupaisable).

> See [teamtopologies.com](https://teamtopologies.com/) for more details about Team Topologies.

> Copyright © 2018-2020 [Team Topologies](https://teamtopologies.com/) - Licenced under [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) ![CC BY-SA 4.0](https://licensebuttons.net/l/by-sa/3.0/88x31.png)

## Overview

To improve the clarity of purpose for teams it can be useful to define a "Team API" for each team. Use this template to help teams think about their Team API.

## How to use

Each team should answer the questions and fill in the details below. Remember that the answers and details will be a point-in-time snapshot of team relationships and team interactions.

## Team API

Date: 2022-08-16

* Team name and focus: 🌮 (Technologies Actualizing Ca$h from Orders) - building and maintaining systems around the iZotope database; collaborating with internal stakeholders to make business better
* Team type: Enabling / Stream aligned (60/40)
* Part of a Platform? (y/n) Details: sorta
* Do we provide a service to other teams? (y/n) Details: yes; we perform operational tasks for teams when no interface exists (account deletes, NFRs, Retail SKU configurations, month close support)
* What kind of Service Level Expectations do other teams have of us? Critical issues should be resolved in a day.  Non-critical issues should be resolved within the week (but probably sooner)
* Software owned and evolved by this team: 
  * Databases
    * Customer Database (izodb)
    * Membership Database
  * .NET Applications
    * Authorization Services
    * Customer Services
    * CRM
    * Retail Digital Delivery (RDD)
    * Sales Service
    * Serial Number Generator
  * Serverless Applications (Python)
    * Data Management API
    * Magento Order Processing System (MOPS)
    * SEAMS
  * API Frontends
    * Authorization API (a Customer Services/Authorization Services frontend)
    * Legacy API (a Customer Services frontend)
    * Private API (frontend for ERP services)
    * Public API (frontend for Customer Services update)
  * Services
    * Adobe Campaign Export (shared with Team Vintage)
    * Yotpo Export
  * Bots
    * iZac
  * Data Input Interfaces
    * Product Tool
    * B2B Invoice Sheet
    * Serial Generating Spreadsheet
  * Test Automation
    * Service Tests
    * Database Tests
* Versioning approaches: semver
* Wiki search terms: 
  * "Application Integration"
  * "Information Systems"
  * "Application Release Management"
  * "ait"
  * "is"
* Chat tool channels: 
  * #team-is-taco2 
  * #team-itai-dev 
  * #team-it2
* Time of daily sync meeting: 
  * async in #team-is-taco2
  * 9:30 EST - Daily Huddle
  * 3:30 EST - Code & Infrastructure Review

> Team type: (Stream-Aligned, Enabling, Complicated Subsystem, Platform)

### What we're currently working on

* Our services and systems: MOPS/OOPS; support tickets for GTM and Finance
* Ways of working: Scrumban/BDD
* Wider cross-team or organisational improvements: integration w/ NAS

### Teams we currently interact with

| Team name/focus | Interaction Mode | Purpose | Duration |
| --------------- | ---------------- | ------- | -------- |
| IT | Collaboration | mutual support | since 2015 |
| GTM/MarTech | SKUs-as-a-Service | Operational Support | since 2015 |
| Nucleus | Facilitating | system support/company release planning | since 2015 |
| Finance | Support-as-a-Service | Operational Support | since 2015 |
| Legal / Customer Care | Erasure-as-a-Service | Operation Support | since 2018 |
| Artist Relations / QA | NFRs-as-a-Service | Operational Support | since 2020 |
| ERP | Collaboration | modernized fulfillment process for iZotope | since April 2022 |

> Team Interaction Modes: (Collaboration, X-as-a-Service, Facilitating)

### Teams we expect to interact with soon

| Team name/focus | Interaction Mode | Purpose | Duration |
| --------------- | ---------------- | ------- | -------- |
| NAS (name tbd) | Collaboration | mutual support | since July |

