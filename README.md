# Grid Ops Manager

## Overview
Grid Ops Manager is a robust grid outage ticket system designed to help utilities manage and track active and archived outages efficiently. This application allows users to monitor outages, affected sites, and site deratings, facilitating clean and easy bookkeeping.

![Main Page](https://github.com/shahzada-shah/gridopsmanager/blob/main/assets/loginauth.png)

## Tech Stack
- **Frontend**: ReactJS
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL (RDS)
- **Hosting:** AWS (S3, RDS, Elastic Beanstalk)
- **State Management:** React Context API
- **Routing:** React Router with Protected Routes
- **Styling:** Styled Components
- **API Calls:** Axios to interact with custom Backend API

![Main Page](https://github.com/shahzada-shah/gridopsmanager/blob/main/assets/outagefetch.png)
![Main Page](https://github.com/shahzada-shah/gridopsmanager/blob/main/assets/outagearchive.png)

## Functionalities
1. **Active Outage Tracking:** Keep track of ongoing outages with real-time data updates.
2. **Archived Outages:** Easily access and review completed outages for historical data and analysis.
3. **Site Management:** View details about affected sites and their current operational capacity.
4. **User Authentication:** Secure login system to ensure data integrity and security.

![Main Page](https://github.com/shahzada-shah/gridopsmanager/blob/main/assets/createcrud.png)
![Main Page](https://github.com/shahzada-shah/gridopsmanager/blob/main/assets/updatecrud.png)

## Live Demo on AWS
The application is deployed on AWS, leveraging Elastic Beanstalk for easy management and scaling. 

URL: [Grid Ops Manager Live Demo](http://outagesystem.s3-website-us-east-1.amazonaws.com)

Test Credentials: <br/>
Username: sshah <br/>
Password: sshah1997s@@

Note: These credentials will give you access to the system where you can view, manage, and archive outage data.
