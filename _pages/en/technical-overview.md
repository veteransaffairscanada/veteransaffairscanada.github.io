---
layout: page
title:  "Technical Overview"
lang: en
permalink: "/technical/"
trans_url: "/technique/"
---

**Overview**

*Find benefits and services* is a web application developed using the `Next.js` framework. It will be referred to as *the App* in the following.

Benefits Data associated with *the App* is stored using `Airtable`, a SaaS product that serves as both a relational database and content management system. *The App* reads data from and in rare cases (e.g. when a user submits feedback), writes data to `Airtable` via a web API.

**Benefits Data**

`Airtable` includes a convenient web interface (which, to a large extent, operates like a spreadsheet) that administrators of *the App* (i.e. VAC staff) can use to keep benefits data current and accurate. This includes associating benefits with a small set of eligibility requirements and categories, relationships that are reflected in *the App* UI as filters. Furthermore, most of the headings and labels in *the App* UI can also be changed in `Airtable`, allowing for simple textual changes to the App to be made without manipulating code. Changes to `Airtable` data can be reflected in *the App* immediately for QA or release to end-users.

**The App**

The *App* is essentially a client-side web application, though its constituent pages can and sometimes are rendered on the web server for various performance gains and connectivity/browser scenarios. The code that defines it is publicly available on [GitHub](https://github.com/cds-snc/vac-benefits-directory). The repository also contains further information about the stack and methodology used to develop *the App* including...
* How to run the code
* Arguments for why the major components of the stack were chosen
* The deployment process observed during development and the tools supporting it
* The automated test coverage of and patterns used in the code base
