# Level 1 --- Web & Python Backend Foundations

> Move from writing standalone Python programs to understanding how real
> backend applications communicate over the web.

**Stage:** Backend Foundation\
**Prerequisite:** Python Foundations\
**Learning Model:** Watch → Read → Reason → Inspect → Code → Test →
Build\
**Next:** Level 2 --- Django Web Development

------------------------------------------------------------------------

## 1. What Backend Development Actually Does

### Client--Server Architecture

[![Client Server
Architecture](https://img.youtube.com/vi/Dg1U-jwVUrg/maxresdefault.jpg)](https://www.youtube.com/watch?v=Dg1U-jwVUrg)

**[▶ Client Server Architecture --- System Design
Tutorials](https://www.youtube.com/watch?v=Dg1U-jwVUrg)**

Focus on:

-   Client responsibilities
-   Server responsibilities
-   Requests and responses
-   Separation of frontend and backend logic
-   How applications communicate over a network

### Think About It

> When you click **"Book Seat"** on a transport website, what should
> happen in the browser and what should happen on the backend?

------------------------------------------------------------------------

## 2. HTTP Fundamentals

### HTTP Crash Course

[![HTTP Crash
Course](https://img.youtube.com/vi/iYM2zFP3Zn0/maxresdefault.jpg)](https://www.youtube.com/watch?v=iYM2zFP3Zn0)

**[▶ HTTP Crash Course &
Exploration](https://www.youtube.com/watch?v=iYM2zFP3Zn0)**

Focus on:

-   Request
-   Response
-   URL
-   Headers
-   Body
-   GET
-   POST
-   PUT
-   PATCH
-   DELETE
-   Status codes
-   Content-Type

### Reasoning Exercise

For each action, decide which HTTP method would normally be appropriate:

1.  View all buses
2.  Create a booking
3.  Change passenger details
4.  Cancel a booking
5.  Retrieve one booking
6.  Update only the passenger's phone number

Defend each choice.

------------------------------------------------------------------------

## 3. JSON & Serialization

### Python JSON Tutorial --- Corey Schafer

[![Python JSON
Tutorial](https://img.youtube.com/vi/9N6a-VLBa2I/maxresdefault.jpg)](https://www.youtube.com/watch?v=9N6a-VLBa2I)

**[▶ Python Tutorial: Working with JSON Data using the json Module ---
Corey Schafer](https://www.youtube.com/watch?v=9N6a-VLBa2I)**

Focus on:

-   JSON structure
-   Python dictionaries and JSON objects
-   Python lists and JSON arrays
-   `json.loads()`
-   `json.dumps()`
-   Reading JSON
-   Writing JSON
-   Serialization
-   Deserialization

### Practice

``` python
route = {
    "route_code": "EMP-DUR",
    "origin": "Empangeni",
    "destination": "Durban",
    "distance_km": 170,
    "available_seats": 12
}
```

Perform:

``` text
Python Dictionary
        ↓
Serialization
        ↓
JSON String
        ↓
Deserialization
        ↓
Python Dictionary
```

Then explain why an API cannot simply send a Python dictionary across
the internet and expect every programming language to understand it.

------------------------------------------------------------------------

## 4. APIs & REST

### REST API Concepts and Examples

[![REST API
Concepts](https://img.youtube.com/vi/7YcW25PHnAA/maxresdefault.jpg)](https://www.youtube.com/watch?v=7YcW25PHnAA)

**[▶ REST API Concepts and Examples ---
WebConcepts](https://www.youtube.com/watch?v=7YcW25PHnAA)**

Focus on:

-   APIs
-   Resources
-   Endpoints
-   HTTP methods
-   Requests
-   Responses
-   REST
-   Retrieving resources
-   Creating resources
-   Modifying resources

### REST Reasoning Exercise

Suppose BIH develops a project-management API.

Resources include:

``` text
participants
projects
teams
tasks
```

Design endpoints to:

-   Retrieve all projects
-   Retrieve project 17
-   Create a project
-   Update project 17
-   Delete project 17
-   Retrieve tasks belonging to project 17

> Do not write Python yet. Design the API first.

------------------------------------------------------------------------

## 5. Django Preview

At this stage, Django is only a preview.

[![Python Django Web
Framework](https://img.youtube.com/vi/F5mRW0jo-U4/maxresdefault.jpg)](https://www.youtube.com/watch?v=F5mRW0jo-U4)

**[▶ Python Django Web Framework --- Full Course for
Beginners](https://www.youtube.com/watch?v=F5mRW0jo-U4)**

Only watch introductory sections covering:

-   Django introduction
-   Virtual environments
-   Creating a project
-   Project structure
-   Applications
-   URLs
-   Views
-   Requests
-   Responses

> Django becomes the main focus in **Level 2 --- Django Web
> Development**.

------------------------------------------------------------------------

## 6. Practice --- Inspect HTTP

### Chrome DevTools --- Network Tab

[![Chrome DevTools
Network](https://img.youtube.com/vi/hPB-Sgy1uoM/maxresdefault.jpg)](https://www.youtube.com/watch?v=hPB-Sgy1uoM)

**[▶ Using Chrome DevTools Network Tab for Inspecting Network
Activity](https://www.youtube.com/watch?v=hPB-Sgy1uoM)**

Focus on:

-   Recording network activity
-   Request details
-   Headers
-   Fetch/XHR
-   Filtering requests
-   Failed requests
-   Network timing

### Inspection Exercise

Open a normal website and use:

**Developer Tools → Network**

Identify at least:

-   1 HTML request
-   1 CSS request
-   1 JavaScript request
-   1 image request
-   1 Fetch/XHR request, if available

Record:

  Property        Value
  --------------- -------
  Request URL     
  Method          
  Status          
  Content-Type    
  Response Size   

------------------------------------------------------------------------

## 7. Logic Lab --- Transport Route API

No additional tutorial is required here.

Design:

``` text
GET /routes/EMP-DUR
```

Before coding, specify:

  Component                Your Decision
  ------------------------ ---------------
  Resource                 
  HTTP Method              
  Path                     
  Input                    
  Validation               
  Business Rules           
  Successful Status Code   
  Failure Status Codes     
  Response Format          

### Technical Reasoning

Defend:

1.  Why is `GET` appropriate?
2.  Should the route code be a path parameter or request body?
3.  What happens when the route does not exist?
4.  What happens when the route is inactive?
5.  Should the frontend determine whether the route is active?
6.  Which information should the backend control?

------------------------------------------------------------------------

## 8. Logic Lab --- Trade Quote Endpoint

Design:

``` text
POST /trade/quote
```

Input:

``` json
{
  "quantity": 100,
  "unit_cost": 25,
  "transport_cost": 450,
  "margin_percentage": 20
}
```

Determine:

-   Product cost
-   Total landed cost
-   Required revenue
-   Recommended unit selling price

### Architecture Question

Decide whether each calculation belongs in:

-   **Frontend**
-   **Backend**
-   **Either**

Defend your decisions based on:

-   Security
-   Consistency
-   Business rules
-   Maintainability
-   Trust

------------------------------------------------------------------------

## 9. API Consumption with Python

### Python Requests --- Corey Schafer

[![Python
Requests](https://img.youtube.com/vi/tb8gHvYlCFs/maxresdefault.jpg)](https://www.youtube.com/watch?v=tb8gHvYlCFs)

**[▶ Python Requests Tutorial --- Corey
Schafer](https://www.youtube.com/watch?v=tb8gHvYlCFs)**

Focus on:

``` python
requests.get()
requests.post()
response.status_code
response.text
response.json()
```

Also understand:

-   GET requests
-   POST requests
-   Parameters
-   JSON responses
-   Authentication concepts
-   Timeouts
-   Exceptions
-   Failure handling

Your program should expect that networks and APIs can fail.

``` text
Send Request
     ↓
Check Connection
     ↓
Check Status Code
     ↓
Parse JSON
     ↓
Validate Required Fields
     ↓
Use Data
     ↓
Handle Failure
```

------------------------------------------------------------------------

## 10. Environment Configuration

### Python Dotenv & Environment Variables

[![Python
Dotenv](https://img.youtube.com/vi/pyUyeepCOjE/maxresdefault.jpg)](https://www.youtube.com/watch?v=pyUyeepCOjE)

**[▶ How to Use Python Dotenv to Manage Environment
Variables](https://www.youtube.com/watch?v=pyUyeepCOjE)**

Focus on:

-   Environment variables
-   `.env`
-   `python-dotenv`
-   `os.getenv()`
-   API keys
-   Database credentials
-   Secret configuration
-   `.gitignore`

### Security Exercise

Explain why this is dangerous:

``` python
API_KEY = "123456789-secret-key"
DATABASE_PASSWORD = "admin123"
```

Especially when the project is pushed to GitHub.

------------------------------------------------------------------------

## 11. Practice Problems

At this point, reduce video usage.

``` text
WATCH
   ↓
UNDERSTAND
   ↓
REASON
   ↓
APPLY
   ↓
BUILD
```

### Problem 1 --- Fuel Price Service

Design:

``` text
POST /fuel/calculate
```

Determine:

-   Input
-   Validation
-   Business logic
-   Success response
-   Failure responses
-   Status codes

### Problem 2 --- Bus Seat Availability

Design:

``` text
GET /buses/{bus_id}/availability
```

Return:

``` text
available
almost_full
full
```

Define exactly when each state occurs.

### Problem 3 --- Currency Conversion API

Design:

``` text
POST /currency/convert
```

Explain why a production backend should normally obtain trusted
exchange-rate data rather than accepting the exchange rate supplied by
every client.

### Problem 4 --- Import Duty Calculator

Design validation for:

-   Product value
-   Duty rate
-   Missing values
-   Negative values
-   Strings instead of numbers
-   Zero
-   Unreasonably large values
-   Malformed JSON

### Problem 5 --- Shipment Tracking

Possible states:

``` text
created
collected
in_transit
delayed
delivered
cancelled
```

Design valid and invalid state transitions.

------------------------------------------------------------------------

# Level 1 Challenge --- Trade & Transport Service

At this point, stop following tutorials.

Build a small Python backend/API prototype representing:

``` text
Routes
Fare Quotes
Shipments
Trade Quotes
```

The project must demonstrate:

-   HTTP understanding
-   RESTful endpoint design
-   JSON request/response handling
-   Python business logic
-   Input validation
-   Error handling
-   Environment configuration
-   Endpoint testing

The exact architecture is your responsibility.

------------------------------------------------------------------------

## Technical Defence

Be prepared to explain:

1.  Why did you choose each HTTP method?
2.  Why did you choose each status code?
3.  Which data should the client be allowed to provide?
4.  Which business rules must remain server-side?
5.  What happens if the client sends malformed JSON?
6.  What information should never be returned publicly?
7.  How did you validate user input?
8.  How does your application handle failures?
9.  What would change when a database is introduced?
10. What would you improve before deploying the service?

------------------------------------------------------------------------

## Assessment

| Area                             | Weight   |
|----------------------------------|----------|
| HTTP/client-server understanding | 20%      |
| API/REST reasoning               | 20%      |
| Python implementation            | 15%      |
| Validation/error handling        | 15%      |
| Business logic                   | 15%      |
| Testing/debugging                | 10%      |
| Documentation                    | 5%       |
| **Total**                        | **100%** |

**Progression requirement: 60%**

------------------------------------------------------------------------

# Video Resource Summary

| Section              | Resource                        | Main Competence |
|----------------------|---------------------------------|-----------------|
| Backend Fundamentals | Client–Server Architecture      | Frontend/backend communication |
| HTTP                 | HTTP Crash Course & Exploration | Requests, responses, methods and status codes |
| JSON                 | Corey Schafer — Working with JSON | Serialization and deserialization |
| APIs & REST          | WebConcepts — REST API Concepts | Resources, endpoints and REST reasoning |
| Django Preview       | Python Django Full Course       | Preview Level 2 |
| HTTP Inspection      | Chrome DevTools Network Tab     | Inspect real HTTP communication |
| Logic Labs           | No tutorial                     | Independent architectural reasoning |
| Python APIs          | Corey Schafer — Requests        | Consume APIs using Python |
| Configuration        | Python Dotenv                   | Protect secrets and configure applications |
| Practice Problems    | No tutorial                     | Independent application |
| Level 1 Challenge    | No tutorial                     | Demonstrated competence |
  -----------------------------------------------------------------------

------------------------------------------------------------------------

## Important Learning Rule

> **The closer you get to the competence challenge, the fewer tutorials
> you should need.**

``` text
WATCH
  ↓
READ
  ↓
REPRODUCE
  ↓
MODIFY
  ↓
REASON
  ↓
SOLVE
  ↓
BUILD INDEPENDENTLY
  ↓
DEFEND
```

If you can only build the project while following someone else's
implementation step-by-step, you have completed learning activities but
have **not yet demonstrated Level 1 backend competence**.

------------------------------------------------------------------------

[Continue to Level 2
→](Python-Backend-Level-2-Django-Web-Development.md)
