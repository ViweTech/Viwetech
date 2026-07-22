# Soc Analyst Incident Response Case Studies

Introduction to phishing

In this case study I am tasked to Identify and close all true positive alerts
Monitor and analyze read time alerts 
Identify and Document critical events ,such as suspicious emails and attachments
I am must create detailed case reports based on my observations to help the team understand 
the full scope of alerts and malicious activity.

tools to be used

SIEM AND SPLUNK

These case studies are based on lab environments and scenarios on Tryhackme

Example Case Study Report

# Incident Response Summary

## Alert

Alert triggered by an Inbound email contains one more external links due to potentially suspicious Traits

## Alert Information

| Field | Value |

| Time | 22 July 2026 10:33 |
| Data Source | Email |
| Recipient | c.allen@thetrydaily.thm |
| Sender | no-reply@m1crosoftsupport.co |
| Subject | Unusual Sign-In Activity |
| Severity | Medium |  

## Investigation

## Email Analysis

The sender Domain Impersonates Microsoft and replaces Letter "I" with number "1"

Legitmate Domain 

Microsoft.com

Observed Domain 

M1crosoftsupport.co

([image alt]https://github.com/ViweTech/Viwetech/blob/e6f28951707ef9b93a439de1a8f4a18dca09c79c/Screenshot%20(7).png)

## The clues or what Indicated this is the following

Typosquatting
brand impersonation
Urgency "48"hrs
Credential harvesting

## Classification

The alert is True positive

The reason 

The Domain is spoofed and is trying to collect the user details

## Affected entities

The reciepient

c.allen@thetrydaily.thm

Sender 

moreply@m1crosoftsupport.co

## Remediation

Quarantine the email
Block the sender
Investigate endpoint
Search if thers other affected Users

## Lessons Learned

It is Easy to be caught by a phishing technique 
It is very important to verify the Domain before entering credatials
Should a user be suspicious of the email they should report early

## My Overall Take of this phishing technique

As mentioned on lessons learned it is very important to verify the Domain to avoid such technique
this was a very exciting challenge to me I did take some time when going through this challenge as it is one of my first 
projects and I did manage to see that this is typosquatting as learnt in My Comptia Security+





