# 📋 Sistema de Cadastro Simples - PHP

Um sistema básico de cadastro de usuários desenvolvido em PHP puro, ideal para aprendizado e projetos iniciais.

## 📖 Descrição

Sistema web que permite cadastrar usuários através de um formulário e exibir uma lista dos cadastros realizados. Desenvolvido com PHP puro, sem frameworks, focado em conceitos fundamentais da linguagem.

## ✨ Funcionalidades

- ✅ Formulário de cadastro com validação
- ✅ Campos: nome, e-mail e senha
- ✅ Armazenamento de dados em arquivo (.txt ou .json)
- ✅ Listagem de usuários cadastrados
- ✅ Interface responsiva e intuitiva

## 🛠️ Tecnologias Utilizadas

- **PHP** - Linguagem de programação server-side
- **HTML5** - Estruturação das páginas
- **CSS3** - Estilização da interface
- **JavaScript** (opcional) - Interatividade client-side

## 📂 Estrutura do Projeto

```
-Sistema_de_Cadastro_Simples-Php/
│
├── assets/              # Recursos estáticos (CSS, JS, imagens)
├── config/              # Arquivos de configuração
│   └── db.php          # Configurações de banco de dados
├── includes/            # Arquivos de inclusão
│   └── header.php      # Cabeçalho das páginas
├── cadastro.php         # Página principal de cadastro
└── README.md           # Documentação do projeto
```

## 🚀 Como Usar

### Pré-requisitos

- PHP 7.4 ou superior instalado
- Servidor web (Apache, Nginx) ou PHP built-in server
- Navegador web moderno

### Instalação

1. Clone o repositório:
```bash
git clone https://github.com/Victorkaue333/-Sistema_de_Cadastro_Simples-Php.git
```

2. Navegue até o diretório do projeto:
```bash
cd -Sistema_de_Cadastro_Simples-Php
```

3. Inicie o servidor PHP:
```bash
php -S localhost:8000
```

4. Acesse no navegador:
```
http://localhost:8000/cadastro.php
```

## 💡 Conceitos Aprendidos

Este projeto aborda conceitos fundamentais de PHP:

- **$_POST** - Captura de dados de formulários
- **Validação de formulários** - Sanitização e validação de inputs
- **Funções PHP** - Criação e uso de funções customizadas
- **Manipulação de arquivos** - Leitura e escrita em arquivos
- **Segurança básica** - Prevenção de injeção de código
- **Estruturação de projetos** - Organização de código em diretórios

## 📝 Exemplo de Uso

1. Preencha o formulário com:
   - Nome completo
   - E-mail válido
   - Senha segura

2. Clique em "Cadastrar"

3. Visualize o usuário na lista de cadastrados

## 🔒 Segurança

⚠️ **Nota**: Este é um projeto educacional. Para ambientes de produção, considere:

- Usar banco de dados ao invés de arquivos
- Implementar hash de senhas (password_hash)
- Adicionar proteção contra SQL Injection e XSS
- Implementar validação server-side robusta
- Usar HTTPS para comunicação segura

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:

1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abrir um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.

## 👨‍💻 Autor

**Victor Kaue**

- GitHub: [@Victorkaue333](https://github.com/Victorkaue333)

## 🌟 Agradecimentos

Projeto desenvolvido para fins educacionais e de aprendizado em PHP.

---

⭐ Se este projeto te ajudou, considere dar uma estrela!
