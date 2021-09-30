# Django-School

This app is meant to be used by school manager to manage their school records:
student data
staff
results and
finances.

It currently doesn't allow students/staff to login.
Solely, it's expected to be used on a single machine or online for managers only.

## Demo
```bash
username: admin
password: admin123
```

## Usage
It's best to install Python projects in a Virtual Environment. Once you have set up a VE, clone this project

```bash
git clone  https://github.com/stephane-evrard/django_school.git
```
Then

```bash
cd Django-School
```
Run

```python
pip install -r requirements.txt #install required packages
python manage.py migrate # run first migration
python manage.py runserver # run the server
```
Then locate http://127.0.0.1:8000

## Admin Login
When you run migrate, a superuser is created.
```bash
username: admin
password: admin123
```

## Live link on heroku
    https://infinite-lowlands-81162.herokuapp.com/

## License
[MIT](https://choosealicense.com/licenses/mit/)


