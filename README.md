# Laundry Automation System

## Installation
To set up the Laundry Automation System, follow these steps:

1. **Install XAMPP:** Download and install XAMPP, which includes Apache, MySQL, and PHP. You can download it from [here](https://www.apachefriends.org/index.html).

2. **Start Apache and MySQL:** Start the Apache and MySQL services from the XAMPP control panel.

3. **Database Setup:**
   - Open your web browser and go to `http://localhost/phpmyadmin`.
   - Log in using the default username `root` and leave the password field blank.
   - Click on the "SQL" tab and run the SQL file provided in the repository to create the necessary database tables.

4. **Code Configuration:**
   - Clone the repository to your local machine.
   - Navigate to the directory where the project is cloned.
   - Open the `config.php` file and update the following:
     - `$serverName`: Set the server name to `localhost` or the appropriate server name if different.
     - `$userName`: Set the username for the MySQL database.
     - `$password`: Set the password for the MySQL database.
     - `$dbName`: Set the name of the database created in step 3.

5. **Access the Application:** Open your web browser and navigate to the directory where the project is cloned. You can access the application by typing `http://localhost/<project_folder_name>` in the address bar.

This setup will allow you to run the Laundry Automation System on your local machine for testing and development purposes.

## Team Members
- **Navaneeth Krishna**
- **BJ Gridhar**
- **Rajveer Singh Khanduja**

## Introduction
Waiting for washed laundry and searching among numerous bags is a common issue faced by college students residing in dormitories. Laundry facilities in college dormitories often serve a large population of students, leading to congestion, long wait times, and difficulties in locating one's clean laundry among the multitude of bags. This results in frustration, inconvenience, and wasted time for students who rely on these facilities to manage their laundry needs.

## Problem Statement
The laundry automation system aims to address the following challenges:
- Congestion and long wait times in laundry facilities.
- Difficulty in locating clean laundry among numerous bags.
- Manual tracking methods leading to errors and inefficiencies.

## Solution
The solution is a web application with QR code scanning to automate laundry processes and provide real-time updates. It aims to streamline operations, reduce wait times, and improve user experience in places like dormitories or apartment complexes.

## Workflow
### Admin Login:
1. **QR Code Pickup:** Admins use QR codes to efficiently pick up bags, ensuring accuracy and speed in the process.
2. **Update and Notify:** After washing, admins rescan QR codes to update backend data and trigger email notifications, keeping users informed.
### Student Login:
1. **Check Status:** Students log in to view their bag's status, including washing status and rack number.
2. **Real-time Updates:** The portal provides instant updates, ensuring students are informed throughout the laundry process.

## Key Features
1. **Login Authentication:** Admins and students can access the system via secure login credentials, ensuring data privacy and security.
2. **QR Code Scanner:** The admin panel facilitates efficient bag pickup and drop-off processes with a QR code scanner. Admins can quickly update the status of laundry bags by scanning QR codes.
3. **Backend Data Management:** Real-time data management ensures accuracy and transparency in laundry operations. The admin panel updates the backend database with relevant information such as laundry status and user details.
4. **Email Notifications:** Integrated email notification functionality sends automated updates to users regarding their laundry status. Admins can configure email templates and trigger notifications for events such as laundry completion or pickup.
5. **Laundry Status Tracking:** The student portal provides a comprehensive view of each student's laundry status. Students can monitor the progress of their laundry, including whether it has been washed and its current rack number.
6. **Real-time Updates:** Users receive real-time updates on their laundry status, ensuring they are informed at every stage of the process.

## Benefits
- **Efficient Tracking:** By automating the laundry process, manual tracking tasks are eliminated, saving time and reducing the likelihood of errors.
- **Reduced Waiting Time:** Real-time updates provide visibility into the status of laundry bags, reducing the need for students to wait in line or search for their laundry.
- **Transparency and Convenience:** Real-time updates offer transparency and convenience, allowing students to plan their pickup accordingly and avoid unnecessary delays.

## Pain Points of Students
1. **Waiting Time:** Long wait times in laundry rooms can disrupt students' schedules and lead to frustration.
2. **Uncertainty:** Without real-time updates, students may feel uncertain about the status of their laundry, leading to anxiety and inconvenience.
3. **Manual Tracking:** Manual tracking methods are prone to errors and inefficiencies, causing delays and confusion for students.
