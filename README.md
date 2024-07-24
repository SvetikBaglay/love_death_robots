docker build -t love-death ./ 
docker run -it -v "$(pwd):/app" -p 4200:4200 love-death:latest bash 
ng serve --host 0.0.0.0
