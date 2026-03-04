# Gerador de Assinatura de E-mail - Grupo Caminho

Aplicação web para gerar assinaturas de e-mail padronizadas para todas as lojas do Grupo Caminho.

## Marcas e Lojas Disponíveis

### Ford
- 2152 - Piracicaba
- 2155 - Bauru
- 2156 - Presidente Prudente
- 2157 - Americana
- 3199 - Araçatuba
- 6664 - São José do Rio Preto
- 5315 - Marilia
- 5334 - campinas

### Hyundai
- 19039 - Catanduva
- 26092 - Piraricaba
- 26093 - Limeira

### RAM
- 90702 - Araçatuba

### Centralizadora
- 40 - Araçatuba

### Omoda & Jaecoo
- OJXXX - Piracicaba

### Fiat
- 90350 - Araçatuba
- 90450 - Votuporanga
- 90742 - Votuporanga

### DAF
- 60572 - São José do Rio Preto 
- 60577 - Ribeirão Preto
- 60942 - Araraquara
- 60960 - Araçatuba

### GWM
- BR2003C - São José do Rio Preto
- BR2014C - Bauru
- BR2017C - Presidente Prudente
- BR2026C - Araçatuba
- BRMAXXXX - Marilia

## Deploy no Vercel

### Opção 1: Via Interface Web
1. Acesse [vercel.com](https://vercel.com)
2. Faça login ou crie uma conta
3. Clique em "Add New" > "Project"
4. Faça upload da pasta `assinatura-generator`
5. Clique em "Deploy"

### Opção 2: Via CLI
```bash
npm i -g vercel
cd assinatura-generator
vercel
```

## Como Usar

1. Acesse a URL do projeto após o deploy
2. Digite o nome completo do colaborador
3. Selecione a marca
4. Selecione a loja
5. Selecione a função/cargo
6. Clique em "Copiar HTML" ou "Copiar Formatado"
7. Cole a assinatura no cliente de e-mail

## Configurando no Cliente de E-mail

### Outlook
1. Vá em Arquivo > Opções > Email > Assinaturas
2. Crie uma nova assinatura
3. Cole o conteúdo copiado (Copiar Formatado)
4. Salve e defina como padrão

### Gmail
1. Vá em Configurações (engrenagem) > Ver todas as configurações
2. Na aba "Geral", localize "Assinatura"
3. Crie uma nova assinatura
4. Cole o conteúdo copiado (Copiar Formatado)
5. Salve as alterações

### Thunderbird
1. Vá em Editar > Configurações da conta
2. Selecione a conta de e-mail
3. Marque "Usar HTML"
4. Cole o código HTML copiado
5. Clique em OK

## Personalização

Para adicionar novas lojas ou modificar informações existentes, edite o objeto `storesData` no arquivo `index.html`.

## Licença

Uso interno - Grupo Caminho Veículos
