# Projeto: Super Nintendo - Colecao e Manutencao

## Visao Geral
Projeto pessoal para gerenciar colecao de jogos de Super Nintendo, incluindo:
- **Wishlist visual** de jogos (site hospedado no GitHub Pages)
- **Guia de upscalers** para conexao com TVs 4K modernas
- **Guia de manutencao** preventiva do console e cartuchos

## URLs
- **Repositorio:** https://github.com/BrunexT3/supernintendo.git
- **GitHub Pages:** https://brunext3.github.io/supernintendo/
- **Branch:** master

---

## Estrutura de Arquivos

```
C:\temp\SuperNintendo\
├── index.html            # Site wishlist (33 jogos)
├── GAMES_LIST.md         # Lista de jogos em markdown
├── UPSCALER-GUIDE.md     # Guia de conexao com TVs 4K
├── MAINTENANCE-GUIDE.md  # Guia de manutencao preventiva
├── README.md             # Descricao do projeto
├── CLAUDE.md             # Este arquivo (contexto)
└── images/               # Box arts dos jogos (33 imagens)
```

---

## Meu Equipamento

### Console SNES
| Info | Valor |
|------|-------|
| **Modelo** | SNS-001 (SNES original americano) |
| **Serial** | UN259795931 |
| **FCC ID** | BMCSNSCD |
| **Revisao** | Provavelmente **2-CHIP** (prefixo UN2) |
| **Confirmado?** | Nao - precisa abrir para verificar placa |
| **Estado** | Funciona (testado em TV de tubo na loja) |
| **Amarelamento** | Leve, perto dos conectores de controle |

> **Nota:** Consoles UN2 sao geralmente 2-CHIP (imagem um pouco mais borrada que 1CHIP). A diferenca e sutil e um bom upscaler compensa bem.

### TV
| Info | Valor |
|------|-------|
| **Modelo** | Samsung QN43QN90CAG |
| **Tipo** | Neo QLED 4K (premium) |
| **Entrada AV/RCA** | **NAO TEM** (somente HDMI) |
| **Problema** | Precisa de conversor/upscaler obrigatoriamente |

### Produtos de Limpeza
| Item | Tenho? | Marca |
|------|--------|-------|
| Limpa contato eletrico | ✅ Sim | Wurth (sem oleo - OK para uso) |
| Alcool isopropilico 90%+ | [ ] Nao | - |
| Creme oxidante 40 vol | [ ] Nao | Para Retr0bright |

---

## Historico de Compras - Video

### RetroScaler 2X (COMPRADO)
| Info | Valor |
|------|-------|
| **Produto** | RetroScaler 2X Conversor AV/Component/S-Video para HDMI |
| **Preco** | R$ 478 |
| **Status** | ✅ Comprado - Aguardando entrega |
| **Entradas** | AV, S-Video, Component (YPbPr) |
| **Link** | mercadolivre.com.br/MLBU781846565 |

### Cabo S-Video (COMPRADO)
| Info | Valor |
|------|-------|
| **Produto** | Cabo S-Video + Audio para SNES |
| **Preco** | ~R$ 40 |
| **Status** | ✅ Comprado - Aguardando entrega |

### Conversor Generico (BACKUP)
| Info | Valor |
|------|-------|
| **Produto** | Cabo Conversor HDMI 1080p para N64/SNES/GameCube |
| **Preco** | R$ 135 |
| **Status** | Funcionando - Manter como backup |
| **Link** | mercadolivre.com.br/MLB34019460 |

### Adaptador HDMI→RCA (COMPRA ERRADA)
| Info | Valor |
|------|-------|
| **Produto** | Adaptador HDMI para AV/RCA |
| **Preco** | ~R$ 50 |
| **Status** | ❌ Faz o CONTRARIO do necessario |
| **Acao** | **DEVOLVER** |

---

## Setup de Video

### Equipamentos Comprados

| Item | Produto | Preco | Status |
|------|---------|-------|--------|
| **Upscaler** | RetroScaler 2X | R$ 478 | ✅ Comprado |
| **Cabo** | S-Video + Audio | ~R$ 40 | ✅ Comprado |
| Conversor antigo | Generico HDMI | R$ 135 | Substituido |

### Configuracao Planejada
```
SNES → Cabo S-Video → RetroScaler 2X → HDMI → TV Samsung QN90C
```

### Qualidade Esperada
| Aspecto | Antes (conversor generico) | Depois (RetroScaler + S-Video) |
|---------|---------------------------|--------------------------------|
| Processamento | Nenhum | Line doubling |
| Sinal | Composite | S-Video |
| Pixels | Borrados | Definidos |
| Qualidade | ⭐⭐ | ⭐⭐⭐⭐ |

