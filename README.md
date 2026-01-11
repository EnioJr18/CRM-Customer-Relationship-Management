# 🚀 Django Sales CRM

Um sistema de Gestão de Relacionamento com o Cliente (CRM), o projeto simula uma aplicação real para gestão de leads, permitindo cadastro, acompanhamento de histórico e análise de métricas.

![Status do Projeto](https://img.shields.io/badge/Status-Em_Desenvolvimento-yellow)
![Python](https://img.shields.io/badge/Python-3.13%2B-blue)
![Django](https://img.shields.io/badge/Django-5.x-green)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Neon-336791)

## 📋 Sobre o Projeto

Este projeto faz parte do meu portfólio de desenvolvimento Backend. O objetivo é criar uma solução robusta utilizando a arquitetura **MVT (Model-View-Template)** do Django, demonstrando boas práticas de engenharia de software, segurança e modelagem de dados.

O sistema permite que vendedores cadastrem potenciais clientes (Leads), registrem interações (ligações, emails) e movam o cliente através de um funil de vendas.

## 🚀 Funcionalidades

### Gestão de Leads (CRUD Completo)
- [x] **Dashboard:** Visão geral com métricas (Total de leads, distribuição por status e prioridade).
- [x] **Cadastro:** Adição de novos clientes com validação de dados.
- [x] **Listagem:** Tabela interativa com busca e filtros rápidos.
- [x] **Detalhamento:** Página exclusiva por cliente mostrando dados cadastrais e linha do tempo.
- [x] **Edição e Exclusão:** Atualização de dados e remoção segura com confirmação.

### Histórico e Interações
- [x] **Timeline:** Registro de notas e conversas (interações) para cada cliente.
- [x] **Histórico:** Visualização cronológica do relacionamento com o cliente.

### Recursos Avançados
- [x] **Autenticação:** Sistema de Login/Logout seguro (apenas usuários autenticados acessam o sistema).
- [x] **Busca e Filtros:** Pesquisa por nome e filtros rápidos (Alta Prioridade, Sem Interação, Recentes).
- [x] **Exportação de Dados:** Geração de relatórios em **CSV** (Leads e Interações) para análise externa.
- [x] **Responsividade:** Interface adaptada para Desktop e Mobile usando Bootstrap 5.

## 🛠️ Tecnologias Utilizadas

- **Backend:** Python 3, Django 5
- **Banco de Dados:** PostgreSQL (Hospedado na Neon Tech)
- **Frontend:** HTML5, CSS3, Bootstrap 5 (CDN)
- **Versionamento:** Git & GitHub

## 🚀 Como rodar o projeto localmente

### Pré-requisitos
* Python instalado
* Conta no Neon (ou PostgreSQL local)

### Passo a Passo

1.  **Clone o repositório**
    ```bash
    git clone https://github.com/EnioJr18/CRM-Customer-Relationship-Management-.git
    cd crm-portfolio
    ```

2.  **Crie e ative o ambiente virtual**
    ```bash
    # Windows
    python -m venv venv
    venv\Scripts\activate

    # Linux/Mac
    source venv/bin/activate
    ```

3.  **Instale as dependências**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Configure as Variáveis de Ambiente**
    Crie um arquivo `.env` na raiz do projeto e adicione a URL do seu banco de dados:
    ```env
    SECRET_KEY=sua_chave_secreta
    DEBUG=True
    DATABASE_URL=postgres://usuario:senha@host-neon.tech/neondb?sslmode=require ou sqlite
    ```

5.  **Execute as Migrations**
    ```bash
    python manage.py migrate
    ```

6.  **Crie um Superusuário (para acessar o Admin)**
    ```bash
    python manage.py createsuperuser
    ```

7.  **Inicie o servidor**
    ```bash
    python manage.py runserver
    ```

8. **Acesse**
```bash
http://127.0.0.1:8000/
```

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
Desenvolvido por **Enio Jr** para fins de estudo e portfólio 💻

📧 Entre em contato: eniojr100@gmail.com <br>
🔗 LinkedIn: https://www.linkedin.com/in/enioeduardojr/ <br>
📷 Instagram: https://www.instagram.com/enio_juniorrr/ <br>
