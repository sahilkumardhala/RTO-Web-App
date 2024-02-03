![web](https://github.com/sahilkumardhala/RTO-Web-App/blob/main/prototype%20Image/Register%20page.jpg)

RTO Web App
Welcome to the RTO Web App repository! This web application is built using HTML, CSS, JavaScript, Django, and SQLite3. Here, you'll find information about the project, its structure, and how to set it up.

Overview
The RTO Web App is designed to streamline processes related to Regional Transport Offices (RTO). It provides a user-friendly interface for various tasks related to vehicle registration, license renewal, and other RTO-related services.

Technologies Used
- HTML: Used for structuring the web pages.
- CSS: Responsible for styling and layout.
- JavaScript: Enhances the interactivity and functionality of the web pages.
- Django: A high-level Python web framework used for backend development.
- SQLite3: The lightweight and easy-to-use database management system.

![database](https://github.com/sahilkumardhala/RTO-Web-App/blob/main/prototype%20Image/Login%20page.jpg)

![database](https://github.com/sahilkumardhala/RTO-Web-App/blob/main/prototype%20Image/DATABASE.jpg)

Installation
Follow these steps to set up the RTO Web App locally:

Clone the repository:

Navigate to the project directory:
```bash
git clone https://github.com/sahilkumardhala/RTO-Web-App.git
```
```bash
cd RTO-Web-App
```
Install dependencies:
```bash
pip install -r requirements.txt
```
Apply migrations:
```bash
python manage.py migrate
```
Run the development server:
```bash
python manage.py runserver
```
Open your web browser and go to http://localhost:8000/ to access the RTO Web App.

Corrently, admin account with the username "`sahil`" and password "`1234`".

If want ,then you can follow these steps:

1. Open the terminal and navigate to the project directory.

2. Run the following command to create a superuser:
   ```bash
   python manage.py createsuperuser
   ```

3. You will be prompted to enter a username, email address, and password. Enter the following details:
   - Username: sahil
   - Email address: (you can leave this blank)
   - Password: 1234

   Press Enter to complete the process.

4. After creating the superuser, you can now use these credentials to log in to the Django admin panel when the application is running.

5. Start the development server if it's not already running:
   ```bash
   python manage.py runserver
   ```

6. Open your web browser and go to [http://localhost:8000/admin/](http://localhost:8000/admin/).

7. Log in using the `username "sahil" and password "1234."`

Now, you should have access to the Django admin panel with the specified admin credentials.
Contribution
If you'd like to contribute to the project, please follow these guidelines:

Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and commit them.
Push the changes to your fork.
Submit a pull request.
Contact
For any inquiries or issues, feel free to contact me:

Email: `sahildhala123@gmail.com`

Twitter: `sahilkumardhal1`

LinkedIn: `Sahil Kumar Dhala`

Thank you for your interest in the RTO Web App!