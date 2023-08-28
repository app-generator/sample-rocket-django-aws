# Django Starter

**Django** starter built with [Rocket Generator](https://app-generator.dev/). Actively supported by [AppSeed](https://appseed.us/) via `Email` and `Discord`.

> Support this service via a [sponsorship](https://appseed.gumroad.com/l/rocket-sponsorship) (managed by GUMROAD) - **ONLY $9**

<br />

## Features: 

- `Up-to-date Dependencies`
- Modern UI 
- CI/CD flow via Render
- API Generator (optional)

<br />

## Start with `Docker`

> In case the starter was built with Docker support, here is the start up CMD:

```bash
$ docker-compose up --build
```

Once the above command is finished, the new app is started on `http://localhost:5085`

<br />

## Manual Build 

> Download/Clone the sources  

```bash
$ git clone https://github.com/<THIS_REPO>.git
$ cd <LOCAL_Directory>
```

<br />

> Install modules via `VENV`  

```bash
$ virtualenv env
$ source env/bin/activate
$ pip install -r requirements.txt
```

<br />

> `Set Up Database`

```bash
$ python manage.py makemigrations
$ python manage.py migrate
```

<br />

> `Generate your API` (optional) 

```bash
$ python manage.py generate-api -f
```

<br />

> `Start the App`

```bash
$ python manage.py runserver
```

At this point, the app runs at `http://127.0.0.1:8000/`. 

<br />

---
**Django** starter built with [Rocket Generator](https://app-generator.dev/)
