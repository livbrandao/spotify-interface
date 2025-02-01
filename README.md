# Spotify Interface Clone

![Spotify Logo](src/assets/icons/logo-spotify.png)

Um clone da interface do Spotify desenvolvido com HTML, CSS e JavaScript vanilla, incluindo funcionalidades de busca de artistas em tempo real.

## 🚀 Funcionalidades

- Interface responsiva similar ao Spotify
- Sistema de busca de artistas em tempo real
- Visualização de cards de artistas
- Layout adaptativo para diferentes tamanhos de tela

## 💻 Tecnologias

- HTML5
- CSS3 (com Flexbox e Grid)
- JavaScript (ES6+)
- API REST local (JSON Server)

## 📋 Pré-requisitos

- Node.js instalado
- NPM ou Yarn
- JSON Server

## 🔧 Instalação

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/spotify-interface.git
cd spotify-interface
```

2. Instale o JSON Server globalmente:

```bash
npm install -g json-server
```

3. Inicie o servidor JSON:

```bash
json-server --watch api-artists/artists.json --port 3000
```

4. Abra o arquivo `index.html` em seu navegador ou use um servidor local como Live Server do VS Code.

## 🎯 Estrutura do Projeto

```
spotify-interface/
├── src/
│   ├── assets/
│   │   ├── icons/
│   │   └── playlist/
│   └── styles/
│       ├── reset.css
│       ├── global.css
│       ├── sidebar-footer.css
│       ├── main-content.css
│       └── media-queries.css
├── api-artists/
│   └── artists.json
├── index.html
├── script.js
└── README.md
```

## 📱 Layout Responsivo

O projeto é totalmente responsivo e se adapta aos seguintes breakpoints:

- Desktop (> 1024px)
- Tablet (768px - 1024px)
- Mobile (< 768px)

## 🔍 Funcionalidade de Busca

A busca de artistas é implementada com as seguintes características:

- Busca em tempo real
- Filtro por nome de artista
- Exibição dinâmica de resultados
- Tratamento de estados vazios

## 🤝 Contribuindo

1. Faça o fork do projeto
2. Crie sua feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## ✒️ Autores

- **Lívia Brandão** - _Desenvolvimento inicial_ - [livbrandao](https://github.com/livbrandao)

## 📄 Licença

Este projeto está sob a licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) para detalhes.

## 🎁 Agradecimentos

- Inspiração no layout original do Spotify
- Alura pela oportunidade de aprendizado na imersão front-end

## 📌 Status do Projeto

🚧 Em desenvolvimento... 🚧

---

⌨️ com ❤️ por [Lívia](https://github.com/livbrandao) 😊
