#1 docker build -t namehere .
#2 docker run --rm -it --name web -p 3000:80 react-docker:1.0.0-dev
(local:publish <- port >)
(--rm means once app is closed then let it remove container too.)
(-it means interact terminal)
(-p means publish)

Reference.
#1 생활코딩
#2 Docker official channel https://youtu.be/8VHheCkw-7k