# Calculadora Financeira

Uma aplicação web para cálculos financeiros com suporte a diferentes tipos de investimentos.

## Recursos

- Cálculo de investimentos (Poupança, CDI, SELIC)
- Taxas atualizadas do mercado
- Interface responsiva
- API RESTful

## Instalação

1. Clone o repositório
2. Configure o arquivo `app/config/config.php`
3. Execute o script `install.sql` no seu banco de dados
4. Configure o servidor web conforme `.htaccess`

## Tecnologias

- PHP 7.4+
- MySQL 5.7+
- Tailwind CSS
- JavaScript ES6+

## Estrutura do Projeto

```
├── app/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   └── views/
├── api/
├── assets/
│   ├── css/
│   └── js/
└── public_html/
```

## Configuração

1. Banco de Dados:
   - Execute o script `install.sql`
   - Configure as credenciais em `config.php`

2. Servidor Web:
   - Configure o Apache/Nginx
   - Ajuste as permissões
   - Configure o PHP

## Segurança

- Proteção CSRF
- Headers de segurança
- Sanitização de inputs
- Cache configurável
- Logs de sistema

## Licença

MIT