# Frois Xavier Construtora — Template

Site one-page em HTML puro + Tailwind CSS (CDN).  
Domínio: **froisxavier.com.br**

---

## 🚀 Deploy na Vercel

1. Suba os arquivos em um repositório GitHub (pode ser privado).
2. Acesse [vercel.com](https://vercel.com) → **Add New Project** → importe o repo.
3. Framework Preset: **Other** (ou "Static Site").
4. Clique em **Deploy**. Pronto.
5. Em **Settings → Domains**, adicione `froisxavier.com.br` e siga as instruções de DNS.

---

## ✏️ Checklist de Edição

Procure por `[EDITAR]` no arquivo `index.html` para localizar todos os pontos a preencher.

### Conteúdo obrigatório
- [ ] Nome / razão social da empresa
- [ ] Logo (substitua o bloco `<div class="w-11 h-11...">` por `<img src="logo.png">`)
- [ ] Slogan / headline principal (seção Hero)
- [ ] Descrição curta da empresa (Hero e Sobre)
- [ ] Texto completo da seção **Sobre**
- [ ] 4 diferenciais/pilares da empresa
- [ ] Texto e pontos de cada um dos 3 **Serviços**
- [ ] Nomes, tipos, cidades e anos de cada uma das 6 **Obras**
- [ ] Número de WhatsApp (substituir `XXXXXXXXXXX` — formato: `5511999999999`)
- [ ] E-mail de contato
- [ ] Telefone de exibição
- [ ] Cidade/região de atendimento
- [ ] CNPJ e número do CREA no rodapé
- [ ] Ano de fundação (barra de stats)
- [ ] Número de obras entregues (barra de stats)

### Imagens
- [ ] Substituir cada bloco `<div class="... stripe-bg">` por `<img src="foto.jpg" class="w-full h-full object-cover absolute inset-0">`
- Sugestão de imagens necessárias:
  - `hero.jpg` — foto principal (proporção 21:9, min. 1400px de largura)
  - `sobre.jpg` — equipe ou canteiro (proporção 4:5)
  - `servico-1.jpg`, `servico-2.jpg`, `servico-3.jpg` (proporção 4:3)
  - `obra-1.jpg` … `obra-6.jpg` (3:4 ou 4:3, conforme definido)

### Opcional
- [ ] Trocar Tailwind CDN pela build local (`npx tailwindcss -i input.css -o style.css --minify`)
- [ ] Adicionar Google Analytics / Meta Pixel
- [ ] Adicionar `<link rel="icon" href="favicon.ico">`
- [ ] Ajustar os filtros da seção Obras conforme as categorias reais

---

## 📁 Estrutura de arquivos

```
/
├── index.html      ← Página completa
├── vercel.json     ← Config de deploy
└── README.md       ← Este arquivo
```

Imagens e logo podem ser colocadas numa pasta `/assets/` e referenciadas como `src="assets/hero.jpg"`.
