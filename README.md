# **EaglerCert**

Unblocked `backup.cert` — always up-to-date, auto-refreshed via GitHub Actions 🔁

## What is this?

This repo provides a continuously updated `backup.cert` file fetched from:

> https://deev.is/eagler/backup.cert

It updates automatically every hour (or on manual trigger) using a GitHub Actions workflow.

## How it works

- Pulls `backup.cert` from the source URL
- Verifies the file is available (HTTP 200)
- Commits and pushes any changes directly to this repo

## Usage

You can reference or download the latest version of `backup.cert` directly from the root of this repository:

