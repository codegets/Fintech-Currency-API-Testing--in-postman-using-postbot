# Fintech Currency API Testing — Postman Collection

## Project Overview
A comprehensive API testing suite for the Frankfurter Exchange Rate API — 
a real world financial data API. Built using Postman with AI assisted 
test script generation via Postbot.

## Why This Project
As a QA Engineer with 4+ years of fintech experience at Visa, Capital One 
and Early Warning Services — I understand how critical accurate financial 
data is. This project applies real QA methodology to test a live currency 
exchange rate API used in financial applications.

## Test Coverage

### 1. GET Latest USD to INR Rate
- ✅ Status code is 200
- ✅ Response has amount, base, date and rates fields
- ✅ Base currency is USD
- ✅ INR rate exists and is a number greater than 0

### 2. GET Historical USD to INR Rate (2024)
- ✅ Status code is 200
- ✅ Response has all required fields
- ✅ Base currency is USD
- ✅ Historical INR rate exists and is valid

### 3. GET Invalid Currency Code — Negative Test
- ✅ Status code is NOT 200 for invalid currency
- ✅ Response contains appropriate error message

## Key Findings
- Current rate (June 2026): 1 USD = ₹95.12
- Historical rate (January 2024): 1 USD = ₹83.17
- INR weakened by ₹11.95 against USD in 2.5 years
- API handles invalid currency codes gracefully with 404 error
- API returns last working day rate when public holiday is requested

## Tools Used
- Postman — API testing platform
- Postbot AI — AI assisted test script generation
- JavaScript — test assertions
- Frankfurter API — free public exchange rate API

## Test Results
- Total tests: 10
- Passed: 10
- Failed: 0
- Pass rate: 100%

## How to Run
1. Download the collection JSON file
2. Open Postman
3. Click Import → Upload the JSON file
4. Click Send on each request
5. Check Test Results tab

## Skills Demonstrated
- REST API testing — GET requests
- Positive and negative test scenarios
- AI assisted automation using Postbot
- Financial domain knowledge
- Status code validation
- Response schema validation
- Error handling verification

## About
Built by Lavanya — QA Engineer with fintech experience at Visa, 
Capital One and Early Warning Services (Zelle).

GitHub: github.com/codegets
LinkedIn: linkedin.com/in/lavanya-a19079220
