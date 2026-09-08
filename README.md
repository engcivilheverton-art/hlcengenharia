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
    ├── images/         # Imagens futuras
    ├── css/            # Arquivos CSS futuros
    └── js/             # Arquivos JavaScript futuros
```

> O site é **single-file** — todo o conteúdo, estilos e imagens estão embutidos no `index.html`.

---

## 🚀 Como publicar no GitHub Pages

### Passo 1 — Criar repositório
1. Acesse [github.com](https://github.com) e faça login
2. Clique em **"New repository"** → nome: `hlc-engenharia` → **Public** → criar

### Passo 2 — Enviar os arquivos
**Pela interface do GitHub (mais fácil):**
1. No repositório criado, clique em **"uploading an existing file"**
2. Arraste todos os arquivos da pasta `hlc-engenharia`
3. Clique em **"Commit changes"**

**Via terminal (Git):**
```bash
git init
git add .
git commit -m "site HLC Engenharia"
git branch -M main
git remote add origin https://github.com/seu-usuario/hlc-engenharia.git
git push -u origin main
```

### Passo 3 — Ativar GitHub Pages
1. No repositório → **Settings** → **Pages**
2. Source: `Deploy from a branch`
3. Branch: `main` / `/ (root)` → **Save**
4. Aguarde ~2 minutos — o link aparecerá no topo da página

---

## 🔗 Domínio personalizado (opcional)

Para usar `hlcengenharia.com.br`:
1. Registre em [registro.br](https://registro.br)
2. Adicione registro CNAME apontando para `seu-usuario.github.io`
3. Em Settings → Pages, informe o domínio customizado

---

## ✏️ Como editar

Abra `index.html` em qualquer editor de texto (recomendamos [VS Code](https://code.visualstudio.com/)).

Principais pontos para atualizar:
- **Textos:** tags `<h1>`, `<h2>`, `<p>`
- **WhatsApp:** busque `wa.me/5531999851926`
- **E-mail:** busque `Projetos@hlcengenharia.com.br`
- **Portfólio:** seção `<!-- PORTFÓLIO -->` para adicionar novos projetos
- **Cores:** variáveis em `:root {` no início do CSS

---

## 📞 Contato

- **E-mail:** Projetos@hlcengenharia.com.br
- **WhatsApp:** (31) 9 9985-1926
- **Localização:** Belo Horizonte — MG
