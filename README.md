# mulesoft
Mulesoft API Design, Build and Deploy 

🧩 MuleSoft Integration Project Portfolio
✅ Core Applications
App1: emp-sapi Introductory Hello World application demonstrating basic MuleSoft setup.

App2: test-flows Demonstrates Sync and Async flows using SubFlows and Private Flows.

App3: emp-sapi-v1 Oracle Database CRUD operations:

Add Employee

Delete Employee

Fetch Employee by ID

Fetch All Employees

📬 Messaging & Queue Integrations
App4: jms-app ActiveMQ integration with Queue and Topic using JMS Connector.

App5: jms-push-operations Push and read operations from ActiveMQ Queue using JMS Connector.

App10: rest-over-jms

Transfers data from JMS Queue to REST service using XML payload.

Consumes REST service to delete employee using URI parameters and Choice router.

📁 File & FTP Operations
App6: ftp-app Reads CSV data from VSFTP using FTP Connector.

App7: database-to-ftp-excel Dumps database records into Excel via VSFTP.

App8: emp-csv-database Bulk inserts CSV data into database using Scheduler and File Connector.

🌐 REST & SOAP Services
App9: consume-json-rest-service Transfers data between REST services using REST Request Connector.

App17: soap-service Sample SOAP Provider using SOAP Router (instead of APIkit).

App18: ws-consumer-demo Consumes SOAP service and applies transformation to the response.

🔐 Environment & Security Configurations
App11: prop-demo Uses environment-specific property files for deployment.

App12: secure-prop-demo Uses Mule Secure Configuration Module to encrypt connector credentials.

⚠️ Error Handling Framework
App13: error-handling-demo Demonstrates:

On Error Propagate

On Error Continue

Raise Error

Centralized Error Handler

📘 API Design & RAML
App14: emp-onboard-sapi.raml RAML specification for employee onboarding API.

App15: emp-onboard-api API implementation from RAML with:

Global Connector Configurations

Global Error Handler

APIkit Router

Modular Flow References

App16: emp-hr-sapi Fragmented RAML specification for HR services.

🔣 DataWeave Operations
App19: dataweave-demos Covers:

Time Conversions

Operators, DataTypes, Type Coercions

Math & String Functions

User-Defined Functions

Map, Filter, and Object operations

🔄 MuleSoft Scopes & Batch Processing
App20: mule-scope-demo Demonstrates:

Target, Async, Try/Catch, Until scopes

On Error Continue / Propagate

ForEach Batch (sync)

Scatter-Gather for multi-table inserts

Batch Job Connector (async)

Batch Step with processor and aggregator
