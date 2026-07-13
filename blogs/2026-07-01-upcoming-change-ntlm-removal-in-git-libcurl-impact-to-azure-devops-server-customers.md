---
title: "Upcoming Change: NTLM Removal in Git (libcurl) – Impact to Azure DevOps Server Customers"
url: "https://devblogs.microsoft.com/devops/upcoming-change-ntlm-removal-in-git-libcurl-impact-to-azure-devops-server-customers/"
date: "2026-07-01"
author: "Gloridel Morales"
feed_url: "https://devblogs.microsoft.com/devops/feed/"
---
In September 2026, libcurl will remove NTLM authentication support, affecting Git operations over HTTPS for Azure DevOps Server customers who rely on NTLM. The post notes that Negotiate (SPNEGO) authentication can silently fall back to NTLM when Kerberos is not properly configured, potentially impacting more environments than expected. Customers are advised to validate their authentication method and transition to Kerberos before the deadline to avoid disruption.
