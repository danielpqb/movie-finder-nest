## How to run

1. Create a root project

```shell
mkdir movie-finder
```

2. Clone this repository

```shell
git clone --recursive https://github.com/danielpqb/ntt
```

4. On the front-end folder (ntt-front), create **.env** based on **.env.example**
5. If you don't have **docker** or **docker-compose**, please make sure you have **both** installed
6. Run docker-compose

```shell
docker-compose up --build
```

7. Access the application through [http://localhost:443](http://localhost:443)
8. And you can also access the api through [http://localhost:4000/api/v1](http://localhost:4000/api/v1/?title=shrek)
9. If you have something running on port 80, please close the process so you can run the application. In case you had, just rerun docker-compose up. A common reason for that port being in use is the apache process on Ubuntu. You can stop it by running:

```shell
sudo /etc/init.d/apache2 stop
```
