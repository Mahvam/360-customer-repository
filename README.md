# 360-Degree Customer Repository

A multi-source automation pipeline that consolidates customer data from across your tech stack into a single, searchable source of truth.

## Overview

The 360-Degree Customer Repository is a data integration system designed to give your entire team instant access to complete customer context: from call transcripts, to support tickets, to CRM activity, to Slack conversations, all searchable by account name in one place.

No more switching between tools. No more missing context. One account lookup gives you everything.

## The Pipeline

Data flows from four sources through Zapier normalization into Airtable:

- **Grain** (Call transcripts) 
- **HubSpot** (Notes, calls, deals)
- **Zendesk** (Support tickets)
- **Slack** (#customer-success channel)

→ **Zapier** (Normalize, tag, attach Customer ID, route)

→ **Airtable** (Single source of truth with customer data, signals, and Slack threads linked by account)

→ **Team Access** (Searchable by account name for CTO, Sales, Customer Success)

## How It Works

1. **Data Collection**: Four systems feed into the pipeline automatically
2. **Normalization & Routing** (Zapier): Data is standardized, tagged with customer ID, and routed to Airtable
3. **Single Source of Truth** (Airtable): All customer data lives in one place with complete event history
4. **Team Access**: Anyone on the team can search by account name and see everything

## Key Benefits

- **Complete Context**: One lookup gives you calls, tickets, notes, conversations
- **No Context Switching**: Stop bouncing between tools
- **Real-Time Signals**: Events flow in automatically
- **Team Alignment**: Sales, CS, and CTO see the same version of truth
- **Searchable**: Find any account instantly

## Tech Stack

Grain | HubSpot | Zendesk | Slack → Zapier → Airtable

## Getting Started

All four source systems connect to Zapier automations that normalize and route data to your Airtable base, where team members can search by account name.

---
