# Day 01 – Getting Started with GCP (Free Trial & Console Basics)

## What I Learned
- **Google Cloud Overview**:  
  GCP offers 200+ services across compute, networking, storage, AI/ML, DevOps, and more. As a beginner, it’s important to start with the fundamentals and understand which services are included in the **free trial**.  

- **Free Trial Account**:  
  - New users get **$300 credits valid for 90 days**.  
  - Some services are always free (e.g., 1 f1-micro VM, 5GB Cloud Storage).  
  - Usage outside the free tier is charged at standard rates, but you won’t be overcharged unless you upgrade to a paid account.  
  - Payment methods supported: credit card, debit card, PayPal (and UPI in some regions).  

- **Default Setup**:  
  - When you sign up, GCP automatically creates a **billing account** and a **default project**.  
  - Each project has a **unique project ID**, which differentiates them even if names are the same.  

- **Google Cloud Console**:  
  - Dashboard shows pinned services, real-time API requests, and monitoring widgets.  
  - Services can be pinned/unpinned for quick access.  
  - Resources can be searched directly (e.g., “Compute Engine” for VMs).  

- **Ways to Interact with GCP**:  
  1. **Console (UI)** – Click through the web interface.  
  2. **APIs** – Programmatic access for automation.  
  3. **Cloud Shell (CLI)** – Pre-configured shell with `gcloud` SDK, code editor, and utilities.  

- **Cloud Shell Features**:  
  - Free for all users.  
  - Includes terminal, file upload/download, web preview for apps, and an online code editor (similar to VS Code).  
  - Great for running quick commands and editing files without local setup.  

- **Free Tier Limits (Examples)**:  
  - 1 non-preemptible **E2-micro VM** in specific US regions (per month).  
  - 30 GB SSD storage free each month.  
  - Services like GKE, BigQuery, Cloud Run also have limited free usage.  
  - Anything beyond the limit is billed at standard rates.  

- **Important Notes**:  
  - Production images with premium OS licenses (e.g., Windows Server, SQL Server) are **not free**.  
  - Always set up **budgets and alerts** to monitor usage.  
  - Free trial users don’t get full technical support beyond the initial period.  

## Reflection
Day-01 introduced the fundamentals of GCP, how to set up a free trial account, and how to navigate the console. I learned the difference between free tier vs. paid resources, explored Cloud Shell and the project structure, and understood how to safely practice without overspending. This foundation prepares me for provisioning my first VM and working with core GCP services.  
