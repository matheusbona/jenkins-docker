# jenkins-docker
Alpine + Jenkins Latest + MVN 3.5.0

Para executar:

Crie um diretório:
mkdir meujenkins

Play na bagaça:
docker run -d -p 8080:8080 -p 50000:50000 --name meujenkins --restart=unless-stopped -v $(pwd)/meujenkins:/var/jenkins_home matheusbona/jenkinsmvn

Enjoy :)

Linkedin: https://www.linkedin.com/in/matheusbona/
E-mail: mateus.bona@gmail.com
