## Application

Create a JVM based backend application using REST. That contains the following endpoints:

* GET /api/stocks (get a list of stocks)
* POST /api/stocks (create a stock)
* GET /api/stocks/1 (get one stock from the list)
* PUT /api/stocks/1 (update the price of a single stock)
* DELETE/api/stocks/1 (delete a single stock)

The initial list of stocks should be created on application start-up. Use a database that is most appropriate for this use-case.
The stock object contains at least the following fields:

* ID
* name (String)
* currentPrice (Amount)
* lastUpdate (Timestamp)

Configure the GET /api/stocks endpoint to support request pagination (the number of stocks per page must be configurable).

Each endpoint must be compliant with the HTTP/1.1 and REST standards.

Use Spring Boot to build and test this application.

Nice to have (Optional)

The codebase should have a comprehensive documentation of its API (Ex: OpenAPI).

The codebase should target Java 8 or higher.

## Implementation
Treat this application as a real MVP that should go to production.

All main use cases must be covered by at least one unit or(and) integration test.


Good luck!
