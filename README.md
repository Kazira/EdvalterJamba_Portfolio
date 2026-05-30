# Edvalter Jamba — Portfolio Estático

Portfolio profissional 100% estático — pronto para GitHub Pages.

## 🚀 Como publicar no GitHub Pages (GRÁTIS)

### Passo 1 — Criar repositório no GitHub
1. Vai a **github.com** e faz login
2. Clica em **"New repository"**
3. Nome sugerido: `EdvalterJamba_Portfolio` (ou `kazira.github.io`)
4. Marca como **Public**
5. Clica **"Create repository"**

### Passo 2 — Fazer upload dos ficheiros
**Opção A — Pelo website (mais fácil):**
1. Abre o repositório criado
2. Clica **"uploading an existing file"**
3. Arrasta TODOS os ficheiros desta pasta para o browser
4. Clica **"Commit changes"**

**Opção B — Com Git (terminal):**
```bash
cd portfolio_static
git init
git add .
git commit -m "Portfolio inicial"
git branch -M main
git remote add origin https://github.com/SEU_USERNAME/EdvalterJamba_Portfolio.git
git push -u origin main
```

### Passo 3 — Activar GitHub Pages
1. No repositório, vai a **Settings → Pages**
2. Em "Source" selecciona **"Deploy from a branch"**
3. Branch: **main** / Folder: **/ (root)**
4. Clica **Save**
5. Aguarda 1-2 minutos

### Passo 4 — O teu link
O portfolio ficará disponível em:
`https://SEU_USERNAME.github.io/EdvalterJamba_Portfolio/`

Ou se o repositório se chamar `SEU_USERNAME.github.io`:
`https://SEU_USERNAME.github.io`

---

## 📂 Estrutura dos ficheiros

```
portfolio_static/
├── index.html              ← Portfolio principal (TUDO aqui)
├── README.md               ← Este ficheiro
└── assets/
    ├── photo.jpg           ← Foto profissional (hero)
    ├── photos/
    │   ├── edvalter_luanda.jpg
    │   └── edvalter_capetown.jpg
    ├── branding/
    │   ├── lanchinhos_logo.jpg
    │   ├── lanchinhos_pitaya.png
    │   ├── lanchinhos_maracuja.png
    │   ├── lanchinhos_chocolate.png
    │   ├── lanchinhos_iogurte.png
    │   ├── lanchinhos_natural.png
    │   └── lanchinhos_flyer.png
    ├── social/
    │   └── ecossulo_logo.jpg
    └── doc/
        └── CV_Edvalter_Jamba.pdf  ← Coloca o teu CV aqui!
```

---

## ✏️ Como editar o conteúdo

O ficheiro `index.html` contém TODO o conteúdo.
Cada texto tem duas versões: `data-pt` (Português) e `data-en` (Inglês).

### Exemplo de como editar texto bilingue:
```html
<!-- ANTES -->
<span data-pt>O meu texto em português</span>
<span data-en>My text in English</span>

<!-- DEPOIS — basta alterar o texto dentro das tags -->
<span data-pt>Novo texto em português</span>
<span data-en>New text in English</span>
```

### Trocar a foto de perfil:
Substitui o ficheiro `assets/photo.jpg` pela tua nova foto (mantém o mesmo nome).

### Adicionar o CV:
Coloca o teu CV em PDF em `assets/doc/CV_Edvalter_Jamba.pdf`

### Alterar cores:
No início do `index.html`, na secção `:root`, podes alterar:
```css
--gold: #b8893a;    /* cor dourada principal */
--teal: #1e7a6e;    /* cor verde-teal */
--kz:   #2a4fa8;    /* azul da Kazira */
```

---

## 🌐 Domínio personalizado (opcional)

Se tiveres um domínio próprio (ex: `edvalterjamba.com`):
1. Cria um ficheiro chamado `CNAME` na raiz do repositório
2. Dentro escreve apenas: `edvalterjamba.com`
3. Nas definições DNS do teu domínio, aponta para o GitHub Pages

---

## ✅ Funcionalidades

- ✅ 100% estático — sem PHP, sem base de dados
- ✅ Bilingue PT/EN com troca instantânea
- ✅ Língua guardada no navegador (localStorage)
- ✅ Design responsivo: Desktop · Tablet · Mobile
- ✅ Cursor personalizado
- ✅ Animações de entrada ao scroll
- ✅ Carrossel de projetos
- ✅ Galeria com lightbox e filtros
- ✅ Botão "voltar ao topo"
- ✅ Optimizado para recrutadores Oil & Gas

---

*Portfolio de Edvalter da Costa Jamba — Luanda, Angola*
