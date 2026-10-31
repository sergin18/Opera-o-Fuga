# OPERAÇÃO: FUGA DO BRASIL

Jogo de plataforma 2D em pixel art procedural, feito com HTML5 Canvas, CSS e JavaScript puro. Não precisa de instalação, servidor ou bibliotecas externas.

## Jogar
Abra `index.html` no navegador ou publique a pasta no GitHub Pages/Vercel.

## Controles
- Andar: A/D ou setas ←/→
- Pular: Espaço, W ou ↑
- Arremessar papelada: X
- Agachar: S ou seta para baixo
- Pausar: P ou Esc
- Celular/tablet: controles de toque na tela

## Campanha
Cinco fases com cenários, colecionáveis, inimigos e um chefão em cada etapa. Derrote o chefão arremessando papelada (X) e avance até a saída. Pule sobre inimigos comuns para eliminá-los. Colete documentos para aumentar sua pontuação.

## Estrutura
- `index.html`: telas e interface
- `css/style.css`: identidade visual e responsividade
- `js/data.js`: dados das cinco fases
- `js/input.js`: teclado e toque
- `js/audio.js`: efeitos sonoros sintetizados
- `js/engine.js`: física, colisões, inimigos, chefões, câmera e renderização
- `js/main.js`: inicialização e navegação

## Observações
O protagonista agora usa sprites recortados da ficha de personagem fornecida pelo usuário (idle, corrida, salto, ataque, agachamento e dano). Cenários e inimigos continuam renderizados em Canvas. O protagonista e as situações são caricaturas fictícias para fins de sátira. O protótipo é local e salva o recorde no navegador.
