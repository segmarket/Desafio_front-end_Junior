# 📝 Desafio Front-End Júnior

Bem-vindo(a) ao nosso desafio para desenvolvedores front-end iniciantes e estagiários!  
Sua missão será criar uma aplicação web para gerenciar uma **To-Do List de Eventos**, com uma interface bonita, recursos úteis e interação com uma API. 💪

---

## 🚀 O Desafio

Você deve desenvolver uma aplicação web com as seguintes funcionalidades:

- 🔐 **Login do usuário**
- 📅 **Importar eventos por intervalo de datas** após o login
- 👀 **Marcar eventos como vistos ou não vistos**
- 📊 **Gerar um relatório com os eventos vistos**, acessível em uma página separada
- 🎯 **Aplicar filtros no relatório**
- 📱 **Interface 100% responsiva**, adaptada para qualquer dispositivo

Tecnologias permitidas:

- **HTML**
- **CSS**
- **JavaScript**
- **localStorage**

---

## 🔐 Autenticação

Antes de importar os eventos, o usuário deve realizar login utilizando o seguinte endpoint:
method: POST, URL: https://segmarket-dash-sandbox-api.azuremicroservices.io/auth/login
JSON: 
{
    login: 'SEU_LOGIN',
    password: 'SUA_SENHA'
  }

📅 Consulta de Eventos
Com o token em mãos, use o endpoint abaixo para consultar os eventos de um intervalo de datas:
method: GET, URL: https://segmarket-dash-sandbox-api.azuremicroservices.io/public/events/getEvents
Params: startDate (Datetime no formato ISO); endDate (Datetime no formato ISO)


### Responsividade
- Layout adaptável para **desktop** e **mobile**  

## 📦 Entregáveis

- 🔗 Repositório com **todo o código-fonte**
- 📄 Um arquivo `PULL_REQUEST.md` explicando suas decisões, processo e pontos importantes
- ⚙️ Instruções de como rodar o projeto localmente

---

## 🧐 Avaliação

Seu projeto será avaliado com base em:

- ✨ Qualidade e organização do código  
- 🧠 Clareza e legibilidade  
- 💻 Interface amigável
- 📱 Responsividade (mobile-first conta pontos!)  
- 📚 Boas práticas e documentação  
- ✅ Funcionalidades completas

---

## 💡 Quer ganhar pontos extras?

Aqui vão alguns bônus que podem te destacar:

- CI/CD com GitHub Actions  
- Paginação, ordenação e filtros dinâmicos  
- Código limpo, modularizado e com separação de responsabilidades

---

##🤝 Enviando sua solução
Crie um arquivo PULL_REQUEST.md com suas explicações e decisões técnicas

Faça um Pull Request com o mesmo nome de branch para os repositórios backend/frontend (ou tudo em um único repo, se for o caso)

Pronto! 🚀

Boa sorte e divirta-se com o código! 😄
Seja criativo(a) e mostre do que você é capaz!
