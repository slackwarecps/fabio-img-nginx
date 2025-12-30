# Fabio Image Nginx

Este repositório hospeda um site estático simples, projetado para servir como base em **estudos e Provas de Conceito (PoCs)** envolvendo **Docker** e **Kubernetes**.

O projeto utiliza o servidor web Nginx para exibir uma página HTML que apresenta, como destaque principal, uma **pomba engraçada** (Pru! Pru!).

## Objetivos

- Fornecer uma imagem leve e funcional para testes de orquestração de containers.
- Servir de laboratório para deploys em Docker e Kubernetes.
- Disseminar a cultura do "Pru!".

## Uso via Docker Hub

A imagem deste projeto está disponível no Docker Hub e pode ser utilizada diretamente:

[https://hub.docker.com/repository/docker/fabioalvaro/fabio-img-nginx/general](https://hub.docker.com/repository/docker/fabioalvaro/fabio-img-nginx/general)

Exemplo de comando para rodar:
```bash
docker run -d -p 8080:80 fabioalvaro/fabio-img-nginx
```

## Estrutura do Projeto

- `Dockerfile`: Configuração da imagem baseada no Nginx.
- `public/`: Contém o código HTML e as imagens (incluindo o GIF da pomba).
- `sobe.sh`: Script auxiliar (verifique o conteúdo para detalhes de execução).