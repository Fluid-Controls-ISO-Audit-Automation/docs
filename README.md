# Audit Automating Application 

## Overview
The ISO-AUDIT PROCESS AUTOMATION is an extensive web application engineered to optimize and elevate the audit procedures within organizations. Constructed on the MERN (MongoDB, Express.js, React, Node.js) stack, this system serves as a robust platform empowering administrators to efficiently oversee audits and communicate effectively with team members. The core aim is to deliver a user-friendly interface that streamlines the processes of creating, updating, and deleting audits, while also guaranteeing prompt and automated notifications to the relevant teams. Leveraging MongoDB for data storage, Express.js for server-side development, react for the client-side user interface, and Node.js for backend operations, the application ensures seamless integration and a responsive experience. With a focus on simplicity and effectiveness, this automation solution stands to enhance audit management, fostering a more organized and efficient workflow within organizations.

## Project Objectives and Scope
The Auditing Notification System incorporates a comprehensive set of key features designed to enhance the efficiency and effectiveness of the auditing process:

1. User Authentication and Authorization: Rigorous user authentication and authorization mechanisms are implemented to ensure that only personnel with proper credentials can access and manage audit-related information. This adds a robust layer of security, safeguarding sensitive data from unauthorized access.

2. Audit Management: The system offers a full spectrum of audit management functionalities, allowing administrators to seamlessly create, read, update, and delete audit details. This includes the ability to associate team members with specific audits and manage crucial dates relevant to the auditing process. This comprehensive suite of audit management tools provides administrators with a centralized and versatile platform for overseeing the entire audit lifecycle.

3. Notification Service: A sophisticated background process is in place to automate the timely delivery of notifications. The system proactively sends emails to team members 30, 15, and 1 day before scheduled audit dates. This proactive notification system ensures that all stakeholders are adequately informed and prepared well in advance, contributing to a more organized and collaborative audit preparation process.

4. User-Friendly Interface: The web application boasts an intuitive and user-friendly interface, specifically designed to facilitate seamless interaction for administrators. This ensures that administrators can navigate the system effortlessly, enhancing their overall experience and efficiency in managing audits. The user-friendly design contributes to a more straightforward and accessible auditing workflow.

5. Database Management: MongoDB, a flexible and scalable NoSQL database, is employed for data storage. This choice of database technology allows for adaptability to varying data structures and ensures scalability to accommodate the growing volume of audit-related information over time. 

6. Mail Integration: The system seamlessly integrates with an email service to facilitate reliable notification delivery. This integration ensures that automated emails are sent consistently and that stakeholders receive timely alerts about upcoming audits. The reliability of the mail integration contributes to the overall dependability of the notification system.

## Software Requirements

1.	Backend:
•	Node.js and Express.js: Node.js provides a scalable and non-blocking I/O environment, making it suitable for building backend services. Express.js is a minimalist web framework for Node.js, simplifying the creation of robust APIs.
•	Nodemailer: Nodemailer is chosen for its simplicity and effectiveness in sending notification emails. It supports various transport methods, including SMTP (Simple Mail Transfer Protocol).
•	JWT (JSON Web Token): JWT is employed for secure user authentication and authorization. It allows the backend to generate tokens that contain user information, which can be verified by the frontend.
•	Mongoose ORM: Mongoose simplifies interactions with MongoDB, providing a schema-based solution for data modeling and validation.

2.	Frontend:
•	React.js: React.js is chosen for its component-based architecture, enabling the creation of reusable UI components. Its virtual DOM ensures efficient updates and renders.
•	Tailwind CSS and Material-UI: Tailwind CSS offers a utility-first approach to styling, providing flexibility and ease of customization. Material-UI provides pre-built React components with a consistent design language.
•	Axios: Axios is a promise-based HTTP client for making requests to the backend API. It simplifies the handling of asynchronous operations.

3.	Development Environment:
•	Git: Git is the industry-standard version control system, enabling collaborative development, code tracking, and easy rollbacks.
•	VSCode: Visual Studio Code is a popular code editor known for its lightweight design, extensions, and integrated version control support.
•	NPM (Node Package Manager): NPM is the default package manager for Node.js, facilitating the installation and management of project dependencies.

4.	Testing:
•	Jest and Enzyme: Jest is a JavaScript testing framework, and Enzyme is a testing utility for React. Together, they provide a comprehensive solution for unit testing React components and backend logic.
•	Supertest: Supertest is used for testing HTTP endpoints in the backend, ensuring that APIs respond correctly to different requests.

5. CI/CD:
•	GitHub Actions: Continuous Integration/Continuous Deployment tools automate testing and deployment processes. They help maintain code quality and streamline the release pipeline.

##	Infrastructure Requirements:

1.	Server Infrastructure:
•	Virtual Private Server (VPS) or Cloud-based Infrastructure: VPS or cloud services like AWS or Azure provide the necessary compute resources. These platforms offer scalability and can accommodate the application's varying resource needs.
•	Minimum of 2 CPU Cores and 4GB RAM: These specifications provide a baseline for the server to handle concurrent user requests and data processing efficiently.
•	Solid State Drive (SSD): An SSD is preferred over an HDD for faster I/O operations, contributing to improved application responsiveness.

2.	Load Balancing:
•	Nginx/K8S: Load balancing ensures even distribution of incoming traffic across multiple server instances, enhancing system performance and availability. SSL termination is configured for handling secure connections.
•	Configuration for SSL Termination: SSL termination at the load balancer level simplifies the handling of secure connections, offloading SSL/TLS decryption from backend servers.

3.	Database Server:
•	Dedicated Server or Cluster for MongoDB: MongoDB requires dedicated servers or clusters to handle data storage and retrieval efficiently.
•	Resource Allocation: Resource allocation depends on the expected data volume and workload. Allocating sufficient CPU and RAM resources ensures optimal database performance.

4.	Backup and Recovery:
•	Regular Backups: Regular automated backups are stored in a separate location, minimizing the risk of data loss due to hardware failures or accidental deletions.
•	Automated Backup Schedules: Automated backup schedules ensure consistent data protection without manual intervention.
•	Disaster Recovery Plan: A comprehensive disaster recovery plan outlines procedures to follow in the event of data loss or system failures.

## System Designs and Diagrams

### Data Flow Diagram
![image](https://github.com/Fluid-Controls-ISO-Audit-Automation/docs/assets/86071680/df313815-7686-4176-9ea4-0b5ae15b30d2)
### Entity Relationship Diagram
![image](https://github.com/Fluid-Controls-ISO-Audit-Automation/docs/assets/86071680/2d97a0bf-617e-4499-845f-b86ad18c5bee)
### Use case Diagram
![image](https://github.com/Fluid-Controls-ISO-Audit-Automation/docs/assets/86071680/9101c999-ec17-438c-b70b-047413a1c29a)

## Project Plan and Timeline

![image](https://github.com/Fluid-Controls-ISO-Audit-Automation/docs/assets/86071680/2dc07926-890a-44f2-b7b8-d65989bbac91)
