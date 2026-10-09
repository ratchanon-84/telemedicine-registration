## Overview

A Telemedicine Registration System that allows patients to register for remote healthcare services through a web application. The system stores registration data in Google Sheets and notifies nurses through the LINE Messaging API.

## System Architecture

```mermaid
flowchart TD
    A[Patient] --> B[Next.js Web Application]
    B -->|API Request| C[Google Apps Script]
    C -->|Store Registration Data| D[(Google Sheets)]
    C -->|Send Notification| E[LINE Messaging API]
    E --> F[Nurse]
```

## Tech Stack

* **Frontend:** Next.js, Tailwind CSS
* **Backend:** Google Apps Script
* **Data Storage:** Google Sheets
* **Messaging Integration:** LINE Messaging API

## Publication

The project was featured on the Kamphaeng Phet Municipality website.

[![Project Publication](https://res.cloudinary.com/dpa96jvla/image/upload/v1789533029/1747791924700_124000_g4_vc7jbg.jpg)](https://www.kppmu.go.th/news-detail?hd=1&id=124000)

[View the publication on the Kamphaeng Phet Municipality website](https://www.kppmu.go.th/news-detail?hd=1&id=124000)
