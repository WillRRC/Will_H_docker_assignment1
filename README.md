To run the app run these commands in order 


docker build -t willhartfielsreactapp:1.0.2 .
docker tag willhartfielsreactapp:1.0.2 whartfielrrc/willhartfielsreactapp:1.0.2
docker push whartfielrrc/willhartfielsreactapp:1.0.2

docker run -p 7775:3000  whartfielrrc/my-react-app:1.0.2

this will run it at port 7775 local host
