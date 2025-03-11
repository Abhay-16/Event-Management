# Event Management System

## Overview
The **Event Management System** is a dynamic web-based application that enables users to book, manage, and inquire about events. It provides an intuitive interface for clients, admins, and users to interact with various functionalities, including event booking, customer inquiries, and reviews.

## Folder Structure
```
Event
│── build/classes
│── controller
│   ├── AddToCart.class
│   ├── DeleteEnq.class
│   ├── DeleteUser.class
│   ├── Flow.class
│── model
│   ├── Dproduct.class
│   ├── EnqList.class
│   ├── Enquiry.class
│   ├── Events.class
│   ├── Ratings.class
│   ├── User.class
│   ├── customer.class
│── src/main/java
│   ├── controller
│   │   ├── AddToCart.java
│   │   ├── DeleteEnq.java
│   │   ├── DeleteUser.java
│   │   ├── Flow.java
│   ├── model
│   │   ├── Dproduct.java
│   │   ├── EnqList.java
│   │   ├── Enquiry.java
│   │   ├── Events.java
│   │   ├── Ratings.java
│   │   ├── User.java
│   │   ├── customer.java
│── webapp
│   ├── META-INF
│   ├── WEB-INF
│   │   ├── lib
│   │   │   ├── mysql-connector-j-8.0.33.jar
│   │   │   ├── servlet-api.jar
│   │   ├── web.xml
│   ├── ViewClients.jsp
│   ├── about.jsp
│   ├── adHeader.jsp
│   ├── adHome.jsp
│   ├── addDelEvent.jsp
│   ├── addEventHeader.jsp
│   ├── bookedEvents.jsp
│   ├── contact.jsp
│   ├── contact1.jsp
│   ├── corporate.jpeg
│   ├── enquiryList.jsp
│   ├── eventBooking.jsp
│   ├── eventCategories.jsp
│   ├── eventStatus.jsp
│   ├── events.jsp
│   ├── example.JPG
│   ├── footer.jsp
│   ├── forgotPassword.jsp
│   ├── gallery.jsp
│   ├── header.jsp
│   ├── index.jsp
│   ├── login.jsp
│   ├── loginHeader.jsp
│   ├── map.jsp
│   ├── pdf.jsp
│   ├── review.css
│   ├── review.jsp
│   ├── service.jsp
│   ├── style.css
│   ├── viewEvents.jsp
│   ├── viewReview.jsp
```

## Features
- **User Authentication:** Login and registration system.
- **Event Booking:** Users can browse and book events.
- **Admin Management:** Admins can add/delete events and manage user inquiries.
- **Enquiry System:** Customers can inquire about events.
- **Feedback & Reviews:** Users can review and rate events.
- **Dynamic Pages:** Built with JSP, Servlets, and MySQL database.

## Installation & Setup
### Prerequisites:
- Java Development Kit (JDK 8 or later)
- Apache Tomcat (Recommended 9.x)
- MySQL Database
- MySQL Connector for Java

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/event-management.git
   ```
2. Import the project into Eclipse/IntelliJ.
3. Configure MySQL database:
   - Create a database named `event_db`.
   - Import the SQL script for tables.
4. Update `web.xml` and database connection settings in Java files.
5. Deploy on Apache Tomcat and start the server.
6. Access the system via `http://localhost:8080/Event/index.jsp`.

## Technologies Used
- **Frontend:** JSP, HTML, CSS
- **Backend:** Java, Servlets, JSP
- **Database:** MySQL
- **Server:** Apache Tomcat

## Contributors
- ABHAY ITAGI - Developer & Maintainer



