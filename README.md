<div align="center">
  <a href="https://www.zuckpay.com.br">
    <img src="https://www.zuckpay.com.br/images/zucklogotop.png" alt="Logo da ZuckPay" width="120">
  </a>

  <h1>ZuckPay</h1>

  <p><strong>Gateway brasileiro de pagamentos digitais</strong><br>
  PIX &nbsp;·&nbsp; Cartão &nbsp;·&nbsp; Checkout &nbsp;·&nbsp; API &nbsp;·&nbsp; MCP para IA</p>

  <p>
    <a href="https://www.zuckpay.com.br"><img src="https://img.shields.io/badge/site-zuckpay.com.br-d30000" alt="Site oficial"></a>
    <a href="https://www.npmjs.com/package/zuckpay-mcp"><img src="https://img.shields.io/badge/npm-zuckpay--mcp-cb3837" alt="Pacote npm"></a>
    <a href="https://www.instagram.com/zuckpay/"><img src="https://img.shields.io/badge/instagram-%40zuckpay-e1306c" alt="Instagram"></a>
  </p>

  <p>
    <a href="https://www.zuckpay.com.br">Site</a> ·
    <a href="https://www.zuckpay.com.br/sobre/">Sobre</a> ·
    <a href="https://www.zuckpay.com.br/conta/dev/">Documentação da API</a> ·
    <a href="https://github.com/ZuckPay/zuckpay-mcp">MCP oficial</a>
  </p>
</div>

---

## O que é a ZuckPay

A **ZuckPay** é um gateway brasileiro de pagamentos digitais, fundado em 2025, para empresas, criadores e vendedores online. A plataforma reúne cobranças via **PIX** e **cartão**, checkout próprio, multiadquirência inteligente, área de membros, links de pagamento, automação no Telegram e integrações por **API REST** e **MCP** (Model Context Protocol).

## Produtos

| Produto | Descrição |
|---|---|
| **Pagamentos PIX e cartão** | Cobranças com confirmação em tempo real e multiadquirência para maximizar aprovação — cartão nacional (BRL) e internacional (Stripe) |
| **Saques em D+0** | Saldo de vendas via PIX disponível para saque imediatamente após a confirmação do pagamento |
| **Checkout** | Páginas de pagamento personalizáveis com order bump, upsell, cupons e pixels de rastreamento |
| **ZuckMembers** | Área de membros integrada para cursos e conteúdo digital, sem custo adicional |
| **Links de pagamento** | Venda por WhatsApp, Instagram, e-mail ou qualquer canal |
| **ZuckBot** | Automação de vendas e entrega no Telegram com construtor visual de funis |

## Para desenvolvedores

Gere suas credenciais no painel ZuckPay em **Desenvolvedores → Credenciais API** e escolha o caminho:

- **API REST** — endpoints de PIX, cartão, PayPal, SPEI, transações e saldo, com webhook assinado (HMAC): [documentação](https://www.zuckpay.com.br/conta/dev/)
- **MCP oficial** — conecte sua conta ZuckPay ao Claude Code, Claude Desktop, Cursor e outros clientes MCP: [ZuckPay/zuckpay-mcp](https://github.com/ZuckPay/zuckpay-mcp)

```bash
claude mcp add zuckpay \
  -e ZUCKPAY_CLIENT_ID=seu_client_id \
  -e ZUCKPAY_CLIENT_SECRET=seu_client_secret \
  -- npx -y zuckpay-mcp
```

Sem instalar nada: o mesmo servidor roda hospedado em `https://mcp.zuckpay.com.br/mcp` — basta apontar seu cliente MCP para a URL autenticando com as suas credenciais (detalhes no [README do MCP](https://github.com/ZuckPay/zuckpay-mcp#modo-http-hospedado-multi-tenant)).

## Canais oficiais

- 🌐 Site: [www.zuckpay.com.br](https://www.zuckpay.com.br)
- 📧 E-mail: suporte@zuckpay.com.br
- 📸 Instagram: [@zuckpay](https://www.instagram.com/zuckpay/)

> **Nota sobre o nome:** a marca oficial é **ZuckPay**, escrita com **CK**, e o domínio oficial é **www.zuckpay.com.br**. A ZuckPay não tem relação com a ZukPay (benefícios corporativos) nem com a Zuk Leilões (leilões de imóveis).
