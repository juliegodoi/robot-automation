# 🤖 Robot Automation

Projeto desenvolvido como parte do curso **Robot Framework: automatizando testes no padrão BDD** da [Alura](https://www.alura.com.br), dentro da formação de **QA**.

Este projeto utiliza o **Robot Framework** para automatizar testes funcionais no sistema **Organo**, uma aplicação para organização de equipes de trabalho.


## ⚙️ Requisitos

Antes de rodar o projeto, certifique-se de ter os seguintes softwares instalados:

- [Node.js](https://nodejs.org/)
- [Python](https://www.python.org/)
- [Robot Framework](https://robotframework.org/)
- [SeleniumLibrary](https://robotframework.org/SeleniumLibrary/)
- WebDriver compatível com o navegador (ex.: Edge, Chrome, Firefox)


## 📦 Instalação do Organo

1. Baixe o repositório do Organo:

   [Download direto do ZIP](https://github.com/alura-cursos/robot-framework-organo/archive/refs/heads/main.zip)

2. Extraia o conteúdo e acesse a pasta pelo terminal. Exemplo:

   ```bash
   cd C:\Users\seu-usuario\Desktop\organo
   npm install
   npm start
   ```


## 🧪 Configurações Adicionais

#### WebDriver

Certifique-se de que o WebDriver do navegador escolhido esteja instalado e acessível via terminal.  
O caminho do executável deve estar configurado na variável de ambiente `PATH`.

> ✅ Neste projeto foi utilizado o **Microsoft Edge**.


#### FakerLibrary

Para gerar dados fictícios nos testes, é necessário instalar e configurar a biblioteca `FakerLibrary`.

Instale com o seguinte comando:

```bash
pip install robotframework-faker
```
Caso enfrente erros, consulte este tópico de ajuda da Alura:  
👉 [https://cursos.alura.com.br/forum/topico-problemas-com-fakerlibrary-no-robot-448428](https://cursos.alura.com.br/forum/topico-problemas-com-fakerlibrary-no-robot-448428)


## 🚀 Executando os Testes

Os arquivos de teste estão localizados na pasta `testes/`:

- `preenchimento_correto.robot`
- `preenchimento_incorreto.robot`

Para executar cada teste, utilize os comandos abaixo no terminal (estando na raiz do projeto):

```bash
robot testes/preenchimento_correto.robot
robot testes/preenchimento_incorreto.robot
```
