# Notes - Nexvent

- References - You need to add references to use that code in your project
- API - To Receive HTTP Request and return HTTPS Responses
- `[controller]` in Route replaces the controller we are targeting

- Main method - It is not directly visible in Program.cs but it is there running in background
- Two Sections in `Program.cs` 
  1. Services - Any class or service that provide something, and to use in API Controller you would use DI.
  2. HTTP Request Pipeline 

- Our request or HTTP request as it comes into our API it goes through a pipeline, then it gets executed by API endpoint and back to client
