# Hahn Application Project

Fullstack application Project (Hahn Software) for creating and handling applicants.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. The project uses an ASP.NET Core 5.0 Web-Host and Class Libraries with Logic and Data in the Backend and a Frontend UI created in Aurelia.
The data is saved in a persistent database in MS Azure.

### Prerequisites

What things you need to install the software and how to install them

- VS 2019
- Node.js
- dotnet

### Installing

Download the project files from https://github.com/LuHa612/hahn-software.git and execute

- dotnet restore
- npm install

to install the missing nugets and node_modules.

## Deployment

Find the publish folder with a self-contained version of the whole project in the root directory. Execute the .exe in the publish folder for a ready-to go built version of the project.

## Executing

To execute the project, either use the beforementioned .exe in the publish folder or open the solution in VS2019 and start debugging with the self-contained (Hahn.Application. ...) option chosen (not IIS). The UI is accesible at http://localhost:5000. The API description is available at http://localhost:5000/swagger. As the data is persitent and the list of Applicants cannot contain duplicate IDs, the "Try it out" option of swagger might return an error if an Applicant with that example ID (10) has already been created. The application will return the next available ID though.

## Built With

* [VS 2019](https://visualstudio.microsoft.com/vs/) - Backend IDE
* [Aurelia](https://aurelia.io/) - Frontend Tool
* [Azure](https://azure.microsoft.com/en-us/features/azure-portal/) - Cloud Database

## Authors

* **Lukas Hans** - *Initial work* - [LuHa612](https://github.com/LuHa612)

## License

This project is licensed under the MIT License - only for test purpose!
