# This project is no longer maintained since some dependent websites are closed.

# safe-hotel

## Prerequisite
```
npm >= 8.1.2
python >= 3.6
```

## First Time Running
```
pip install -r requirements.txt
npm install # optional
```

## Run the Project
```
python main.py
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

## Framework
```
/src: this folder stores data and frontend codes;
    /src/assets: static data;
    /src/components: frontend Vue components, may be involved in multiple use cases;
    /src/data: volatile data;
    /src/network: define the rules communicating frontend and backend;
    /src/router: define the url of each page;
    /src/view: main web pages (use cases) in the project;
/server: this folder stores backend codes;
    /server/flask_app.py: flask app, implementing the "filter" use case functional requirements;
    /server/update_hotel.py: periodically fetch hotel data to /src/data;
    /server/update_map.py: periodically fetch covid data to /src/data;
    /server/utils.py: general variables and functions to be used.
```
