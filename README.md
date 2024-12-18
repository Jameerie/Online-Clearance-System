# Online Clearance System

This project is an *Online Student Clearance System* that allows administrators to manage student records and clearance processes, while students can view and pay outstanding fees, track their payment history, and update their profiles.

---

## Features

### Admin Panel
- *Login and Logout*
- *User Management* (Add/Delete Users)
- *Register New Student*
- *List All Students*
- *Manage Student Clearance*
- *Add Fee*
- *View Payment History*
- *Change Password*

### Student-Side
- *Login and Logout*
- *Dashboard Page*
- *Pay Outstanding Fee*
- *View Payment History*
- *Update Photo*
- *Change Password*
- *Print Clearance Letter*
- *Print Receipt*

---

## Requirements

To run this project locally:

1. *Local Web Server*  
   Install [XAMPP](https://www.apachefriends.org) or any other PHP-compatible web server.

2. *Source Code*  
   - Clone the repository from GitHub.

---

## Installation/Setup Instructions

### Step 1: Clone the Repository
Clone the project to your local machine using Git:

bash
git clone https://github.com/jameerie/online-clearance-system.git

Step 2: Start the Web Server

	•	Open XAMPP Control Panel and start Apache and MySQL services.

Step 3: Move the Source Code

	•	If not already in htdocs, move the cloned repository to:

C:\xampp\htdocs\online-clearance-system

Step 4: Database Configuration

	1.	Open your browser and go to PHPMyAdmin:

http://localhost/phpmyadmin


	2.	Create a new database named:

student_clearance


	3.	Import the provided SQL file located in the db folder:
	•	File Name: student_clearance.sql

Step 5: Access the System

Open your browser and run the system:
	•	Student Side:

http://localhost/online-clearance-system/


	•	Admin Panel:

http://localhost/online-clearance-system/Admin

Admin Login Credentials

	•	Username: admin1
	•	Password: password1
     Register a student in the Add Student page of the admin panel, a password will be automatically generated, the login details will be viewable in the records page and can be used to login on the
	 student page, use that to login to the student's pages and do your thing.


# GitHub Repository

How to Contribute

	1.	Fork the repository.
	2.	Create a new branch:

git checkout -b feature/your-feature-name

	3.	Make your changes and commit:

git commit -m "Add your message here"

	4.	Push to your branch:

git push origin feature/your-feature-name

	5.	Open a Pull Request on GitHub.

Cloning for Local Development

To clone and test this system locally:

git clone https://github.com/jameerie/online-clearance-system.git

# Troubleshooting

	1.	Apache/MySQL Won’t Start:
	•	Ensure no other processes (like Skype) are using ports 80 or 3306.
	•	Update XAMPP port configurations if necessary.
	2.	Database Import Issues:
	•	Ensure the database name is exactly student_clearance.
	•	Use PHPMyAdmin’s “Import” feature and select student_clearance.sql.
	3.	Access Issues:
	•	Verify the project folder is inside the htdocs directory.
	•	Confirm Apache and MySQL services are running.

# License

This project is licensed under the MIT License. See the LICENSE file for details.

# Author

Developed by Alameen Onafeko. For contributions, suggestions, or issues, feel free to open a GitHub issue or submit a pull request.

---