# NoteHub
## Task:
A notes/image sharing platform (partially similar to Instagram) where you let users create/read/update/delete their notes, photos, etc. Users could comment on the images and notes.

Sub-application 1: the front-end and back-end should use the Model-View-Controller framework of ASP.NET 8.0
Sub-application 2: the backend should be .NET 8.0 (can reuse that from Sub-application 1), and the front-end should use a front-end framework with AJAX call (e.g., React).
A short documentation of 2000-5000 words (in English) must be written, which should include some diagrams for the software architecture and database

## What we learned:
- Introduction to .NET Core
- Model-View-Controller
- Entity Framework (Database CRUD, Asynchronous)
- Data Access Layer (DAL)
- Logging and Error Handling
- Forms and Input validation
- Security: Authentication and Authorisation
- Unit Testing
- Single Page Applications (React)


## Versions of Node.js, ASP.NET, React that are used:
- Node.js: v22.11.0
- ASP.NET: .NET 8.0
- React: 18.3.1

## Running the project
Sub application-1 can be run using these commands after opening the project:
- Open new terminal
- Cd WebMVC
- Dotnet ef database update
- Dotnet run
- Open browser
- http://localhost:5000

Sub application-2 can be run using these commands after opening the project: 
- ### Backend:
- Open new terminal
- cd api
- Dotnet ef database update
- dotnet run
- ### Frontend:
- Open new terminal
- cd reactapp
- Npm install
- npm start
