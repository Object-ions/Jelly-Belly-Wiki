# Jelly Belly Wiki Project

### By Moses Atia Poston

## Table of Contents

1. [Project Description](#project-description)
2. [Project Overview](#project-overview)
3. [Important Note for Running the Application](#important-note-for-running-the-application)
4. [Technologies Used](#technologies-used)
5. [Explore the Project](#explore-the-project)
6. [License](#license)
7. [Contact](#contact)

## [Project Description](#project-description)

The Jelly Belly Wiki Project is an integrated solution comprising a data collection subsystem, a backend API, and a frontend client. This project showcases a comprehensive approach to full-stack web development, with a focus on the Jelly Belly candy brand. The data collection subsystem employs Python scripts for web scraping, the backend API is developed with C# .NET EF Core and MySQL, and the frontend client is built using React.

## [Project Overview](#project-overview)

This project is structured into three main components, each residing in its own submodule within this repository:

1. **Jelly Belly Wiki API Data Collection**: [Repository](https://github.com/Object-ions/Jelly-Belly-Wiki-API-Data-Collection): this repository dedicated to scripts and supporting files for data collection, primarily using Python for web scraping from the official Jelly Belly website.

2. **Jelly-Belly-Wiki-API**: [Repository](https://github.com/Object-ions/Jelly-Belly-Wiki-API): This repository contains the API implementation and the seeded data from the scraping process. The API is built using C# and EF Core .Net with MySql migrations.

3. **Jelly-Belly-Wiki-Client**: [Repository](https://github.com/Object-ions/Jelly_Belly_Wiki_Client): The client-side component focusing on user interface and interaction. It includes all frontend development, offering a visually appealing and demonstrates the API's application and functional user experience.

**Note**
Each submodule is equipped with its own README file, containing detailed instructions, documentation, and specific notes relevant to that part of the project.

## [Important Note for Running the Application](#important-note-for-running-the-application)

In order to fully experience the Jelly Belly Wiki application, it is essential to follow these steps:

1. **API and Database Setup**:

   - First, download and install the API from the `/API` submodule. This step is crucial as the API serves as the backend for the application and interacts with the database.
   - Ensure that the database is properly set up and connected as per the instructions in the API repository.

2. **Client UI Installation**:

   - After setting up the API and database, proceed to download and install the client UI from the `/Client` submodule. The client UI is the frontend of the application and requires the API to be operational for the full functionality.

3. **Data Collection Scripts**:
   - The data collection scripts located in the `/Data-collection` submodule have already been executed to scrape and seed the data into the API's database. Therefore, it is not necessary to run these scripts for the application to work.
   - These scripts are included in the repository to provide insight into the data collection and preparation process, which is a fundamental aspect of this project.

By following these instructions, you can ensure a smooth setup and enjoy the complete functionality of the Jelly Belly Wiki application.

## [Technologies Used](#technologies-used)

**Programming Languages and Frameworks:**

- **C#**: Primary programming language for backend development.
- **ASP.NET Core**: Framework for building high-performance web applications.
- **Entity Framework Core**: ORM framework for data access in .NET applications.
- **Python**: Used for web scraping and data processing.

**Web Technologies:**

- **HTML**: Standard markup language for creating web pages.
- **CSS**: Style sheet language used for describing the presentation of a web page.
- **JavaScript**: Programming language for creating interactive web pages.
- **React**: JavaScript library for building user interfaces.
- **Webpack**: A module bundler for JavaScript applications.

**Database Technologies:**

- **MySQL**: Database management system used for storing and retrieving data.
- **LINQ (Language-Integrated Query)**: A .NET component that adds native data querying capabilities to .NET languages.

**API Development and Testing:**

- **Postman**: Collaboration platform for API development and testing.
- **Swagger**: Tool for documenting APIs.
- **Fetch API**: A browser API for making asynchronous HTTP requests in JavaScript.
- **Jelly Belly Wiki API**: Custom API developed for this project.

**Web Scraping and Data Processing:**

- **Selenium WebDriver**: Tool for automating web browser interactions.
- **BeautifulSoup**: Library for pulling data out of HTML and XML files.

**Data Format:**

- **JSON (JavaScript Object Notation)**: Data format used for storing and transporting data.

**Testing:**

- **TDD (Test-Driven Development) with Jest**: JavaScript testing framework used following the TDD methodology.

**Artificial Intelligence:**

- **Artificial Intelligence (AI - ChatGPT 4)**: Used for retrieving 'facts' and formatting the output.

## [Explore the Project](#explore-the-project)

I encourage exploring each submodule for a deeper understanding of the individual components and their roles within the project. The submodules are structured to provide a clear and efficient overview of the project's multiple facets, from data collection to user interaction.

Please refer to the README files in each submodule for detailed directions, instructions, and additional notes pertinent to each specific segment of the project.

## [License](#license)

[MIT](https://choosealicense.com/licenses/mit/)

Copyright (c) 2023 Moshe Atia Poston.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

### [contact](#contact)

If you detect any bug in the program, please reach out to me at [moshikoatia@gmail.com](mailto:moshikoatia@gmail.com).
