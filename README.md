mvn clean package docker:build -DpushImage

docker run -p 9001:9001 -v /Users/baochunyu/Downloads/logs:/data/logs -t baochunyu1987/ms-docker 

mvn clean package docker:build -DpushImage -Dproject.tag=