Certifique-se de estar no diretório que contém os arquivos `Dockerfile` e `index.html` no terminal.
Execute o comando "docker build -t httpd-lab:1.0".
Você pode conferir a imagem que acabou de criar com o comando docker images.
Após criar a imagem, execute o comando "docker run -d -p 8080:80 httpd-apache:latest".
O serviço web estará disponivel no endereço localhost:8080.
