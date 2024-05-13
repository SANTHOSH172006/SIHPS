# Smart India Hackathon Workshop
# Date: 10-05-2024
## Register Number: 212223220099
## Name: SANTHOSH D
## Problem Title
E-Waste Facility Locator
## Problem Description
Website that tells you the location of the nearest e-waste collection and recycling facility. Offers educational pop-ups on the harmful components of your e-waste and their effects on the environment and human health if not disposed correctly. There could be an option to input the model of your old device and earn credit points relative to the amount of precious metals recovered from the device if disposed correctly.
## Problem Creater's Organization
Ministry of Environment

## Idea
The E-Waste Facility Locator is a digital platform designed to help individuals and organizations easily locate nearby facilities for the proper disposal and recycling of electronic waste (e-waste). This initiative aims to promote environmental sustainability by facilitating the responsible disposal of electronic devices, preventing them from ending up in landfills where they can harm the environment.

## Proposed Solution / Architecture Diagram
1.User Interface (UI): Frontend application accessible via web browsers and mobile devices. Provides the user interface for searching e-waste facilities, educational pop-ups, user account management, and rewards tracking.

2.Application Server: Backend server responsible for handling user requests, processing data, and communicating with other components. Implements the business logic of the application, including search functionality, rewards calculation, and user authentication.

3.Database: Stores user data, e-waste facility information, device models, rewards points, and other relevant data. Can be a relational database management system (RDBMS) or a NoSQL database depending on scalability and data structure requirements.

4.Geolocation Service: Utilizes geolocation APIs to determine the user's location when they allow access or manually input it. Provides location data to the application server for finding nearby e-waste facilities.

5.Educational Content Repository: Repository for storing educational content related to e-waste recycling. Contains information, images, videos, and interactive elements for displaying educational pop-ups and tooltips on the UI.

6.External APIs: Integrates with external APIs for mapping and geolocation services to fetch and display e-waste facility locations on the map. May also integrate with electronics manufacturers' APIs for retrieving device model information and calculating rewards points.

7.Partnership Integration: Integrates with partner systems, such as electronics manufacturers or retailers, to provide exclusive incentives and rewards for users. Communicates with partner APIs to validate rewards and incentives earned by users.

![image](https://github.com/SANTHOSH172006/SIHPS/assets/144979212/1b58f2a0-8d90-4f42-97f8-3f49f813f712)


## Use Cases
Finding Nearest E-Waste Facility: User launches the application and allows access to their location. The system identifies the user's location and displays nearby e-waste recycling facilities on the map. User selects a facility for more information or navigation directions.

Contributing New Facility Information: User registers or logs into the application. User submits information about a new e-waste recycling facility, including its location, contact details, and accepted materials. Submitted information undergoes verification before being added to the database.

Feedback and Ratings: User selects a facility from the search results. User provides feedback on their experience with the facility, such as cleanliness, staff friendliness, and overall satisfaction. User ratings and comments are displayed to other users to help them make informed decisions.

Promotion and Awareness: The application sends push notifications or emails to users about e-waste recycling events, campaigns, or special initiatives. Users can share information about the application and specific facilities on social media platforms to raise awareness among their peers.

Educational Resources: The application provides educational resources and tips on reducing e-waste, proper disposal methods, and the environmental impact of electronic devices. Users can access articles, videos, and infographics to learn more about e-waste management best practices.

## Technology Stack
1.Frontend:React.js with Bootstrap for responsive UI.

2.Backend: Node.js with Express.js, MongoDB for data storage.

3.Authentication: JWT for user authentication.

4.Map Integration: Google Maps API.

5.Cloud Services: AWS for hosting, S3 for storage.

6.DevOps: CI/CD with GitHub Actions, monitoring with AWS CloudWatch.

7.Security: SSL/TLS encryption, OWASP Top 10 compliance.

## Dependencies
1.Frontend: React.js, React Router, Axios, Bootstrap or Material-UI

2.Backend: Node.js with Express.js, Mongoose, Passport.js, jsonwebtoken, Dotenv

3.Database: MongoDB

4.Geolocation Services: Google Maps API or Mapbox API

5.Cloud Services: AWS SDK, AWS S3 SDK

6.Development and Deployment: GitHub Actions or CircleCI, AWS CloudWatch

7.Security: Helmet, bcrypt.js
