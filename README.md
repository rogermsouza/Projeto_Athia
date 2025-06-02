# Projeto Athia

Este projeto foi desenvolvido em PHP utilizando o padrão MVC (Model-View-Controller), o que facilita no desenvolvimento e suporte, com banco de dados MySQL e executado em ambiente local com Apache (via XAMPP).

> 💡 **MVC (Model-View-Controller)** é um padrão de arquitetura de software que organiza uma aplicação em três componentes principais: **Modelo**, **Visão** e **Controlador**. Essa separação facilita a manutenção, escalabilidade e desenvolvimento de aplicações, especialmente em projetos web.

## 📁 Estrutura do Projeto

- **config/**: Arquivos de configuração do sistema e conexão com o banco de dados.
- **controllers/**: Controladores responsáveis pela lógica de cada funcionalidade.
- **models/**: Modelos que lidam com a comunicação com o banco de dados.
- **views/**: Telas exibidas ao usuário.
- **public/**: Arquivos públicos como CSS, imagens e componentes reutilizáveis.
- **index.php**: Roteador principal que define o controller e ação com base na URL.

## 🗃️ Banco de Dados

- O banco de dados utilizado é chamado **`athia`**.
- A estrutura e dados iniciais estão no arquivo `athia.sql` localizado em:
  

- Você pode importá-lo via phpMyAdmin ou outro cliente MySQL.

## 🧩 Tecnologias Utilizadas

- PHP com padrão MVC
- MySQL
- HTML / CSS
- Apache (via XAMPP)

## 🚀 Como executar o projeto

Você pode **baixar manualmente** ou **clonar este repositório** localmente.

### 📥 Baixando manualmente:

1. Clique no botão verde `Code` e selecione **Download ZIP**.
2. Extraia o conteúdo do `.zip` para a pasta `htdocs` do seu XAMPP.
3. Inicie o Apache e o MySQL pelo painel do XAMPP.
4. No **phpMyAdmin**, crie o banco `athia` e importe o arquivo:
config/Banco_de_Dados-sql/athia.sql

5. No navegador, acesse:
http://localhost/projetoathia/


### 🔁 Clonando o repositório:

```bash
# Clone o repositório
git clone https://github.com/rogermsouza/Projeto_Athia.git

# Acesse o diretório
cd Projeto_Athia

# (Opcional) Mova para o diretório htdocs do XAMPP, se necessário:
# mv Projeto_Athia /c/xampp/htdocs/

# Inicie Apache e MySQL pelo XAMPP

# No navegador, acesse:
http://localhost/projetoathia/

