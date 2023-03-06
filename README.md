# GreatKart - Site to sell courses


Source code can be found on the following link:

https://drive.google.com/drive/folders/1otEVT1DroNKHzVivBL21z78b19TUzZZU?usp=sharing



Some of the base html css are uploaded here




Instructions to run the project


1. Open git bash in the root directory.


2. Run the command "source env/Scripts/activate". 


3. After that run "python manage.py runserver 9000" command.

Once command is executed you should get message displaying text "Watching for file changes with StatReloader".


4. Then open any web browser and type "https://127.0.0.1:9000" in the address bar which will lead to the homepage of the website. 


5. For admin panel "https://127.0.0.1/securelogin" and login id / password can be set from the command prompt by running the command "winpty python manage.py createsuperuser" or "python manage.py createsuperuser".

Already an account is created with following details, one can directly login with this account:

email: xyz@gmail.com
password: xyz



6. Customers can create account by selecting 'Register' button or 'Sign in' if they already have account. After the creation of each account, they have to approved by admin through admin login and going to accounts section and selecting 'Is active' checklist.

Already an account is created with following details, one can directly login with this account:

email: abc@gmail.com
password: abc





Note:

Any changes (addition/removal) of the products (courses), categories, etc. can be done from admin panel.

Customers can only view and order products.
