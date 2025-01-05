# Calculadora Financeira

Aplicação web para cálculos financeiros com suporte a diferentes tipos de investimentos e comparações.

## Funcionalidades

- Cálculo de investimentos (Poupança, CDI, SELIC)
- Simulador PGBL vs CDB
- Taxas atualizadas do mercado
- Interface responsiva
- API para integrações
- Sistema de cache para melhor performance
- Proteção CSRF
- Logs de sistema

## Tecnologias

- PHP 7.4+
- MySQL 5.7+
- JavaScript ES6+
- Tailwind CSS
- API RESTful

## Estrutura do Projeto

```
/
├── api/                 # Endpoints da API
├── app/                 # Núcleo da aplicação
├── assets/             # Recursos estáticos
├── classes/            # Classes PHP
├── includes/           # Arquivos incluídos
├── logs/              # Logs do sistema
└── sections/          # Seções do site
```

## Configuração

1. Clone o repositório:
```bash
git clone https://github.com/Lucasdoreac/Calculadora_Financeira_Luaraujo.com.git
```

2. Configure o banco de dados:
- Execute o script `install.sql`
- Configure as credenciais em `includes/config.php`

3. Configure o servidor web:
- Aponte o DocumentRoot para a pasta public_html
- Certifique-se que o mod_rewrite está ativado

## Desenvolvimento

1. Branches principais:
- main: código em produção
- develop: desenvolvimento
- feature/*: novas funcionalidades
- hotfix: correções urgentes

2. Para contribuir:
- Crie uma branch a partir do develop
- Faça suas alterações
- Envie um pull request

## Licença

MIT