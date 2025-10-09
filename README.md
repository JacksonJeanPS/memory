-----

# Página Romântica Interativa 💖

Uma página web pessoal e interativa criada para celebrar o amor. O projeto combina um design moderno com elementos dinâmicos como player de música, carrossel de fotos, contador de relacionamento e texto com efeito de digitação, tudo sobre um fundo de vídeo responsivo.

*Dica: Grave um GIF da sua página para colocar aqui\!*

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://imgshields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
</div>

-----

## 🔥 Funcionalidades

  - **🎥 Fundo de Vídeo Responsivo**: Carrega vídeos diferentes para a versão desktop e mobile, otimizando a experiência.
  - **🎵 Player de Música Completo**:
      - Playlist com troca automática e manual de faixas.
      - Controles de play, pause, avançar e reiniciar.
      - Barra de progresso clicável com tempo atual e duração total.
  - **🖼️ Carrossel de Fotos Automático**:
      - Exibe uma sequência de imagens que avança sozinha a cada 5 segundos.
      - Permite navegação manual ao clicar nas imagens ou nos pontos de navegação.
  - **⏳ Contador de Relacionamento**:
      - Exibe em tempo real a duração do relacionamento (anos, dias, horas, minutos e segundos) a partir de uma data pré-definida.
  - **✍️ Texto Animado**:
      - Uma mensagem especial é revelada com um efeito de "máquina de escrever" (`typewriter`).
  - **✨ Design Moderno**:
      - Utiliza o efeito *glassmorphism* (`backdrop-filter`) para criar painéis translúcidos e elegantes.
      - Layout totalmente responsivo que se adapta a telas de celular.

-----

## 🛠️ Tecnologias Utilizadas

  - **HTML5**: Estrutura semântica do conteúdo.
  - **CSS3**: Estilização, animações (`@keyframes`), design responsivo (`@media`) e efeitos visuais.
  - **JavaScript (Vanilla)**: Toda a lógica interativa do player, carrossel, contador e texto animado, sem a necessidade de bibliotecas externas.

-----

## 📂 Estrutura do Projeto

Para que o projeto funcione corretamente, os arquivos devem seguir esta estrutura:

```
/memoris/
│
├── index.html          # O arquivo principal
├── back-desktop.mp4    # Vídeo para telas grandes
├── back-mobile.mp4     # Vídeo para telas pequenas
│
├── musica/
│   ├── musica1.mp3
│   └── musica2.mp3
│
└── imagens/
    ├── foto1.jpg
    ├── foto2.jpg
    └── ...
```

-----

## 🚀 Como Usar

1.  **Clone ou baixe** este repositório.
2.  **Adicione seus arquivos** nas pastas `musica/` e `imagens/`.
3.  **Atualize os nomes dos arquivos** no `index.html` e no script JavaScript (veja a seção de personalização abaixo).
4.  **Abra o arquivo `index.html`** em seu navegador.

-----

## 🎨 Como Personalizar

Você pode customizar facilmente os principais elementos no próprio código:

  - **Para mudar a data do contador:**

      - No JavaScript, altere a data na linha:
        ```javascript
        const startDate = new Date('2018-09-30T00:00:00');
        ```

  - **Para editar a playlist de músicas:**

      - No JavaScript, modifique o array `playlist` com os caminhos das suas músicas:
        ```javascript
        const playlist = [
            'musica/SuaMusica1.mp3',
            'musica/SuaMusica2.mp3'
        ];
        ```

  - **Para alterar as fotos do carrossel:**

      - No HTML, altere os caminhos das imagens nas tags `<img>`:
        ```html
        <div class="carousel-track">
            <img src="imagens/sua-foto1.jpg" alt="Foto 1">
            <img src="imagens/sua-foto2.jpg" alt="Foto 2">
            </div>
        ```

  - **Para modificar a mensagem animada:**

      - No JavaScript, edite o texto da variável `amorText`:
        ```javascript
        const amorText = "Seu novo texto de amor vai aqui...";
        ```

<div align="center">
  <hr> 
  <h4> <i>Feito com ❤️ para celebrar grandes histórias.</i> </h4>
</div>
