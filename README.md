# Caneta Depiladora — Landing Page

Site de vendas da Caneta Depiladora Facial Elétrica.

## Deploy na Vercel

1. Faça login em [vercel.com](https://vercel.com)
2. Clique em **"Add New Project"**
3. Importe este repositório (ou arraste a pasta)
4. Clique em **"Deploy"** — sem nenhuma configuração extra

## Estrutura

```
/
├── index.html        ← página principal
├── sobrancelha.png   ← imagem do produto
├── vercel.json       ← config da Vercel
└── README.md
```

## Personalização

- **Link do checkout:** `index.html` → procure `CHECKOUT_URL`
- **Pixel do Meta:** `index.html` → procure `fbq('init'`
- **Avaliações/Depoimentos:** `index.html` → procure `const REVIEWS` e os blocos `.testi-card`
