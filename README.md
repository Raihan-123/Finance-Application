# 👋Introduction
- Welcome to our Finance Application's README!

Our Finance Application is a reliable and efficient web-based budgeting tool designed to help users manage their finances effectively. With this application, users can effortlessly add, categorize, and track their expenses

## Key Features
- Expense Management: Easily add and track your expenses.
- Category Customization: Create custom categories tailored to your needs.
- Default Categories: Utilize built-in categories for convenient expense organization.
- Budget Calculation: Stay on top of your budget by tracking expenses across different categories.

## 🏃‍♂️Installation
1. Clone the repository

``` bash
git clone https://github.com/Raihan-123/Finance-Application.git
```
2. Change the working directory
```bash
cd finance-application
```
3. Install dependencies
```bash
pip install -r requirements.txt
```
or
```bash
python -m pip insatll -r requirements.txt 
```
4. Then run the `python manage.py migrate` to make create tables in the database
```bash
python manage.py migrate
```
5. Then run the `python manage.py collectstatic` command
```bash
python manage.py collectstatic
```
6. Start the development server
```bash
python manage.py runserver
```
>Note: Do not use the this server for production

7. Open your web browser and navigate to http://127.0.0.1:8000 to use the application.

8. Thats all your good to go. Enjoy the app 💖!!

> Change the .env file according to your needs.


## Usage
### Adding a new category
#### To add a new category, follow these steps:

1. Log in to your account.
2. Click on the user profile dropdown menu in the navigation menu.
3. Click on the "Add Category" button.
4. Enter the name and budget of the new category.
5. Click on the "Confirm" button.

### Editing a category
#### To edit a category, follow these steps:

1. Log in to your account.
2. Click on the "Analytics" link in the navigation menu.
3. Click on "Update" button besides the cateogory you want to edit.
4. Update the name and budget of the category.
5. Click on the "Confirm" button.

### Adding an expense
#### To add an expense, follow these steps

1. Log in to your account.
2. Click on "+ Add Expense" box in the body (if no expense is added)  
3. Click on "+ Add Expense" button (if atleast one expense is added)
4. Enter the Cateogry and the expense value.
5. Click on the "Confirm" button.



## Contributing
Contributions to the Django Finance App are welcome! Please submit a pull request with any changes or improvements you would like to make.
