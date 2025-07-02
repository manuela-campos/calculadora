# Projeto de Versionamento com Git e GitHub

Este repositório foi criado como parte de uma atividade prática para aplicar conhecimentos em controle de versionamento com **Git** e **GitHub**, além de desenvolver uma funcionalidade simples em **JavaScript** utilizando a classe `Math`.

---

## ✅ Objetivos da Atividade

- Criar um repositório local utilizando Git.
- Criar um repositório remoto no GitHub.
- Conectar o repositório local ao repositório remoto.
- Adicionar colaborador (colega de sala) ao repositório remoto.
- Criar uma nova funcionalidade utilizando a classe `Math` do JavaScript.
- Utilizar comandos Git como `branch`, `push`, `pull` e `merge`.
- Sincronizar as alterações locais com o repositório remoto após contribuição externa (professor).

---

## 🛠️ Ferramentas Utilizadas

- **Git** – Controle de versão
- **GitHub** – Hospedagem de código
- **Visual Studio Code** – Ambiente de desenvolvimento
- **JavaScript (Node.js)** – Lógica da aplicação

---

## 🚧 Etapas Realizadas

1. **Criação do Projeto**
   - Criei o projeto no Visual Studio Code
   - Inicializei o Git com `git init`
   - Criei o arquivo `index.js`

2. **Repositório Remoto**
   - Criei um repositório no GitHub
   - Conectei ao repositório local com:
     ```bash
     git remote add origin <URL>
     git add .
     git commit -m "Início do projeto"
     git push -u origin main
     ```

3. **Nova Funcionalidade**
   - Criei uma nova branch: `git checkout -b math-feature`
   - Fiz os seguintes commits durante o desenvolvimento:

     - **Criando variáveis**
       ```javascript
       let num1;
       let num2;
       ```

     - **Inserindo a multiplicação**
       ```javascript
       console.log(`Multiplicação: ${num1} * ${num2} = ${num1 * num2}`);
       ```

     - **Inserindo a divisão**
       ```javascript
       console.log(`Divisão: ${num1} / ${num2} = ${num1 / num2}`);
       ```

     - **Atualizando a quebra de linha com soma**
       ```javascript
       console.log(`Soma: ${num1} + ${num2} = ${num1 + num2}`);
       ```

     - **Inserindo a subtração**
       ```javascript
       console.log(`Subtração: ${num1} - ${num2} = ${num1 - num2}`);
       ```

     - **Incluindo nova frase à conta com exponenciação**
       ```javascript
       console.log(`A Exponenciação dos números ${num1} ** ${num2} = ${num1 ** num2}`);
       ```

   - Após finalizar a funcionalidade, fiz o merge com a branch principal:
     ```bash
     git checkout main
     git merge math-feature
     git push origin main
     ```

4. **Colaboração**
   - Adicionei um colega como colaborador no GitHub
   - Enviei o link do repositório no Classroom
   - O professor foi adicionado como colaborador e fez uma alteração no projeto

5. **Atualização**
   - Atualizei meu repositório local com:
     ```bash
     git pull origin main
     ```

---

## Ferramentas Utilizadas

- Git
- GitHub
- Visual Studio Code
- JavaScript (Node.js)

---

## Link do Repositório

[🔗 Clique aqui para acessar o repositório](https://github.com/manuela-campos/calculadora.git)

---

## Colaboradores

- Aluno responsável: [@manuela-campos](https://github.com/manuela-campos)
- Colega de sala:
  - [@HelenCrystina](https://github.com/HelenCrystina)
  - [Matheus Faria](https://github.com/Math3Faria)
  - [@Isabella Souza](https://github.com/isasmj)
  -[@Gabriele Furlan Cavalcanti](https://github.com/gabrieleCavalcanti)
- Professor: colaborador convidado
