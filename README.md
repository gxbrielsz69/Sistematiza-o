# Clínica Alento — Landing Page

Landing page estática desenvolvida para a Clínica Alento, apresentando a clínica e seus principais serviços de saúde (atendimento médico, exames laboratoriais e de imagem, aconselhamento nutricional e outros procedimentos de cuidado).

## 🗂️ Estrutura do projeto

```
clinica-alento/
├── index.html   # Estrutura e conteúdo da página
├── style.css    # Estilos (tokens de cor/tipografia, layout responsivo)
├── script.js    # Menu mobile e feedback do formulário (sem back-end)
└── README.md
```

## ✅ Requisitos atendidos

- Título da aba (`<title>`)
- 4 ilustrações originais (SVG) representando os serviços — acima do mínimo de 2 imagens
- Descrição de cada serviço oferecido
- Equipe fictícia com 3 membros, foto (avatar) e cargo
- Uso de `<h1>`, `<h2>` e `<h3>` (mais de 2 níveis de cabeçalho)
- Formulário estático com Nome, E-mail, Cidade e Estado — **não envia dados a nenhum servidor** (apenas exibe uma mensagem de confirmação em tela via JavaScript no navegador)

## ▶️ Como executar localmente

Não é necessário instalar nada. Escolha uma das opções:

**Opção 1 — Abrir diretamente**
Dê duplo clique no arquivo `index.html` (ou clique com o botão direito → Abrir com → seu navegador).

**Opção 2 — Servidor local (recomendado)**
```bash
# dentro da pasta do projeto
python3 -m http.server 8000
```
Depois acesse `http://localhost:8000` no navegador.

Ou, com a extensão **Live Server** do VS Code: clique com o botão direito em `index.html` → "Open with Live Server".

## 🌐 Publicar online (GitHub Pages)

1. Suba os arquivos para um repositório no GitHub.
2. Vá em **Settings → Pages**.
3. Em "Source", selecione a branch `main` e a pasta `/ (root)`.
4. Salve — em alguns minutos o site estará disponível em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`.

## 🎨 Notas de design

- Tipografia: **Fraunces** (display, para títulos) + **Work Sans** (texto), via Google Fonts.
- Paleta: verde-floresta, âmbar e sálvia sobre fundo marfim — evitando o visual "genérico de SaaS" (cards idênticos, gradientes, ícones de estoque).
- Ilustrações dos serviços e avatares da equipe são gerados de forma independente (SVG inline e serviço de avatares por iniciais), sem depender de bancos de imagens externos com direitos autorais.
