# jenkins-docker
Alpine + Jenkins Latest + MVN 3.5.0
Docker Hub URL: https://hub.docker.com/r/matheusbona/jenkinsmvn/

Faça o clone do projeto:
git clone https://github.com/matheusbona/jenkins-docker.git
cd jenkins-docker

Para buildar:
docker build -f Dockerfile .

Para executar:

Crie um diretório:
mkdir meujenkins

Play na bagaça:
docker run -d -p 8080:8080 -p 50000:50000 --name meujenkins --restart=unless-stopped -v $(pwd)/meujenkins:/var/jenkins_home matheusbona/jenkinsmvn

Enjoy :)

Linkedin: https://www.linkedin.com/in/matheusbona/
E-mail: mateus.bona@gmail.com
