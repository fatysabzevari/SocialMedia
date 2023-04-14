# SocialMedia

## note:

------------




**note you must have : pip , virtualenv installed in your system**

```bash
git clone https://github.com/fatysabzevari/SocialMedia
cd SocialMedia
virtualenv env 
. env/bin/active 
pip install -r requirments.txt
python manage.py migrate
python manage.py collectstatic 
python manage runserver
```

## what the user Can Do after Sign in  : 
- Post in his Profile page
- Replay on users Posts
- simple like system can user like any posts
- Follow other users to see their posts in his home page
- Search for users
- See Follow  Suggestion in the bottom of his home page
- full control on his information , edit data and his image.

>  Note : I'm just python developer not desinger or front end  so my website design is Bad, I tried to do my best But I was Sure that  will be Ugly, any way** the project is all about Backend not Front  :+1:  .**

- all the Django code by me excep the login,Register function from try-django4 open source project
- all the style by except comment Box from [comment box](https://bootsnipp.com/ "comment box") and simple  one JQuery function for Replay button


