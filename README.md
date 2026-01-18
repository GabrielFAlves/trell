# Site de Despedida Retro - Adeus G.FIRMEZA

Site nostalgico estilo anos 90/2000 para despedida do G.FIRMEZA que esta se mudando para Portugal!

## VGT (VINIGOTA) - HACKATHON WINNERS 🏆

Site oficial de despedida do grupo VGT com referencias a:
- Dead by Daylight 🔦
- Terraria ⛏️
- Club Penguin 🐧
- Girias lendarias: TRELL, BKZL, ICFV, LEGACY, TUFF, COOKED
- O lendario "sorubao na escada de emergencia da IBMEC" 😂

## Como usar

1. Abra o arquivo `index.html` no navegador
2. Personalize o conteudo (veja abaixo)
3. Compartilhe com seus amigos!

## Personalizacao

**NOTA:** O site ja esta personalizado para o G.FIRMEZA e o grupo VGT! 🎮

### 1. Nome e referencias ja personalizados
O site ja contem:
- Nome: G.FIRMEZA
- Grupo: VGT (VINIGOTA)
- Jogos: Dead by Daylight, Terraria, Club Penguin
- Girias: TRELL, BKZL, ICFV, LEGACY, TUFF, COOKED
- Memes: Sorubao na escada da IBMEC
- Data: 22/01/2025

### 2. Adicionar GIFs animados retro
O site esta preparado para usar GIFs classicos da era Web 1.0!

