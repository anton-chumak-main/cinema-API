# cinema-API
Api service for cinema management written on DRF

# Installation

Python3 must be already installed

```shell
git clone https://github.com/anton-chumak-main/cinema-API.git
cd cinema_service
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
Create .env file and populate it with necessary env variables which are listed in .env.sample
And then run following commands:
docker compose duild
docker compose up
```

## Getting access
* get access token via /api/user/token/
  * set email and password for django user according to your .env file
  * install extension ModHeader for your browser 
  and paste the access token there like this: Bearer < your access token >
  

## Feature
* JWT authenticated
* Powerful admin panel for advanced managing /admin/
* Documentation is located at /api/doc/swagger/
OR api/doc/redoc/
* Managing order and tickets
* Creating movie with genres, actors
* Adding movie session
* Filtering movie and movie sessions
