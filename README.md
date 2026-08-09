Sobre o Projeto

O objetivo foi transformar um layout criado no Figma em uma página web completa — estruturada, estilizada e animada do zero.

Além de implementar o design proposto, foram feitas melhorias funcionais que não existiam na referência original:

O site de referência possuía botões de Trailer e Comprar Ingresso que não tinham nenhuma funcionalidade.
Decidi substituí-los por uma navegação no header com dois botões 100% funcionais:
TRAILER → abre o trailer em um modal com player completo
ELENCO → redireciona suavemente para a seção de elenco via scroll animado
- Funcionalidades
- Sequência de frames sincronizada com o scroll, simulando um vídeo interativo controlado pela rolagem da página
- Scroll suave com pin de seções usando GSAP ScrollSmoother + ScrollTrigger
- Troca de textos letra a letra com SplitText em ordem aleatória, criando efeito cinematográfico
- Máscara de revelação que abre do centro e empurra os elementos ao rolar
- Player de vídeo customizado com controles de play, pause, seek, mute e tela cheia
- Modal de trailer acessível via botão no header
- Seção de elenco com crossfade de imagens e barra de progresso com indicador animado
- Layout responsivo adaptado para diferentes tamanhos de tela

 *Tecnologias Utilizadas*
HTML	Estrutura semântica da página
CSS 	Estilização, variáveis e animações
JavaScript	Lógica de interação e animações
GSAP (ScrollTrigger, ScrollSmoother, SplitText)	Animações sincronizadas com scroll
Figma	Prototipagem e referência do layout


📁 Estrutura de Pastas
Spider-Man/
├── assets/
│   ├── frames/         # Sequência de imagens
│   ├── elenco/         # Fotos dos atores
│   └── ...             # SVGs, vídeo e demais assets
├── index.html
├── style.css
└── main.js

🚀 Como Rodar Localmente
bash
# Clone o repositório
git clone https://github.com/joseluizp/Spider-Man.git

# Acesse a pasta
cd Spider-Man

# Abra o index.html com Live Server (VS Code)
# Clique com o botão direito em index.html → Open with Live Server

⚠️ A sequência de frames é carregada via requisições locais. Use um servidor local (como o Live Server do VS Code) para evitar erros de CORS.

Aprendizados

Transformar um design do Figma em código funcional do início ao fim
Criar animações de alta qualidade com timing e sincronismo usando GSAP
Trabalhar com frames de imagens controladas pelo scroll
Tomar decisões de UX e : identificar o que estava quebrado na referência e propor soluções funcionais

 Autor:

Desenvolvido por José Luiz · Curso DevArt

# Spider-Man

## Preview

![Preview 01](./assets/Preview01.png)

![Preview 02](./assets/Preview02.png)