**Pasta gifs/**: Ja existe uma pasta `gifs/` com instruções completas no arquivo `COMO-ADICIONAR-GIFS.txt`

**GIFs recomendados** (baixe de https://gifcities.org/ ou https://cyber.dabamos.de/88x31/):
- `fire.gif` - Fogo animado
- `construction.gif` - Under Construction classico
- `new.gif`, `cool.gif` - Badges 88x31
- `web.gif`, `geocities.gif` - Badges retro

**IMPORTANTE**: Mesmo sem os GIFs, o site funciona perfeitamente! Todas as animacoes CSS (estrelas girando, fogo pulsando, badges piscando) continuam funcionando. Os GIFs sao um extra opcional.

### 3. Adicionar fotos REAIS do grupo
Atualmente as fotos sao placeholders tematicos. Para adicionar fotos reais:

```html
<!-- Procure pelas imagens placeholder no HTML, exemplo: -->
<img src="https://via.placeholder.com/300x200/8B0000/FFFFFF?text=Dead+by+Daylight" alt="DBD Nights">

<!-- Substitua por suas fotos reais: -->
<img src="fotos/dbd-night.jpg" alt="DBD Nights">
```

Sugestoes de fotos:
- Screenshots de partidas de Dead by Daylight, Terraria ou Club Penguin
- Fotos do hackathon que o VGT venceu
- Fotos da galera na IBMEC
- Prints das conversas com as girias TRELL, BKZL, etc

### 3. Adicionar mais mensagens no livro de visitas
Adicione mais entradas antes do formulario:

```html
<div class="guestbook-entry">
    <div class="guestbook-author">Seu Nome</div>
    <div class="guestbook-date">Data</div>
    <p>Sua mensagem aqui!</p>
</div>
```

### 4. Adicionar mais perguntas ao Quiz
O quiz ja tem 4 perguntas sobre VGT, jogos e girias. Para adicionar mais:

```html
<h3 style="color: #0000FF; margin: 30px 0 20px 0;">Pergunta 5: Sua pergunta aqui?</h3>
<div class="quiz-option" onclick="answerQuiz(this, false)">❌ Resposta errada</div>
<div class="quiz-option" onclick="answerQuiz(this, true)">✅ Resposta correta!</div>
```

### 5. Personalizar ainda mais o Top 10
O Top 10 ja esta com momentos do VGT, mas voce pode editar:

```html
<div class="top10-text">Seu momento personalizado aqui! 🎮</div>
```

## Referencias VGT Incluidas no Site

### Jogos do Grupo:
- **Dead by Daylight** 🔦👻 - Mencionado no Top 10, Quiz e MSN Chat
- **Terraria** ⛏️🌙 - Referencias a madrugadas construindo
- **Club Penguin** 🐧❄️ - Nostalgia da infancia

### Girias Lendarias:
- **TRELL** - Espalhado pelo site todo
- **BKZL** - No marquee e mensagens
- **ICFV** - Livro de visitas e pop-ups
- **LEGACY** - MSN e pop-ups
- **TUFF** - Quiz e mensagens
- **COOKED** - Referencias ao codigo

### Momentos Memoraveis:
- **VGT (VINIGOTA)** - Nome do grupo, aparece em todo o site
- **Hackathon Winners** - Destaque no header e Top 10
- **Sorubao na escada de emergencia da IBMEC** - Top 10 #1 e livro de visitas
- **G.FIRMEZA** - Nome do amigo que vai embora

### Easter Eggs Especiais:
- Pop-ups aleatorios com referencias ao VGT
- MSN Chat com respostas personalizadas usando as girias
- Loading screen com mensagens sobre DBD, Terraria e Club Penguin
- Galeria com placeholders tematicos dos jogos

## Funcionalidades incluidas

### Interatividade Total:
- **Tela de loading** estilo Windows 98 ao carregar o site
- **Contador de visitas animado** (fake, so visual)
- **Contador regressivo** ate 22/01/2025 (ja configurado!)
- **Cursor customizado** com rastro de estrelas
- **Confete caindo** em momentos especiais
- **Pop-ups aleatorios** de zoeira (estilo anos 90)
- **Chat MSN Messenger fake** com bot que responde mensagens
- **Quiz interativo** sobre o amigo (personalizavel)
- **Top 10 momentos** com ranking visual
- **Galeria de fotos** com efeitos hover
- **Jogo da memoria** interativo com tema de Portugal
- **Livro de visitas** funcional (as mensagens ficam so enquanto a pagina estiver aberta)
- **Player de musica** simulado (MIDI fake)
- **Sons nos botoes** (beeps retro ao clicar)
- **Animacoes retro**: avioes voando, bandeiras balancando, textos piscando
- **Easter egg**: Digite o Konami Code (setas: ↑↑↓↓←→←→BA)

## Elementos retro classicos

- Comic Sans MS (a fonte favorita dos anos 90)
- Cores vibrantes e contrastantes
- Bordas 3D (ridge, outset, inset)
- Texto animado tipo marquee
- Badge "Best Viewed in IE 6.0"
- WebRing (fake)
- Secao "Under Construction"
- Contador de visitas estilo antigo

## Hospedagem gratuita

Voce pode hospedar este site gratuitamente em:
- **GitHub Pages**: https://pages.github.com/
- **Netlify**: https://www.netlify.com/
- **Vercel**: https://vercel.com/

Basta fazer upload do arquivo `index.html` e suas fotos!

## Dicas e Recursos Especiais

### Funcionalidades Automaticas:
- **Tela de Loading**: Aparece automaticamente ao carregar a pagina
- **Confete**: Cai quando o site carrega, ao completar o jogo da memoria e ao assinar o livro
- **Pop-ups de Zoeira**: Aparecem aleatoriamente a cada 20-30 segundos (pode fechar clicando no X)
- **Chat MSN**: Aparece 2 segundos apos o loading - converse com o Saudade Bot!
- **Sons**: Todos os botoes fazem "beep" ao clicar (tipo Windows 98)

### Observacoes Tecnicas:
- O site funciona 100% offline, nao precisa de servidor
- Todas as funcionalidades sao em JavaScript puro (vanilla)
- As mensagens do livro de visitas nao sao salvas (voce pode adicionar localStorage se quiser)
- Para adicionar musica de verdade, inclua um arquivo de audio e use a tag `<audio>`
- O contador regressivo esta configurado para **22/01/2025 as 10:00**

### Easter Eggs:
1. **Konami Code**: Digite ↑↑↓↓←→←→BA para ativar modo rainbow
2. **Cursor com estrelas**: Move o mouse para ver o rastro magico
3. **Minimizar MSN**: Clique no "_" no chat MSN para minimizar

Divirta-se e boa sorte para seu amigo em Portugal!
