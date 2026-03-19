# 🐳 Dockerfiles e Compose

<div align="center">
  <img src="https://media.giphy.com/media/xT9IgzoKnwFNmISR8I/giphy.gif" width="150" alt="Matrix Tech GIF">
  <br>
  <strong>Ambientes, personalizações e contêineres Docker mantidos pelo Prof. Ed</strong>
</div>

<div align="center">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/Docker_Compose-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker Compose">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
  <img src="https://img.shields.io/badge/Shell_Script-121011?style=for-the-badge&logo=gnu-bash&logoColor=white" alt="Shell Script">
</div>

---

## 🌟 Sobre o Repositório

Este repositório atua como o centralizador oficial das configurações e orquestrações de contêineres do **Prof. Ed**. Aqui você encontrará **Dockerfiles** variados e arquivos **`docker-compose.yml`** prontos para instanciar serviços e ecossistemas interconectados com apenas uma linha de comando.

A infraestrutura contida aqui foi desenhada para criar laboratórios virtuais isolados, consistentes, seguros e ágeis, eliminando o clássico problema do *"na minha máquina funciona"*.

### 📦 O que você vai encontrar aqui:

- 🛠️ **Dockerfiles customizados:** Receitas de imagens baseadas em Linux com ferramentas úteis pré-instaladas.
- 🐙 **Docker Compose:** Orquestração multi-container (ex: servidores Web atrelados a banco de dados com volumes persistentes).
- ⚙️ **Scripts e Utilidades:** Arquivos `.sh` agregados para buildar, rodar ou destruir os ambientes de forma automatizada.

---

## 🚀 Como Utilizar

Certifique-se de que você possui o **Docker** e o **Docker Compose** instalados e rodando corretamente na sua máquina.

### Passos básicos:

**1. Clone o repositório:**
```bash
git clone https://github.com/ed1rac/Dockerfiles-e-Compose.git
```

**2. Acesse a pasta do serviço/laboratório que deseja rodar:**
```bash
cd Dockerfiles-e-Compose/<pasta-desejada>
```

**3. Inicie o ecossistema com o Compose:**
Para rodar os serviços em segundo plano (background), utilize a flag `-d`:
```bash
docker-compose up -d
```

**4. Derrubando os contêineres:**
Após concluir o laboratório ou trabalho, desligue todos os contêineres de forma limpa:
```bash
docker-compose down
```
> *Se quiser apagar também os volumes de dados persistentes gerados por aquela sessão, você pode usar `docker-compose down -v`.*

---

## 👨‍💻 Autor

👋 Feito por **Prof. Ed (Edkallenn Lima)**
- ⭐️ Conheça meus outros projetos acadêmicos: [edkallenn.github.io](https://edkallenn.github.io/)
- 🌐 Redes Sociais: [LinkedIn](https://www.linkedin.com/in/edkallenn/) | [GitHub](https://github.com/ed1rac)
