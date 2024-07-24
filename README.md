# django-react

## Links
- https://www.photondesigner.com/articles/use-react?ref=yt
- https://github.com/tomdekan/use-react
- https://www.youtube.com/watch?v=Az1BosALarw&t=2s
- http://localhost:5173/ - connect here
- http://localhost:8000/

## Commands
- node -v
- npm -v
- npm create vite@latest
- cd react+django
- npm install
- npm run dev
- pip install --upgrade django django-cors-headers python_dotenv
- django-admin startproject core .
- python manage.py startapp apples
- python manage.py makemigrations
- python manage.py migrate
- python manage.py shell
- python manage.py createsuperuser

## Data import
- python manage.py shell
```
from apples.models import Apple

Apple.objects.create(name='Bramley', color='red and green', photo_url='https://upload.wikimedia.org/wikipedia/commons/thumb/5/52/Bramley%27s_Seedling_Apples.jpg/320px-Bramley%27s_Seedling_Apples.jpg')
Apple.objects.create(name='Cox Orange Renette', color='yellow', photo_url='https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Cox_orange_renette2.JPG/320px-Cox_orange_renette2.JPG')
Apple.objects.create(name='Granny Smith', color='green', photo_url='https://upload.wikimedia.org/wikipedia/commons/thumb/b/bf/Granny_smith_closeup.jpg/320px-Granny_smith_closeup.jpg')
Apple.objects.create(name='SugarBee', color='red and yellow', photo_url='https://upload.wikimedia.org/wikipedia/commons/thumb/5/5b/The_SugarBee_Apple_now_grown_in_Washington_State.jpg/320px-The_SugarBee_Apple_now_grown_in_Washington_State.jpg')

```

## Connect 
- http://localhost:5173/
- http://127.0.0.1:8000/apples/
