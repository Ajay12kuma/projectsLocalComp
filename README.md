The first project, "PdfGenerator," is a Spring MVC-based web application that generates PDF documents using the open-source library OpenPDF. The application exposes an API that accepts requests with data to be included in the PDF, and returns a PDF document as the response.

The process begins with a client sending a request to the API with the required data. The API then generates a PDF document using OpenPDF, populating it with the provided data. The generated PDF document is then returned as the response to the client.

The second project, "SpringAuth," is a Spring MVC-based web application that handles user authorization and authentication . The application exposes an API that allows clients to authenticate and authorize users.

The application stores user data in a MySQL database using JPA (Java Persistence API). JPA provides a set of APIs for persisting Java objects to a relational database. It simplifies database access and reduces the amount of boilerplate code required for data persistence.

When a client requests access to a protected resource, the application verifies the user's credentials and checks if the user is authorized to access the resource. If the user is authorized, the application returns the requested resource. If the user is not authorized, the application returns an error message.

The frontend of the application is implemented using Angular 12.Angular provides a set of APIs for building components, services, and modules.

