# Projeto trilha back-end

Projeto final para a disciplina back-end
---

## Tecnologias Utilizadas

* **PHP** (versão 8.x ou superior)
* **Composer** (Gerenciador de dependências)
* **XAMPP** (Servidor Apache e banco de dados MySQL/MariaDB)

---

## Pré-requisitos

Antes de começar, certifique-se de ter instalado em sua máquina:
* [XAMPP](https://apachefriends.org)
* [Composer](https://getcomposer.org)
* [Git](https://git-scm.com) *(opcional)*

---

## Como rodar o projeto localmente

### 1. Mova o projeto para a pasta do XAMPP
Clone este repositório ou extraia os arquivos dentro da pasta `htdocs` do seu diretório de instalação do XAMPP (geralmente em `C:\xampp\htdocs\` no Windows):

```bash
cd C:\xampp\htdocs\
git clone https://github.com
```

### 2. Instale as dependências
Abra o terminal na pasta raiz do projeto e instale os pacotes configurados no `composer.json`:

```bash
cd Projeto-back-end
composer install
```

### 3. Configure o ambiente *(opcional)*
Caso o projeto utilize variáveis de ambiente ou banco de dados:
1. Copie o arquivo de exemplo `.env.example` e renomeie para `.env` (se aplicável).
2. Abra o **Painel de Controle do XAMPP** e inicie os módulos **Apache** e **MySQL**.
3. Acesse `http://localhost/phpmyadmin`, crie o banco de dados com o nome do projeto e importe o arquivo `.sql` (caso exista).

### 4. Acesse no navegador
Com o Apache rodando, abra o navegador e acesse:

```text
http://localhost/Projeto-back-end
```
*(Nota: Se a pasta inicial do projeto for `public/`, acesse `http://localhost/Projeto-back-end/public`)*

---

## Estrutura de Pastas

```text
Projeto-back-end/
├── public/             # Arquivos públicos (index.php, CSS, JS, imagens)
├── src/                # Código-fonte principal (classes, controllers, etc.)
├── vendor/             # Dependências gerenciadas pelo Composer
├── composer.json       # Configurações e dependências do projeto
├── composer.lock       # Versões exatas das dependências instaladas
└── README.md           # Documentação do projeto
```

---

## Autor

* Kaio Alves - *Desenvolvimento* - [https://github.com/kaiodwada]
