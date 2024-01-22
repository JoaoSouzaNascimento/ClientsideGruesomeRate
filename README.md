  *Comandos via terminal:*

    *Criar imagem*
      docker build -t meu_app .

    *Criar Conteiner*
      docker run --name django_app -p 8000:8000 meu_app
