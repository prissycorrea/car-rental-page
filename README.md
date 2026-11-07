# 🚗 Car Rental Page

Landing page de aluguel de carros com carrossel em tela cheia, efeito parallax e rodas que giram na troca de slide. Feita com HTML, CSS e JavaScript puro, sem build, usando [Swiper](https://swiperjs.com/) para o carrossel.

## ✨ Funcionalidades

- **Carrossel em tela cheia** com três modelos: Lexus LC Series, Ford Mustang e Audi A5
- **Animação das rodas**: carroceria e rodas são imagens separadas, e as rodas giram durante a transição entre slides
- **Painel de detalhes** (Lexus LC): especificações (autonomia, assentos, potência) e galeria com quatro fotos, com botão de voltar
- **Navegação** por setas e paginação
- **Header fixo** com logo, menu (Home, Electric Cars, Sport Cars, SUV) e acesso à conta
- **Barra lateral de redes sociais**
- **Layout responsivo** com ajuste para telas de até 1024px

## 🛠️ Tecnologias

| Tecnologia | Uso |
|---|---|
| HTML5 + CSS3 | Estrutura e estilos (CSS inline no `index.html`) |
| JavaScript | Interações e controle do painel de detalhes |
| [Swiper 11](https://swiperjs.com/) | Carrossel e efeito parallax (via CDN) |
| [Font Awesome 6](https://fontawesome.com/) | Ícones (via CDN) |
| [Google Fonts – Poppins](https://fonts.google.com/specimen/Poppins) | Tipografia |

## 📁 Estrutura

```
car-rental-page/
├── index.html          # Página completa (HTML, CSS e JS)
└── assets/
    └── img/
        ├── *-Body.png      # Carrocerias recortadas
        ├── *-Wheel*.png    # Rodas (animadas separadamente)
        ├── Lexus-LC-Photo-0X.png  # Galeria do painel de detalhes
        ├── logo.png
        └── user.png
```

## 🚀 Como rodar

Não precisa instalar nada. Clone o repositório e abra o `index.html` no navegador:

```bash
git clone https://github.com/prissycorrea/car-rental-page.git
cd car-rental-page
```

Depois é só abrir o `index.html`. Se preferir um servidor local, use a extensão **Live Server** do VS Code ou:

```bash
npx serve .
```

> É preciso estar conectado à internet, já que Swiper, Font Awesome e a fonte são carregados por CDN.

## 🗺️ Próximos passos

- [ ] Painel de detalhes para o Ford Mustang e o Audi A5
- [ ] Fluxo de reserva no botão **Rent Now**
- [ ] Links reais no menu e nas redes sociais
- [ ] Publicar no GitHub Pages

## 👩‍💻 Autora

Feito por **Priscilla Correa** · [@prissycorrea](https://github.com/prissycorrea)
