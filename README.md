API que faz predições para cartas Gods Unchained
================================================

## Execução DOCKER (Dockerfile instala todas as dependências):
### Construção da imagem Docker:
docker build -f Dockerfile -t predcards .

### Rodar a aplicação, liberando o prompt:
docker run -itd -p 5017:5017 predcards

## URL:
http://localhost:5017/api/
