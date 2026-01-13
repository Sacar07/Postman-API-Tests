# Project Overview

### This repository contains comprehensive API testing projects performed using Postman on public demo APIs such as GoRest API, Books API and MockAPI. The purpose of this work is to demonstrate practical API testing skills including:

1) Response validation with Postman assertions

2) API chaining and workflow automation

3) Authentication and authorization testing

4) Environment and collection variable management

5) Data-driven testing

6) File upload testing

7) Negative and positive scenario coverage

### Each collection in this repo includes structured test cases and assertions that validate expected behavior and support robust testing practices. Screenshots and evidence of execution are provided to showcase test results and logic.

# Tools used:
- Postman
- REST APIS
- JSON
- Chrome devTools
- Github
  
# Issue Faced:
401 Unauthorized while sending Bearer token 

## Root Cause:
API endpoint was outdated (.glitch.me) and redirected to a new domain (.click). Postman drops Authorization headers during redirects.

## Fix:
Used the final endpoint https://simple-books-api.click/orders directly.
