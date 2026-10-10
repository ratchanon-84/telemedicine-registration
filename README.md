## Overview

Reduced registration-related calls by 80% allowing 4 out of 5 patients to register without calling hospital staff. Built the system with Next.js, Google Apps Script and Google Sheets. Implemented nurse notifications via the LINE Messaging API and CI/CD using free-tier cloud services.

## System Architecture

```mermaid
flowchart TD
    A[Patient] --> B[Next.js Web Application]
    B -->|API Request| C[Google Apps Script]
    C -->|Store Registration Data| D[(Google Sheets)]
    C -->|Send Notification| E[LINE Messaging API]
    E --> F[Nurse]
```

## Notification Preview

Registration notifications are sent to nurses via the LINE Messaging API using Flex Messages.

![LINE Messaging Notification](https://res.cloudinary.com/dpa96jvla/image/upload/v1779584919/%E0%B8%94%E0%B8%B5%E0%B9%84%E0%B8%8B%E0%B8%99%E0%B9%8C%E0%B8%97%E0%B8%B5%E0%B9%88%E0%B8%A2%E0%B8%B1%E0%B8%87%E0%B9%84%E0%B8%A1%E0%B9%88%E0%B9%84%E0%B8%94%E0%B9%89%E0%B8%95%E0%B8%B1%E0%B9%89%E0%B8%87%E0%B8%8A%E0%B8%B7%E0%B9%88%E0%B8%AD_1_v8yqdd.png)

## Tech Stack

* **Frontend:** Next.js, Tailwind CSS
* **Backend:** Google Apps Script
* **Data Storage:** Google Sheets
* **Messaging Integration:** LINE Messaging API

## Publication

The project was adopted by the Mayor of Kamphaeng Phet Municipality.

[![Project Publication](https://res.cloudinary.com/dpa96jvla/image/upload/v1789533029/1747791924700_124000_g4_vc7jbg.jpg)](https://www.kppmu.go.th/news-detail?hd=1&id=124000)
