# Sistema Especialista de Sintomas

Sistema feito para conseguir distinção entre doenças com sintomas bem parecidos, e no final da respostas, ele gera uma porcentagem com a chance de qual doença pode ser.

As regras para chegarem nas doenças foram pegas do gov.br sobre cada doença em específico.

## Como rodar o projeto

Primeiro, entra na pasta do projeto:
```bash
cd health-compass
```

Depois, tem que instalar as dependências (é obrigatório pra funcionar):
```bash
npm install
```

Se quiser, também pode ver as dependências no arquivo `requirements.txt`.

Depois, só rodar:
```bash
npm run dev
```

O projeto vai abrir no navegador (geralmente em http://localhost:8080).

## Pra fazer o build de produção

Se quiser gerar a versão de produção:
```bash
npm run build
```
