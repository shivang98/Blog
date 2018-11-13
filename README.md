# Blog
A company blog clone developed using Python and Django
Only superuser can create and edit blog posts.
Anybody can comment on the blog but superuser have to approve the comment.

![alt text](https://raw.githubusercontent.com/shivang98/Blog/master/mysite/blog/static/images/img.png)

## How to run
Please install Python 3.6 and Django 2.1 before running the app
1. Clone the repositorie using git clone https://github.com/shivang98/Blog
2. cd into mysite folder
3. python manage.py makemigrations
4. python manage.py migrate
5. python manage.py runserver
6. Go to the shown ip address

*Note-* If you want to add posts you have to create a super user using following command in mysite directory

python manage.py createsuperuser
