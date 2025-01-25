# MadoffAirlines

## API Documentation
To access the API documentation go to [api/docs](./api/docs)

## Overall Description
Madoff Airlines is an online ticketing platform designed to simplify and streamline the process of searching, booking, and managing flight tickets. The platform offers a seamless flight booking experience with a user-friendly interface, real-time flight data integration, and robust security features. It supports user registration, flight searches, ticket bookings, and secure payment processing, while also integrating with third-party services through APIs.

## Key Features
1) Intuitive and Clean UI: Easy-to-navigate interface for a smooth user experience.

2) User Registration and Login: Secure account creation and authentication.

3) Flight Search and Filtering: Advanced search options with real-time flight data.

4) Booking Management: Manage bookings, select seats, and add baggage preferences.

5)  Secure Payment Processing: Safe and reliable payment integration (future release).

6)  Thorough Security Features: Protects user data with encryption and secure APIs.


## Requirements: 

1) Node.js ^22.9.0 -Runtime environment
2) pnpm - package manager
3) PostgreSQL - Database
4) npm - Node package manager
5) Docker - Containerization



## How to setup everything and run it locally

1. Clone the git repository.
    ```shell
    git clone https://git.liacs.nl/s3856348/madoffairlines.git
    && cd ./madoffairlines
    ```
2. Navigate to the API Folder:
    ```shell
    cd ./api
    ```

On the API folder, go the README file there and continue with the instructions there. Once done, the other instructions are on the ~/web directory README file. 

Here is an overview:

1) Setup postgresql server
2) Setup the API
3) Setup the front-end
> The guide on how to setup steps 1-2 can be found in the api directory. The instructions are there in the README.md.

> The guide on how to setup 3 can be found in the web directory. The instructions are there in the README.md.


## Technologies Used:

Frontend: Next.js, Tailwind CSS, Framer Motion, Radix UI, Lucide React.

Backend: Node.js, Express.js, Prisma (ORM).

Database: PostgreSQL.

APIs: Amadeus API (for real-time flight data).

Testing: Jest, React Testing Library.

Version Control: Git








