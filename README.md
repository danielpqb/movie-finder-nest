## How to run

1. Create a root project

```shell
mkdir movie-finder
```

2. Clone this repository

```shell
git clone --recursive https://github.com/danielpqb/ntt
```

4. Create .env based on .env.example on the front-end folder (change [http://localhost:4000](http://localhost:4000/) to [http://localhost:80/api](http://localhost/api))
5. If you don't have docker and/or docker compose, please make sure you have both installed
6. Run docker compose

```shell
docker-compose up --build
```

7. After that, you can access the application through [http://localhost:80](http://localhost/)
8. And you can also access the api through [http://localhost:80/api/v1](http://localhost/api/v1)
9. If you have something running on port 80, please close the process so you can run the application. In case you had, just rerun docker compose up. A common reason for that port being in use is the apache process on Ubuntu. You can stop it by running:

```shell
sudo /etc/init.d/apache2 stop
```
