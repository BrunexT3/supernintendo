# Projeto: SNES Wishlist

## Visao Geral
Site de wishlist de jogos de Super Nintendo com cards visuais mostrando box art dos jogos. Hospedado no GitHub Pages.

## URLs
- **Repositorio:** https://github.com/BrunexT3/supernintendo.git
- **GitHub Pages:** https://brunext3.github.io/supernintendo/
- **Branch:** master

## Configuracao Git
```bash
# Remote configurado
origin  https://github.com/BrunexT3/supernintendo.git

# Credential helper (usa GitHub CLI)
git config credential.helper "!gh auth git-credential"

# Conta GitHub ativa: BrunexT3
```

## Estrutura de Arquivos
```
C:\temp\SuperNintendo\
├── index.html          # Pagina principal com todos os jogos
├── GAMES_LIST.md       # Lista de jogos em markdown
├── README.md           # Descricao do projeto
├── CLAUDE.md           # Este arquivo (contexto para o Claude)
└── images/             # Pasta com box arts dos jogos
    ├── supermarioworld.jpeg
    ├── zelda.jpg
    ├── dk1.png
    ├── dk2.webp
    ├── ... (33 imagens total)
```

## Lista Completa de Jogos (33 jogos)

| # | Citado | Nome Completo | Ano | Genero | Imagem |
|---|--------|---------------|-----|--------|--------|
| 1 | Super Mario World | Super Mario World | 1991 | platformer | supermarioworld.jpeg |
| 2 | Zelda | The Legend of Zelda: A Link to the Past | 1992 | action | zelda.jpg |
| 3 | DK 1 | Donkey Kong Country | 1994 | platformer | dk1.png |
| 4 | DK 2 | Donkey Kong Country 2: Diddy's Kong Quest | 1995 | platformer | dk2.webp |
| 5 | Mortal Kombat | Mortal Kombat | 1993 | action | mortalkombat.jpg |
| 6 | Street Fighter 2 | Street Fighter II: The World Warrior | 1992 | action | streetfighter.jpg |
| 7 | ISSS Deluxe | International Superstar Soccer Deluxe | 1995 | sports | international.jpg |
| 8 | Super Metroid | Super Metroid | 1994 | action | supermetroid.jpeg |
| 9 | Super Mario All Star | Super Mario All-Stars | 1993 | platformer | supermarioallstar.jpeg |
| 10 | Yoshi's Island | Super Mario World 2: Yoshi's Island | 1995 | platformer | yoshiisland.jpg |
| 11 | Aladdin | Disney's Aladdin | 1993 | platformer | Disney's Aladdin.jpeg |
| 12 | Rei Leao | Disney's The Lion King | 1994 | platformer | Disney's The Lion King.jpeg |
| 13 | Castlevania IV | Super Castlevania IV | 1991 | action | catlevania.jpg |
| 14 | Indiana Jones | Indiana Jones' Greatest Adventures | 1994 | action | Indiana Jones' Greatest Adventures.jpeg |
| 15 | Prince of Persia | Prince of Persia | 1992 | action | Prince of Persia.jpg |
| 16 | Super Mario RPG | Super Mario RPG: Legend of the Seven Stars | 1996 | rpg | Super Mario RP.jpeg |
| 17 | Super Mario Kart | Super Mario Kart | 1992 | racing | Super Mario Kart.jpeg |
| 18 | F-Zero | F-Zero | 1991 | racing | F-Zero.png |
| 19 | Top Gear | Top Gear | 1992 | racing | Top Gear.jpeg |
| 20 | Top Gear 2 | Top Gear 2 | 1993 | racing | Top Gear 2.png |
| 21 | Lemmings | Lemmings | 1992 | puzzle | Lemmings.jpg |
| 22 | Tartaruga Ninja | Teenage Mutant Ninja Turtles IV: Turtles in Time | 1992 | action | Teenage Mutant Ninja Turtles IV.jpeg |
| 23 | Simpsons | The Simpsons: Bart's Nightmare | 1992 | platformer | The SimpsonsBart's Nightmare.jpeg |
| 24 | Mickey | The Magical Quest Starring Mickey Mouse | 1992 | platformer | The Magical Quest Starring Mickey Mouse.png |
| 25 | Double Dragon | Super Double Dragon | 1992 | action | Super Double Dragon.jpeg |
| 26 | Battletoads | Battletoads in Battlemaniacs | 1993 | action | Battletoads in Battlemaniacs.png |
| 27 | Batman | Batman Returns | 1993 | action | Batman Returns.webp |
| 28 | Killer Instinct | Killer Instinct | 1995 | action | Killer Instinct.jpg |
| 29 | Mortal Kombat 2 | Mortal Kombat II | 1994 | action | Mortal Kombat II.jpeg |
| 30 | DK 3 | Donkey Kong Country 3: Dixie Kong's Double Trouble! | 1996 | platformer | Donkey_Kong_Country_3_capa.png |
| 31 | Demon's Crest | Demon's Crest | 1994 | action | Demonscrest_us.jpg |
| 32 | Blackthorne | Blackthorne | 1994 | action | Blackthorne.jpg |
| 33 | Star Wars 1 | Super Star Wars | 1992 | action | StarWars 1.jpg |

## Generos Disponiveis
- `platformer` - Plataforma
- `action` - Acao
- `racing` - Corrida
- `sports` - Esportes
- `rpg` - RPG
- `puzzle` - Puzzle

## Como Adicionar Novos Jogos

### 1. Adicionar imagem
Colocar a imagem do box art na pasta `images/`

### 2. Editar index.html
Adicionar entrada no array `games` (linha ~411):
```javascript
{ citado: "Nome Curto", completo: "Nome Oficial Completo", lancamento: ANO, genero: "GENERO", boxArt: "images/NOME_ARQUIVO.jpg" }
```

### 3. Commit e Push
```bash
cd "C:\temp\SuperNintendo"
git add index.html images/NOVA_IMAGEM.jpg
git commit -m "feat: add NOME_DO_JOGO"
git push origin master
```

O deploy no GitHub Pages e automatico apos o push.

## Filtros do Site
O site tem filtros por genero:
- Todos
- Plataforma (platformer)
- Acao (action)
- Corrida (racing)
- Esportes (sports)
- RPG (rpg)
- Puzzle (puzzle)

## Jogos Sugeridos para Adicionar (ainda nao na lista)
- Chrono Trigger (RPG, 1995)
- Final Fantasy VI (RPG, 1994)
- Mega Man X (action, 1993)
- Contra III: The Alien Wars (action, 1992)
- Secret of Mana (rpg, 1993)
- Earthbound (rpg, 1995)
- NBA Jam (sports, 1994)
- Super Punch-Out!! (sports, 1994)
- Star Fox (action, 1993)
- Kirby Super Star (platformer, 1996)

## Ultima Atualizacao
- **Data:** 27 de Janeiro de 2026
- **Total de jogos:** 33
- **Ultimo commit:** feat: add 3 new games (Demon's Crest, Blackthorne, Super Star Wars)
