# Portfolio Ives Mendes

## Como Adicionar Sua Foto

Para adicionar sua foto na seção "Sobre Mim", siga estes passos:

### 1. Prepare a Foto
- Use uma foto de boa qualidade (recomendado: 600x600 pixels ou maior)
- Formato: JPG, PNG ou WebP
- A foto será exibida como um círculo, então escolha uma que funcione bem nesse formato

### 2. Adicione a Foto
- Coloque sua foto na pasta `images/`
- Renomeie para `ives-mendes.jpg` (ou atualize o HTML com o nome correto)
- Se usar outro formato, atualize a extensão no arquivo `index.html`

### 3. Localização no Código
A foto está configurada na seção "Sobre Mim" do arquivo `index.html`:

```html
<div class="about-image">
    <img src="images/ives-mendes.jpg" alt="Ives Mendes - Desenvolvedor Full Stack" class="profile-photo">
</div>
```

### 4. Estilos Aplicados
A foto terá:
- Formato circular (300x300px no desktop)
- Borda roxa com efeito hover
- Sombra elegante
- Responsiva para dispositivos móveis
- Efeito de escala no hover

### 5. Personalização
Para alterar o estilo da foto, edite o arquivo `styles.css` na seção `.profile-photo`.

## Estrutura do Projeto
```
portfolio-ivesmendes/
├── index.html          # Página principal
├── styles.css          # Estilos CSS
├── script.js           # JavaScript
├── images/             # Pasta para imagens
│   └── ives-mendes.jpg # Sua foto (adicionar aqui)
└── README.md           # Este arquivo
```

## Tecnologias Utilizadas
- HTML5
- CSS3 (com variáveis CSS e Grid/Flexbox)
- JavaScript vanilla
- Font Awesome para ícones
- Google Fonts (Inter)

## Como Executar
1. Abra o arquivo `index.html` em qualquer navegador moderno
2. Ou use um servidor local para desenvolvimento

## Personalização
- Cores: Edite as variáveis CSS no arquivo `styles.css`
- Conteúdo: Modifique o texto no arquivo `index.html`
- Estilos: Ajuste os estilos no arquivo `styles.css`
