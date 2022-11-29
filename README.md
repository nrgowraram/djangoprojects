# djangoprojects 

I created a new folder for Django project which is "djangoprojects"
Then I installed virtual environment using 
"pip install virtualenv" in the cmd.
I named it as "venv" 
I used the terminal from the pycharm
I activated the virtual environment using the command "venv\scriots\activate"
Then I installed Django using "pip install django" 
I checked the Django version using "django-admin version"
Then I created the Django project using command "django-admin startproject hello_world"
And then Icreated the app using " django-adminstartapp HelloWorld" 
In settings.py file I added my app name in the installed apps 
then I opened the views.py file and added the following code 
from django.shortcuts import render
from django.http import HttpResponse
def sayHello(request):
    return HttpResponse('<h1 style="color:black">{"Message":"Hello World!"}</h1>')
Modified the urls.py file and then copied the urls.py file and pasted in the HelloWorld app 
and made some changes in the include line and then run the server using "pythom manage.py runserver" 
Then i got a url link http://127.0.0.1:8000/ 
which shows the output which is attached in the assignment. 
