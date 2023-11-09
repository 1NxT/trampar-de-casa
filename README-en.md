# Trampar de Casa 💻🏠

![GitHub last commit (branch)](https://img.shields.io/github/last-commit/ocodista/trampar-de-casa/main)
![GitHub contributors](https://img.shields.io/github/contributors/ocodista/trampar-de-casa)
![Website](https://img.shields.io/website?up_message=online&up_color=green&down_message=offline&down_color=red&url=https%3A%2F%2Fwww.trampardecasa.com.br%2F)
![GitHub license](https://img.shields.io/github/license/ocodista/trampar-de-casa)

![Static Badge](https://img.shields.io/badge/nextjs-white?style=for-the-badge&logo=nextdotjs&logoColor=white&labelColor=black&color=white)
![Static Badge](https://img.shields.io/badge/typescript-%2306B6D4?style=for-the-badge&logo=typescript&labelColor=white&color=%233178C6)
![Static Badge](https://img.shields.io/badge/vite-%23646CFF?style=for-the-badge&logo=vite&labelColor=black)
![Static Badge](https://img.shields.io/badge/tailwindcss-%2306B6D4?style=for-the-badge&logo=tailwindcss&labelColor=black&color=%2306B6D4)

## About the project 🎯

The Trampar de Casa is an open-source
an initiative dedicated to connecting Brazilian developers to remote work opportunities, encouraging inclusion, diversity, and through geographical boundaries.

Weekly, we send one email with job opportunities and 100% remotes matching our subscribers' profiles.

## [Manifesto sobre o Trabalho Remoto](./manifesto.md)

## Roadmap of the project 🚧

- [ ] **Preference Registration**: Define the preference of work of our users.
- [ ] **Select and send personalized job opportunities**: Send selected job opportunities with the user's preferences.
- [ ] **Automatic send job opportunity**: Send job opportunities regularly with no actively searching.
- [ ] **A page for partner companies**: Show more info about partner companies.

---

## How to Contribute 🚀

1. **Fork** of the repository.
2. **Clone** of the repository in your local development environment.
3. **Create** a new branch to your new function or correction.
4. **Implement** your changes and add unit tests, if applicable.
5. **Push** to your branch in your fork.
6. Send a **Pull Request** to the main repository.

---

## Como executar a aplicação localmente

1. Após clonar o repositório localmente, a partir do seu fork, entre na pasta criada.
2. Execute o comando `yarn`.
3. Se você não tiver o yarn instalado, execute `npm install --global yarn`.
4. Para executar a aplicação no ambiente de desenvolvimento, execute o comando `turbo dev`.
5. Se você não tiver o turbo instalado, execute `npm install --global turbo`.
6. A aplicação estará disponível em http://localhost:3000.

## Como subir o banco de dados localmente

1. Certifique-se de ter o [docker](https://www.docker.com/) instalado na sua máquina.
2. Navegue até a pasta `apps/web`.
3. Execute o comando `npm install` para instalar as dependências do projeto.
4. Na pasta packages/db (`cd packages/db`), execute o comando `npm run db-start` para gerar a pasta `prisma/client` e subir uma instância local do Supabase.
5. Você verá informações no terminal sobre as credenciais da sua instância local do Supabase.
6. Na pasta apps/web (`cd apps/web`), crie um arquivo `.env`.
7. Copie o conteúdo do `.env.example` para o `.env`, e preencha `SUPABASE_URL` e `SUPABASE_SERVICE_ROLE` com as credencias do passo 5.
8. Execute o comando `npm run db-seed` caso queira popular sua base de dados.
9. Caso tenha alguma dúvida consulta a [documentação oficial do supabase](https://supabase.com/docs/guides/getting-started/local-development) e a [documentação oficial do prisma](https://www.prisma.io/docs/guides/migrate/seed-database).

## Contribuidores ✨

<a href="https://github.com/ocodista/trampar-de-casa/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ocodista/trampar-de-casa&anon=0&columns=20&max=100" />
</a>

Toda e qualquer contribuição é muito bem-vinda!