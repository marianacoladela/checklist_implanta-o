# Nômade — Checklist de Implantação

App PWA instalável no celular, hospedado no GitHub Pages.

## Como publicar no GitHub Pages

### 1. Criar repositório no GitHub
1. Acesse github.com e faça login
2. Clique em **New repository**
3. Nome: `nomade-checklist` (ou qualquer nome)
4. Deixe **Public**
5. Clique **Create repository**

### 2. Fazer upload dos arquivos
Na página do repositório criado:
1. Clique em **uploading an existing file**
2. Arraste a pasta inteira (ou todos os arquivos):
   - `index.html`
   - `manifest.json`
   - `sw.js`
   - pasta `icons/` com os dois ícones
3. Clique **Commit changes**

### 3. Ativar GitHub Pages
1. Vá em **Settings** → **Pages**
2. Em "Source", selecione **Deploy from a branch**
3. Branch: **main** / pasta: **/ (root)**
4. Clique **Save**
5. Aguarde ~1 minuto

### 4. Acessar o app
A URL será: `https://SEU_USUARIO.github.io/nomade-checklist/`

---

## Instalar no celular

### iPhone (Safari)
1. Abra a URL no Safari
2. Toque no botão **Compartilhar** (quadrado com seta)
3. Role e toque **Adicionar à Tela de Início**
4. Confirme o nome e toque **Adicionar**

### Android (Chrome)
1. Abra a URL no Chrome
2. Toque no menu (⋮)
3. Toque **Adicionar à tela inicial**
4. Confirme

O app abre em tela cheia, sem barra do navegador, como um app nativo!

---

## Funcionalidades
- ✅ Criar múltiplos checklists com dados do imóvel
- ✅ Marcar Sim/Não em cada item
- ✅ Campos de quantidade/tipo e observação
- ✅ Barra de progresso em tempo real
- ✅ Histórico de todos os checklists salvos
- ✅ Excluir checklists antigos
- ✅ Enviar relatório completo por WhatsApp
- ✅ Funciona offline (após primeiro acesso)
- ✅ Dados salvos localmente no celular
