# Job Intelligence Engine

**Postman · REST APIs · JavaScript · JSON · OAuth 2.0 / PKCE · Salesforce**

**Project type:** API Integration, Data Processing & CRM Automation  
**Status:** Working prototype — further development in progress

## 1. Business Case

### Business Problem

Job opportunities are distributed across multiple recruitment platforms, making it difficult to consolidate, compare and prioritize relevant vacancies.

Manual job searching introduces several challenges:

- Fragmented data across multiple platforms
- Inconsistent job descriptions and data structures
- Difficulty prioritizing opportunities based on relevant skills
- Repetitive manual data entry
- Limited visibility into opportunities already identified

### Business Objective

Develop a job intelligence solution that retrieves job opportunities through APIs, processes and scores relevant information, and transfers structured records into Salesforce for tracking.

### Key Business Questions

1. How can job opportunities from different sources be retrieved programmatically?
2. How can API responses be transformed into a consistent data structure?
3. How can job opportunities be scored against predefined criteria?
4. How can structured job records be imported into Salesforce?
5. How can this process reduce repetitive manual work?

## 2. Solution Overview

The solution uses Postman to execute external job API requests, JavaScript to process and score results, and Salesforce as a destination for structured job records.

**Implemented capabilities:**

- Configured job-search API requests in Postman.
- Worked with HTTP methods, query parameters, JSON responses and API tests.
- Developed and revised JavaScript job-fit scoring logic.
- Configured Salesforce API access using OAuth 2.0 / PKCE.
- Created a custom Salesforce object for job tracking.
- Successfully imported structured job records into Salesforce.
- Validated API requests and integration results through testing.

## 3. Technical Architecture

External Job APIs → Postman → JSON Processing & JavaScript Scoring → Salesforce REST API → Custom Job Tracking Object

## 4. Technologies

| Technology | Application |
|---|---|
| Postman | API requests, testing and collections |
| REST APIs | Retrieval and transfer of structured data |
| JavaScript | Response processing and fit scoring |
| JSON | Data exchange and transformation |
| OAuth 2.0 / PKCE | Salesforce API authentication |
| Salesforce | Custom object, data storage and job tracking |
| GitHub | Version control and technical documentation |

## 5. Testing and Results

**Verified outcomes:**

- Successful execution of external job API requests
- Successful Salesforce API authentication
- Passing API tests
- Successful bulk import of job records into Salesforce

## 6. Current Limitations and Next Steps

The solution remains an evolving prototype. Potential enhancements include scheduled API retrieval, improved duplicate detection, automated updates, scoring calibration, and reporting dashboards.

## 7. Portfolio Artifacts

The repository will include sanitized Postman collections, selected JavaScript examples, architecture documentation and test evidence. No active API credentials or personal access tokens will be published.
