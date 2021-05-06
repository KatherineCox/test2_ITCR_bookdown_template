# PIs and Lab Managers

## Introduction

### Who is this guide for?

### What's in this guide?

### Philosophy

## Account Setup

This guide provides an opinionated walkthrough on how to set up AnVIL for your lab, based on experiences from many labs actively using AnVIL.  Following our recommendations will help you configure your team so that you can more clearly see where charges are coming from and have greater control over which users can spend your money and access your data.

### Goals for this guide

<img src="02-getting_started_pis_files/figure-html//162GS7ArBPM4w_rPazcUrpnoEKT7jx9i7fpPQkH_iC_0_gd5c49c5c55_0_165.png" title="List of goals for this guide: 1) get your accounts, 2) set up billing, 3) set up your lab members to do research on AnVIL, and 4) monitor and manage spending." alt="List of goals for this guide: 1) get your accounts, 2) set up billing, 3) set up your lab members to do research on AnVIL, and 4) monitor and manage spending."  />

### Overview

AnVIL uses [Terra](https://anvil.terra.bio/) to run analyses.  Terra operates on Google Cloud Platform, so you’ll pay for all storage and analysis costs through a Google account linked to Terra.  The costs are the standard Google Cloud Platform fees for storing and moving data as well as executing an analysis.  These costs are passed along through Terra without any markup.

<img src="02-getting_started_pis_files/figure-html//162GS7ArBPM4w_rPazcUrpnoEKT7jx9i7fpPQkH_iC_0_gd84a304855_0_138.png" title="Diagram outlining the roles of Google and Terra for AnVIL.  A 'PI' signs in with a Google ID, which lets them create a Google Billing Account.  Money flows from the Google Billing Account to a Terra Billing Project, and then to individual Terra Workspaces" alt="Diagram outlining the roles of Google and Terra for AnVIL.  A 'PI' signs in with a Google ID, which lets them create a Google Billing Account.  Money flows from the Google Billing Account to a Terra Billing Project, and then to individual Terra Workspaces"  />

1. Create a Google account
1. Set up Google Billing (and claim your free credits!).
    + Add an administrator or viewer (optional)
1. Link Terra to the Google Billing Account
1. Create Terra Billing Projects
1. Set budgets and alerts (optional, but highly recommended)
1. Add users and Workspaces


