## Overview

A Telemedicine Registration System that reduced patient registration steps by 80% from 5 to 1. Built with Next.js, Google Apps Script, and Google Sheets, with nurse notifications via the LINE Messaging API and CI/CD implemented using free-tier cloud services.

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
