1. build:
docker build -t kinuniversal .
2. run
docker run -p 8082:80 --name kin kinuniversal
3. test:
http://localhost:8082/.well-known/apple-app-site-association