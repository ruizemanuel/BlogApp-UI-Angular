# Angular Blog Project

This project is a blog developed with Angular, utilizing various libraries and tools to provide an advanced blogging experience. Below, you'll find the main features of the project, the tools used, and how to run it.

## Test the App

Test the app on the live demo: [blogapp-emanuelruiz.netlify.app](https://blogapp-emanuelruiz.netlify.app/)

Credentials:
User: admin@blogapp.com
Password: Admin@123

## Key Features

**User Management:** Implements JWT Token to handle user authentication, enabling secure access to the blog's functionalities.

**Session Cookies:** Uses Cookie Service to efficiently and securely manage user sessions.

**Markdown Rendering:** Utilizes ngx-markdown to render content in Markdown format, allowing users to publish content with rich formatting.

**Reactive Programming:** Makes extensive use of RxJS for handling events and asynchronous communication, enhancing efficiency and reactivity.

**HTTP Interceptors:** Integrates HTTP_INTERCEPTORS to intercept and modify HTTP requests globally, providing features such as authentication tokens.

## Installation

When you clone this repository, make sure to run the following commands to install the necessary dependencies:
`npm install`

## Backend Configuration

The application, by default, is configured to connect to a backend developed in .NET, deployed on Azure. However, you have the option to download and run the backend locally.
To run the backend locally, download it from [Github](https://github.com/ruizemanuel/BlogApp-API-.NET) and follow the instructions in the backend's README.

## Running the Application

To start the Angular application, use the following command:
`ng serve`

The application will be available at http://localhost:4200/ by default.

## Libraries Used

**JWT Decode:** jwt-decode - For decoding and managing JWT tokens used in authentication.

**Cookie Service:** ngx-cookie-service - For effective management of session cookies.

**Ngx Markdown:** ngx-markdown - For rendering content in Markdown format.

**RxJS:** rxjs - For reactive programming and efficient event handling.

## Autor

👤 **Ruiz, Jose Emanuel**

* GitHub: [ruizemanuel](https://github.com/ruizemanuel)