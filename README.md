# HLC Engenharia — Site Institucional

Site institucional da **HLC Engenharia**, escritório de projetos de instalações prediais com foco em metodologia BIM.

## 🌐 Acesso

Após publicar no GitHub Pages, o site estará disponível em:
`https://seu-usuario.github.io/hlc-engenharia`

---

## 📁 Estrutura do Projeto

```
hlc-engenharia/
├── index.html          # Página principal (site completo)
├── README.md           # Este arquivo
└── assets/
    ├── images/         # Imagens futuras (logo, fotos, etc.)
    ├── css/            # Arquivos CSS futuros
    └── js/             # Arquivos JavaScript futuros
```

> O site atual é **single-file** — todo o conteúdo, estilos e imagens estão embutidos no `index.html`.

---

## 🚀 Como publicar no GitHub Pages

### Passo 1 — Criar repositório no GitHub
1. Acesse [github.com](https://github.com) e faça login
2. Clique em **"New repository"**
3. Nome sugerido: `hlc-engenharia`
4. Deixe como **Public**
5. Clique em **"Create repository"**

### Passo 2 — Enviar os arquivos
**Opção A — Pela interface do GitHub (mais fácil):**
1. No repositório criado, clique em **"uploading an existing file"**
2. Arraste a pasta `hlc-engenharia` ou selecione os arquivos
3. Clique em **"Commit changes"**

**Opção B — Via Git (terminal):**
```bash
git init
git add .
git commit -m "primeiro commit - site HLC Engenharia"
git branch -M main
git remote add origin https://github.com/seu-usuario/hlc-engenharia.git
git push -u origin main
```

### Passo 3 — Ativar o GitHub Pages
1. No repositório, vá em **Settings** → **Pages**
2. Em **"Source"**, selecione: `Deploy from a branch`
3. Em **"Branch"**, selecione: `main` / `/ (root)`
4. Clique em **Save**
5. Aguarde ~2 minutos e o link aparecerá no topo da página

---

## 🔗 Domínio personalizado (opcional)

Para usar `hlcengenharia.com.br` no lugar do link do GitHub:
1. Registre o domínio em [registro.br](https://registro.br)
2. No painel do domínio, adicione um registro CNAME apontando para `seu-usuario.github.io`
3. No GitHub Pages (Settings → Pages), informe o domínio customizado

---

## ✏️ Como editar o site

Abra o arquivo `index.html` em qualquer editor de texto (recomendamos o [VS Code](https://code.visualstudio.com/)) e edite diretamente.

Principais seções para personalizar:
- **Textos:** busque pelas tags `<h1>`, `<h2>`, `<p>`
- **WhatsApp:** busque por `wa.me/5531999851926` para atualizar o número
- **E-mail:** busque por `Projetos@hlcengenharia.com.br`
- **Cores:** busque por `:root {` no início do CSS

---

## 📞 Contato do escritório

- **E-mail:** Projetos@hlcengenharia.com.br
- **WhatsApp:** (31) 9 9985-1926
- **Localização:** Belo Horizonte — MG
