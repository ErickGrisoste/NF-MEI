# 📌 NF-MEI: Visão Geral

### 🧨 Problema
Muitos MEIs e autônomos enfrentam dificuldades para emitir notas fiscais devido à burocracia, sistemas confusos oferecidos por prefeituras e falta de organização com seus clientes, serviços e orçamentos. O processo é demorado, pouco intuitivo e feito de forma manual.

### 💡 Solução
Um aplicativo simples, acessível e voltado exclusivamente para o MEI. O NF-MEI permite gerar notas fiscais com agilidade, emitir orçamentos e recibos profissionais e organizar clientes e serviços de forma prática.

### 👥 Usuários e Clientes
#### Usuários (quem usa):

- Microempreendedores Individuais
- Prestadores de serviço (designers, programadores, eletricistas, etc.)
- Pequenos vendedores autônomos
- Profissionais liberais com CNPJ

#### Clientes (quem paga):
- Os próprios usuários, no plano NF-MEI Plus, buscando mais agilidade e controle financeiro.

### 🛠 Recursos Principais
#### Versão Free:
- Emissão manual de notas fiscais
- Geração de PDF profissional da nota
- Histórico básico de NFs

#### Versão Plus:
- Cadastro de clientes e serviços
- Geração de orçamentos e recibos profissionais
- Conversão de orçamentos em NFs com 1 clique
- Relatórios básicos de faturamento

### 📲 Canais
- Aplicativo Web (inicialmente)
- Divulgação via redes sociais (Instagram, TikTok, YouTube)
- Parcerias com contadores e cursos de MEI
- Comunidades de autônomos e grupos de WhatsApp

### 💸 Custo e Receita
#### Custos:
- Desenvolvimento do sistema
- Hospedagem (servidor, banco de dados, envio de PDFs)
- Manutenção e atualizações
- Marketing digital

#### Receitas:
- Plano gratuito com recursos básicos
- Plano NF-MEI Plus com assinatura mensal (ex: R$ 9,90)
- Possibilidade de planos anuais com desconto
- Potencial de revenda white-label para contadores


Requisitos funcionais:
Cadastro de usuários (MEIs) com login e senha;
Deve ser possível emitir notas fiscais preenchendo os dados manualmente;
O sistema deve gerar notas fiscais em PDF com layout profissional;
Deve existir um histórico básico das notas emitidas;
Na versão paga, o usuário poderá: Cadastrar cliente e serviços/produtos; Criar orçamentos; Converter orçamentos em NFs com um clique; Visualizar relatórios básicos de faturamento mensal.

Requisitos não funcionais:
O sistema será desenvolvido em Spring boot  no backend;
O frontend será construído com React/Angular;
O banco de dados utilizando PostgresSQL;
O sistema será hospedado na Vercel;
A aplicação deve ser acessível via celular. Na versão NF-MEI Plus o usuário poderá ter uma visualização mais ampla via web.