### Configuracao TV Samsung QN90C
1. `Configuracoes > Imagem > Tamanho da Imagem` → **4:3**
2. `Configuracoes > Geral > Modo Game` → **Ativado** (reduz lag)

**Detalhes completos:** Ver UPSCALER-GUIDE.md

---

## Ferramentas de Manutencao

| Item | Tenho? | Prioridade |
|------|--------|------------|
| Chave Gamebit 3.8mm (cartuchos) | [ ] | Alta |
| Chave Gamebit 4.5mm (console) | [ ] | Alta |
| Alcool isopropilico 90%+ | [ ] | Media |
| Ferro de solda 30W | [ ] | Baixa |
| Baterias CR2032 com terminais | [ ] | Baixa |
| Creme oxidante 40 vol | [ ] | Media |

---

## Proximas Acoes

### Video (Aguardando Entrega)
- [ ] Aguardar chegada do RetroScaler 2X
- [ ] Aguardar chegada do cabo S-Video
- [ ] Configurar RetroScaler 2X + S-Video
- [ ] Ajustar proporcao da TV para 4:3
- [ ] Devolver adaptador HDMI→RCA errado
- [ ] (Opcional futuro) Testar cabo Component para comparar com S-Video

### Manutencao (Prioridade Media)
- [ ] Comprar kit chaves gamebit (3.8mm + 4.5mm)
- [ ] Abrir console para confirmar revisao (2-CHIP ou 1CHIP)
- [ ] Limpar slot de cartuchos
- [ ] Clarear area amarelada com Retr0bright

### Jogos (Prioridade Baixa)
- [ ] Testar saves dos jogos RPG (Zelda, Mario RPG)
- [ ] Verificar se baterias dos cartuchos ainda funcionam

---

## Lista de Jogos (33 total)

### Por Genero

**Plataforma (10)**
- Super Mario World, DK 1/2/3, Super Mario All-Stars
- Yoshi's Island, Aladdin, Rei Leao, Simpsons, Mickey

**Acao (15)**
- Zelda, Mortal Kombat 1/2, Street Fighter II, Super Metroid
- Castlevania IV, Indiana Jones, Prince of Persia, TMNT IV
- Double Dragon, Battletoads, Batman Returns, Killer Instinct
- Demon's Crest, Blackthorne, Super Star Wars

**Corrida (4)**
- Super Mario Kart, F-Zero, Top Gear 1/2

**Esportes (1)**
- International Superstar Soccer Deluxe

**RPG (1)**
- Super Mario RPG

**Puzzle (1)**
- Lemmings

### Jogos Sugeridos para Adicionar
- Chrono Trigger (RPG)
- Final Fantasy VI (RPG)
- Mega Man X (action)
- Contra III (action)
- Secret of Mana (RPG)
- Earthbound (RPG)

---

## Configuracao Git

```bash
# Remote
origin  https://github.com/BrunexT3/supernintendo.git

# Credential helper
git config credential.helper "!gh auth git-credential"

# Conta GitHub: BrunexT3
```

### Como Adicionar Novos Jogos

1. Adicionar imagem em `images/`
2. Editar `index.html` (array `games` linha ~411)
3. Commit e push:
```bash
cd "C:\temp\SuperNintendo"
git add index.html images/NOVA_IMAGEM.jpg
git commit -m "feat: add NOME_DO_JOGO"
git push origin master
```

---

## Guias Disponiveis

### UPSCALER-GUIDE.md
- Minha situacao atual (TV, produtos comprados)
- Historico de compras e testes
- Comparativo de opcoes (SCART combo, RetroScaler, OSSC, RetroTINK)
- Troubleshooting para TV Samsung QN90C
- Onde comprar (Brasil e internacional)

### MAINTENANCE-GUIDE.md
- Limpeza do console e cartuchos
- Produtos recomendados (limpa contato Wurth OK)
- Troca de bateria CR2032
- Identificacao 1CHIP vs 2-CHIP
- Clareamento Retr0bright
- Armazenamento correto
- Diagnostico de problemas

---

## Ultima Atualizacao

- **Data:** 29 de Janeiro de 2026
- **Total de jogos:** 33
- **Status video:** ✅ RetroScaler 2X + Cabo S-Video comprados (aguardando entrega)
- **Investimento total video:** R$ 478 + R$ 40 = **R$ 518**
- **Jogo testado:** Mortal Kombat
- **Proxima acao:** Configurar setup quando chegar
