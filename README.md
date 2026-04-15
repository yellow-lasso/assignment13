# Congressional Trade Disclosure Analysis Tool (Web Application – Assignment 13)

## Overview

This project extends the Congressional Trade Disclosure Analysis Tool by adding a RESTful API that allows external systems to access application data in JSON format.

In this version, the application exposes secure API endpoints that enable retrieval of trade data for authenticated users. These endpoints return structured JSON responses and include proper HTTP status codes for error handling.

This assignment represents a key step in transforming the application into a service that can be consumed by other applications, scripts, or integrations.

---

## Features

### 1. REST API Implementation

- API endpoints are grouped under the `/api/v1/` prefix.
- The API returns data in JSON format instead of HTML.
- Endpoints allow programmatic access to trade data.

---

### 2. Get All Trades Endpoint

- Endpoint:
