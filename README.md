# Projeto DevOps - Pipeline CI/CD em Nuvem

Projeto prático para a disciplina de Cloud Computing e DevOps. O objetivo é demonstrar um fluxo completo de CI/CD, desde a criação da aplicação até o deploy automatizado.

## Arquitetura e Ferramentas
* **Aplicação:** Site estático em HTML servido via Nginx.
* **Containerização:** Docker e Docker Compose (arquivo `docker-compose.yml` configurado).
* **CI (Integração Contínua):** GitHub Actions automatizando o teste de build do contêiner a cada *push*.
* **CD e Nuvem (Deploy):** Render (PaaS), realizando a entrega contínua com HTTPS configurado automaticamente.

## Como executar o projeto localmente
1. Clone este repositório.
2. Na raiz do projeto, execute o comando: `docker-compose up --build`
3. Acesse `http://localhost` no seu navegador.
