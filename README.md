# 🐾 Pet Shower Truck

Site institucional (landing page) da **Pet Shower Truck** — serviço de **banho e tosa móvel** que atende na porta da casa do cliente em **Monte Mor - SP** e região.

> Levamos toda a estrutura e o cuidado de um pet shop até a sua porta, sem estresse para o seu cão.

---

## 📋 Sobre o projeto

Página única (single-page), responsiva e mobile-first, feita com **HTML, CSS e JavaScript puro** — sem dependências, sem build e sem gerenciador de pacotes. Basta abrir o `index.html` no navegador.

O objetivo é apresentar a empresa, divulgar os serviços e pacotes, mostrar fotos dos atendimentos e facilitar o agendamento direto pelo **WhatsApp**.

---

## ✨ Seções e funcionalidades

A página é dividida nas seguintes seções (na ordem em que aparecem):

- **Navbar** — menu fixo com navegação por âncoras e menu hambúrguer no mobile.
- **Hero** — chamada principal com botão de agendamento pelo WhatsApp.
- **Sobre** — diferenciais da empresa:
  - 🚐 Atendimento móvel (caminhão equipado vai até você)
  - ❤️ Atenção individual (um pet de cada vez)
  - 😊 Menos estresse para o animal
  - 📍 Atendimento em Monte Mor - SP e região
- **Serviços** — cards com os serviços oferecidos:
  - 🛁 Banho Completo
  - ✂️ Tosa (higiênica, na raça e personalizada) — *destaque "Popular"*
  - 🌟 Banho + Tosa (combo)
  - 🐶 Adestramento
  - 🍖 Comida Natural para Pets
- **Pacotes de Fidelidade** — planos recorrentes:
  - 📅 Pacote Semanal
  - 🌟 Pacote Quinzenal — *destaque "Mais Econômico"*
- **Galeria** — grade de fotos dos atendimentos (pasta `images/`).
- **Contato** — telefone/WhatsApp, Instagram e localização.
- **Footer** — logo, links e direitos reservados.
- **Botão flutuante do WhatsApp** — acesso rápido em qualquer ponto da página.

Cada serviço e pacote tem um botão que abre o **WhatsApp** com uma mensagem pré-preenchida correspondente, agilizando o contato.

---

## 🗂️ Estrutura de arquivos

```
PetShowerTruck/
├── index.html      # Conteúdo e estrutura da página
├── style.css       # Estilos (mobile-first, variáveis CSS, breakpoints em 900px e 640px)
├── script.js       # Menu hambúrguer e sombra da navbar ao rolar
├── images/         # Fotos dos atendimentos (dog1..dog13, gato1, gato2)
└── README.md
```

---

## 🎨 Identidade visual

Paleta definida como variáveis CSS em `style.css`:

| Cor       | Hex       | Uso              |
|-----------|-----------|------------------|
| Turquesa  | `#00B4D8` | Cor principal    |
| Amarelo   | `#FFD60A` | Destaques        |
| Laranja   | `#FF6B35` | Ações/CTAs       |
| Texto     | `#1A1A2E` | Texto principal  |

- **Fonte:** [Poppins](https://fonts.google.com/specimen/Poppins) (via Google Fonts).

---

## 📞 Contato da empresa

- **WhatsApp / Telefone:** (19) 98405-2004
- **Instagram:** [@petshowertruck](https://www.instagram.com/petshowertruck/)
- **Atendimento:** Monte Mor - SP e região (na porta da sua casa)

---

## 🚀 Como visualizar

Não há build nem instalação. Basta abrir o arquivo `index.html` no navegador:

```bash
# Windows
start index.html

# macOS
open index.html

# Linux
xdg-open index.html
```

---

## 🛠️ Tecnologias

- HTML5
- CSS3 (variáveis, Flexbox/Grid, design responsivo mobile-first)
- JavaScript (vanilla)

---

## 📝 Como atualizar as fotos da galeria

1. Coloque os arquivos na pasta `images/`.
2. Adicione (ou troque) as tags `<img>` dentro da div `.galeria-grid` no `index.html`:
   ```html
   <img src="images/minha-foto.jpeg" alt="Pet Shower Truck - descrição da foto">
   ```

---

© Pet Shower Truck — Banho e Tosa Móvel em Monte Mor - SP. Todos os direitos reservados.
