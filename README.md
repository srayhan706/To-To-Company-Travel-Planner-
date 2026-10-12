# ToToCompany — Travel & Flight Booking Platform

ToToCompany is a full-stack travel web application developed using **Next.js, Spring Boot, and MySQL**. It allows users to explore landmarks, browse flight information, manage profiles, and authenticate securely.

## Features
- Responsive home, about, services, and profile pages.
- Landmark exploration with search and filtering by country and type.
- Flight search interface with departure, destination, and travel date selection.
- User registration and login.
- Google OAuth 2.0 authentication.
- Email OTP verification and password recovery.
- Profile management.

## Technology Stack
- **Frontend:** Next.js, React.js, HTML, CSS, JavaScript
- **Backend:** Java, Spring Boot, REST APIs
- **Database:** MySQL
- **Authentication:** Spring Security, JWT, Google OAuth 2.0
- **Tools:** Git, GitHub, Docker

## Design Patterns
- **Singleton:** Spring-managed security and configuration beans.
- **Factory:** Spring `@Bean` factory methods.
- **MVC:** Separation of controllers, business logic, models, and views.
- **Builder:** Builder-style construction of DTOs and authentication objects, where implemented.

## Installation

**1. Clone the repository**
```bash
git clone <YOUR_REPOSITORY_URL>
cd ToToCompany
```

**2. Configure MySQL**

Create the `totocompany` database and configure the database credentials in the Spring Boot application.

**3. Run the backend**
```bash
cd backend
./mvnw spring-boot:run
```

**4. Run the frontend**
```bash
cd frontend
npm install
```

Create `.env.local`:
```env
NEXT_PUBLIC_API_URL=http://localhost:8080
```

Start the frontend:
```bash
npm run dev
```

Frontend: `http://localhost:3000`

Backend: `http://localhost:8080`

## Contributors

- Tahshina Islam Munni — Roll 26
- S. M. Imran Rahman — Roll 40
- Shariful Islam Rayhan — Roll 41
- Nirjhar Singha — Roll 46

## Academic Information

**Course:** CSE-3216 — Software Design Pattern Lab

**Department:** Computer Science & Engineering, University of Dhaka

**Project:** ToToCompany
