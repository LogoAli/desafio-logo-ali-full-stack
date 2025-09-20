# 🚀 Desafio Estagiário - Fullstack  

Bem-vindo ao desafio para a vaga de **estagiário em desenvolvimento**! 🎯  
O objetivo é avaliar seus conhecimentos práticos em **desenvolvimento backend e frontend**, organização de código, boas práticas e criatividade na solução.  

---

## 📌 Descrição do Desafio  

Você deverá desenvolver um **sistema fullstack** composto por um **backend (API REST)** e um **frontend (aplicação web)**.  

A ideia é validar:  
- Seu domínio em **HTML, CSS e JavaScript**.  
- Suas noções de **backend (API, rotas, regras de negócio)**.  
- Sua capacidade de criar interfaces **usáveis e responsivas**.  
- Seu entendimento de **persistência de dados** (mesmo que em memória).  

O projeto não precisa ser perfeito — queremos avaliar sua evolução, organização e como você resolve problemas.  

---

## 🔧 Requisitos Backend (API REST)  

Você pode usar **qualquer linguagem/framework** de sua preferência (Node.js, Go, Java, Python, etc).  

A API deverá conter os seguintes endpoints:  

1. **Login**  
   - Endpoint para autenticação de usuário.  
   - Deve aceitar apenas:  
     - Email: `admin@email.com`  
     - Senha: `Admin@123`  
   - Caso email/senha sejam inválidos, retornar mensagem de erro.  
   - **Bônus**: Implementar geração de token **JWT**.  

2. **Criação de Usuário Administrador**  
   - Deve receber:  
     - Nome  
     - Email  
     - Senha  
     - CPF  
   - Validar se os campos obrigatórios foram preenchidos.  

3. **Criação de Estabelecimento**  
   - Deve receber:  
     - Nome (até 50 caracteres)  
     - Descrição (até 300 caracteres)  
     - Documento (até 14 caracteres)  
   - Validar os limites de caracteres.  

4. **Listagem de Estabelecimentos**  
   - Retornar todos os estabelecimentos cadastrados.  

5. **Edição de Estabelecimento**  
   - Permitir atualizar os dados de um estabelecimento.  

6. **Desativação de Estabelecimento**  
   - O estabelecimento não deve ser excluído, apenas **desativado logicamente** (ex: `ativo = false`).  

👉 Os dados podem ser armazenados **em memória** (listas/arrays).  
👉 **Bônus**: 
   - Utilizar banco de dados (SQLite, PostgreSQL, MongoDB, etc).
   - Autenticação dos endpoints via token **JWT**.  

---

## 🎨 Requisitos Frontend (Aplicação Web)  

Você pode utilizar **HTML, CSS e JavaScript** ou frameworks modernos (React, Vue.js, Angular, etc).  

O frontend deverá:  
- Implementar as telas conforme o **protótipo no Figma** (link será fornecido).  
- Consumir os endpoints do backend.  
- Seguir boas práticas de responsividade.  

👉 **Bônus**:  
- Utilização de frameworks modernos (React, Vue, Angular).  
- Estilização com TailwindCSS, SCSS ou outra ferramenta.  
- Uso de componentes reutilizáveis.  

---

## ✅ O que será avaliado  

- Clareza e organização do código.  
- Estrutura do projeto (separação de responsabilidades).  
- Validações no backend.  
- Fidelidade ao protótipo do frontend.  
- Criatividade e soluções extras.  
- Documentação (como rodar o projeto).  

---

## 📦 Entrega  

1. Crie um repositório **público no GitHub** com o código do desafio.  
2. No `README.md` do seu projeto, explique:  
   - Como rodar o backend.  
   - Como rodar o frontend.  
   - Tecnologias utilizadas.  
   - Quais bônus foram implementados.  
3. Inclua o link do protótipo do Figma utilizado no frontend.  

---

## 🎁 Diferenciais  

- JWT para autenticação.  
- Uso de banco de dados.  
- Testes automatizados (unitários ou de integração).  
- Deploy do projeto (backend e/ou frontend).  

---

## 🚀 Boa sorte!  

Esse desafio é uma oportunidade para você mostrar **suas habilidades técnicas e criativas**.  
Não precisa ser perfeito — queremos entender como você pensa e resolve problemas.  
