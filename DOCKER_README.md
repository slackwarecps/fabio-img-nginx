# Fabio Image Nginx (Docker Image)

Esta é a imagem oficial do projeto **Fabio Image Nginx**.

## Sobre este Projeto

Esta imagem contém um site estático simples servido via Nginx, projetado para servir como base em **estudos e Provas de Conceito (PoCs)** envolvendo **Docker** e **Kubernetes**.

A aplicação exibe uma página HTML que apresenta, como destaque principal, uma **pomba engraçada** (Pru! Pru!).

## 🔗 Código Fonte no GitHub

O código fonte, Dockerfile e instruções detalhadas de desenvolvimento estão hospedados no GitHub:

👉 **[https://github.com/slackwarecps/fabio-img-nginx](https://github.com/slackwarecps/fabio-img-nginx)**

## 🚀 Como Usar

Para iniciar um container rapidamente:

```bash
docker run -d -p 8080:80 fabioalvaro/fabio-img-nginx:latest
```

Acesse em seu navegador: `http://localhost:8080`

## Tags Disponíveis

- `latest`: Versão mais recente estável.
- `2.0`: Versão com layout centralizado e fundo cinza.
- `1.0`: Versão inicial (se disponível).

## Contribuição

Sinta-se à vontade para abrir issues ou pull requests no repositório do GitHub.
