# Azure RBAC Automation Tool

## Overview
This project provides a Python-based solution to extract and analyze Azure RBAC role assignments across subscriptions and resource groups.

It is designed to support:
- Governance visibility
- Access auditing
- Role assignment tracking

## Features
- Export RBAC role assignments
- Generate structured output (Excel)
- Helps identify over-privileged access

## Use Case
In large Azure environments, tracking "who has access to what" becomes complex.  
This tool simplifies RBAC visibility and supports governance initiatives.

## Prerequisites
- Python 3.x
- Azure CLI login (`az login`)

## Installation
```bash
pip install -r requirements.txt
