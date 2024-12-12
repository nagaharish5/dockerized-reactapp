Docker build commands

1)docker build -t react:v1 .

2)docker run -d -p 80:80 react:v1

Creating react app command
1)Node version required 18
2)npx create-react-app react-app

Advantages of nginx
using above command we can create a basic react app ,which can serve itself,
but we are using nginx for deploying the react app  beacuse of static file optimization,caching,scalability

