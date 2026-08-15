# ShareGuard 365

> Helps IT admins and MSPs instantly audit, visualize, and enforce secure-by-default sharing policies across all M365 tenants from one dashboard.

## Overview

ShareGuard 365 connects to Microsoft Graph to scan all SharePoint sites, OneDrive accounts, and Teams channels for overly permissive sharing links, anonymous access, and policy drift from Microsoft's secure-by-default sharing standards. It surfaces risk scores per site and user, generates board-ready compliance reports, and lets admins bulk-remediate non-compliant links in one click. MSPs can manage multiple tenants from a single pane of glass with white-label PDF reporting.

## Problem This Solves

Admins have no easy way to see who shared what externally, whether anonymous links are still active, or which sites violate the new secure-by-default sharing policies — manually auditing this in the M365 admin portal is slow, incomplete, and non-exportable.

## Target Audience

MSPs managing 10–200 seat M365 tenants and IT admins in mid-market orgs (200–2000 users) who are responsible for data governance and need to prove sharing hygiene to auditors or leadership.

## Tech Stack

PHP, Microsoft Graph, PowerShell, OAuth2 Multi-tenant

## Quick Start

```powershell
# Clone the repository
git clone https://github.com/shareguard-365.git
cd shareguard-365

# One-click install & run
.\Install.ps1

# Or run the script directly
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
.\scripts\{shareguard-365}.ps1
```

## Usage



## Monetization Strategy

SaaS Subscription: $29/month per single tenant, $79/month for MSP multi-tenant (up to 10 tenants), $149/month for unlimited tenants. Annual plans at 20% discount. Optional one-shot PowerShell Source Code bundle at $149 for self-hosters.

| Metric | Value |
|--------|-------|
| Revenue Potential | HIGH |
| Estimated Effort  | 1-3months |

## About the Author