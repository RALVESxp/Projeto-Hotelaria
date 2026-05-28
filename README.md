<readme>
    
# 🏨 Projeto Vesta

**Sistema de Gestão Hoteleira** desenvolvido para automatizar e otimizar as operações diárias de hotéis e pousadas. O Vesta centraliza o controle de reservas, o cadastro de hóspedes e a gestão financeira em uma plataforma eficiente, robusta e de fácil navegação.

## 🚀 Tecnologias Utilizadas

O sistema foi construído utilizando as seguintes tecnologias:

* **Back-end:** PHP
* **Banco de Dados:** MySQL
* **Servidor Web:** Apache
* **Front-end:** HTML5, CSS3, JavaScript

## ✨ Funcionalidades Principais

* 👥 **Gestão de Hóspedes:** Cadastro detalhado e controle de histórico de clientes.
* 📅 **Controle de Reservas:** Gerenciamento de disponibilidade de quartos em tempo real, abrangendo os fluxos de check-in e check-out.
* 🛏️ **Administração de Acomodações:** Cadastro e controle de status (livre, ocupado, manutenção) dos quartos.
* 💰 **Frente de Caixa e Financeiro:** Registro de movimentações financeiras, pagamentos e controle de caixa da recepção.

## ⚙️ Como Executar Localmente

O sistema foi projetado para rodar em servidores locais. Você pode utilizar soluções como XAMPP, WAMP ou o **USBWebserver**.

1.  Clone este repositório para a sua máquina local:
    ```bash
    git clone [https://github.com/SEU_USUARIO/vesta.git](https://github.com/SEU_USUARIO/vesta.git)
    ```
2.  Mova os arquivos do projeto para o diretório público do seu servidor (ex: pasta `htdocs` no XAMPP ou a pasta raiz correspondente no USBWebserver).
3.  Inicie os serviços do **Apache** e do **MySQL**.
4.  Acesse o seu gerenciador de banco de dados (ex: phpMyAdmin, geralmente em `http://localhost/phpmyadmin`) e crie um banco de dados chamado `vesta` (ou o nome configurado no projeto).
5.  Importe o script `.sql` (se incluído no repositório) para criar as tabelas e a estrutura do banco.
6.  Abra o seu navegador e acesse o sistema através de: `http://localhost/vesta` (ou a porta específica configurada no seu servidor local, como `http://localhost:8080/vesta`).

## 👨‍💻 Autor

Desenvolvido por **Thiago Ramalho Alves** como projeto acadêmico e de portfólio de desenvolvimento Full-Stack.
</readme>
