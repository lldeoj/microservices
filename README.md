# microservices
microsoft course about microservices


Front-end 
http://localhost:5902/

Back-end
http://localhost:5000/pizzainfo


To run
> into folder backend 
> docker build -t pizzabackend .
> docker run -it --rm -p 5200:80 --name pizzabackendcontainer pizzabackend

> into root folder
> docker-compose build
> docker-compose up

