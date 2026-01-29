# Guia: Conectar Super Nintendo em TVs 4K Modernas

## Minha Situacao Atual

### TV
| Info | Valor |
|------|-------|
| **Modelo** | Samsung QN43QN90CAG |
| **Tipo** | Neo QLED 4K |
| **Entrada AV/RCA** | NAO tem (somente HDMI) |
| **HDMI testada** | HDMI 2 |

### Problema
A TV Samsung QN90C e uma TV premium que **nao tem entrada AV/RCA**, entao e obrigatorio usar um conversor/upscaler para conectar o SNES.

---

## Historico de Compras e Testes

### Conversor Generico SNES→HDMI (EM USO)
| Info | Valor |
|------|-------|
| **Produto** | Cabo Conversor HDMI 1080p para N64/SNES/GameCube |
| **Preco** | R$ 135 |
| **Status** | ✅ Funcionando |
| **Jogo testado** | Mortal Kombat |

**Link:** mercadolivre.com.br/MLB34019460

### Limitacoes do Conversor Generico
| Problema | Solucao |
|----------|---------|
| Imagem esticada 16:9 | Ajustar TV para proporcao 4:3 |
| Qualidade borrada | Normal para conversor generico (upgrade = upscaler) |
| Pixels nao definidos | Upscaler (RetroTINK/OSSC) melhora muito |

### Adaptador HDMI→RCA (COMPRA ERRADA)
| Info | Valor |
|------|-------|
| **Produto** | Adaptador HDMI para AV/RCA |
| **Preco** | R$ ~50 |
| **Status** | ❌ Produto errado - faz o CONTRARIO do necessario |
| **O que faz** | Converte HDMI → RCA (para TV de tubo) |
| **O que eu precisava** | RCA → HDMI (para TV 4K) |

**Acao:** Devolver este produto

---

## Opcoes Analisadas

### Hierarquia de Qualidade de Video

```
RGB SCART > S-Video > Composite (RCA amarelo)
    ⬆️           ⬆️            ⬆️
  Melhor    Intermediario    Basico
```

### Conversor vs Upscaler - Diferenca Importante

| Tipo | O que faz | Qualidade | Lag | Preco |
|------|-----------|-----------|-----|-------|
| **Conversor generico** | So converte sinal | Baixa | Alto (30-100ms) | R$ 50-150 |
| **Upscaler (OSSC, RetroTINK)** | Converte + melhora imagem | Alta | Zero | R$ 400+ |

---

## Opcao A: Combo SCART (RGB)

### Componentes

| Item | Preco | Link |
|------|-------|------|
| Cabo SCART RGB para SNES | R$ 89 | MLB-1890943224 |
| Conversor SCART→HDMI | R$ 129 | MLB2018131838 |
| **Total** | **R$ 218** | |

### Cabo SCART RGB (VALIM)
| Info | Valor |
|------|-------|
| **Compatibilidade** | SNES, N64, GameCube |
| **Tipo sinal** | RGB (melhor qualidade) |
| **Avaliacoes** | 4,7/5 (30 avaliacoes, +100 vendidos) |
| **Vendedor** | VALIM (MercadoLider) |

### Conversor SCART→HDMI (Generico)
| Info | Valor |
|------|-------|
| **Entrada** | SCART |
| **Saida** | HDMI |
| **Tipo** | Conversor generico chines |
| **Risco** | Pode ter mesma incompatibilidade do anterior |

**Pros:**
- ✅ Sinal RGB (melhor qualidade de imagem)
- ✅ Preco mais baixo total
- ✅ Cabo com boas avaliacoes

**Contras:**
- ⚠️ Conversor generico (mesmo risco do anterior)
- ⚠️ Dois produtos = mais pontos de falha

---

## Opcao B: RetroScaler 2X

| Info | Valor |
|------|-------|
| **Produto** | RetroScaler 2X Conversor AV/Component/S-Video para HDMI |
| **Preco** | R$ 478 |
| **Entradas** | AV (RCA), S-Video, Component |
| **Saida** | HDMI |
| **Tipo** | Clone do RetroTINK 2X |
| **Vendedor** | pascolishop (MercadoLider Silver) |

**Link:** mercadolivre.com.br/MLBU781846565

**Pros:**
- ✅ Baseado no RetroTINK (mais confiavel)
- ✅ Funciona com cabo RCA que ja tenho
- ✅ Multiplas entradas (posso melhorar depois com S-Video)
- ✅ Um unico equipamento

**Contras:**
- ⚠️ Preco mais alto
- ⚠️ Sinal Composite (RCA) e inferior a RGB

---

## Opcao C: OSSC (Open Source Scan Converter)

### OSSC V1.8 (Classico)
| Info | Valor |
|------|-------|
| **Preco** | EUR 115-148 (~R$ 650-850) |
| **Entradas** | SCART, Component, VGA |
| **Saida** | HDMI/DVI ate 1440p |
| **Latencia** | Zero lag |
| **Onde comprar** | videogameperfection.com (Irlanda) |

### OSSC Pro
| Info | Valor |
|------|-------|
| **Preco** | EUR 292-348 (~R$ 1.650-2.000) |
| **Saida** | Ate 4K |
| **Onde comprar** | videogameperfection.com |

**Pros:**
- ✅ Projeto open source, comunidade ativa
- ✅ Entrada SCART nativa
- ✅ Zero lag
- ✅ Melhor custo-beneficio para SCART

**Contras:**
- ⚠️ Importacao (frete + impostos ~60-80%)
- ⚠️ Pode ter problemas de compatibilidade com algumas TVs
- ⚠️ Configuracao mais complexa

**Combo OSSC + Cabo SCART:**
| Item | Preco |
|------|-------|
| OSSC V1.8 | ~R$ 750 |
| Cabo SCART RGB | R$ 89 |
| Impostos (~60%) | ~R$ 450 |
| **Total estimado** | **~R$ 1.300** |

---

## Opcao D: RetroTINK (Linha Completa)

### RetroTINK 2X Pro
| Info | Valor |
|------|-------|
| **Preco** | US$ 80-130 (~R$ 400-650) |
| **Entradas** | Composite, S-Video, Component |
| **Saida** | 480p HDMI |
| **SCART** | NAO tem (precisa adaptador) |

### RetroTINK 5X Pro
| Info | Valor |
|------|-------|
| **Preco** | US$ 300-350 (~R$ 1.500-1.750) |
| **Entradas** | Composite, S-Video, Component, **SCART** |
| **Saida** | Ate 1440p |
| **Destaques** | Scanlines CRT, motion-adaptive deinterlacing |

### RetroTINK 4K
| Info | Valor |
|------|-------|
| **Preco** | US$ 500-750 (~R$ 2.500-3.750) |
| **Saida** | 4K nativo |
| **Destaques** | Melhor qualidade possivel |

**Onde comprar:** retrotink.com (USA) + impostos de importacao

---

## Opcao E: RAD2X

| Info | Valor |
|------|-------|
| **Preco** | US$ 70-100 (~R$ 350-500) |
| **Tipo** | Cabo HDMI direto para o console |
| **Saida** | 480p |
| **SCART** | NAO existe versao SCART |

**Pros:**
- ✅ Solucao mais simples
- ✅ Zero lag
- ✅ Baseado em RetroTINK

**Contras:**
- ⚠️ Um cabo por console
- ⚠️ Importacao necessaria

---

## Comparativo Final

| Opcao | Preco Total | Qualidade Video | Confiabilidade | Risco |
|-------|-------------|-----------------|----------------|-------|
| **A) SCART combo** | R$ 218 | ⭐⭐⭐⭐⭐ RGB | ⭐⭐⭐ Media | Conversor generico |
| **B) RetroScaler 2X** | R$ 478 | ⭐⭐⭐ Composite | ⭐⭐⭐⭐ Boa | Baixo |
| **C) OSSC V1.8** | ~R$ 1.300 | ⭐⭐⭐⭐⭐ RGB | ⭐⭐⭐⭐⭐ Alta | Importacao |
| **D) RetroTINK 5X** | ~R$ 2.000+ | ⭐⭐⭐⭐⭐ RGB | ⭐⭐⭐⭐⭐ Alta | Importacao |
| **E) RAD2X** | ~R$ 500 | ⭐⭐⭐⭐ | ⭐⭐⭐⭐ Boa | Importacao |

---

## Recomendacao por Perfil

| Perfil | Opcao | Investimento |
|--------|-------|--------------|
| **Economico (arriscar)** | Combo SCART | R$ 218 |
| **Custo-beneficio Brasil** | RetroScaler 2X | R$ 478 |
| **Melhor qualidade** | OSSC V1.8 + SCART | ~R$ 1.300 |
| **Premium** | RetroTINK 5X Pro | ~R$ 2.000+ |

---

## Troubleshooting - Conversor Nao Funciona

### Checklist Basico
| # | Verificacao |
|---|-------------|
| 1 | Conversor tem cabo USB de alimentacao? Esta conectado? |
| 2 | Testou em TODAS as portas HDMI? (1, 2, 3, 4) |
| 3 | TV esta na entrada HDMI correta? |
| 4 | Liga o SNES DEPOIS de conectar tudo? |
| 5 | LED do conversor acende? |

### Configuracoes Samsung QN90C
1. `Configuracoes > Geral > Gerenciador de Dispositivos Externos`
2. Procure **HDMI UHD Color** → Desative para a porta em uso
3. `Configuracoes > Geral > Modo Game` → Desative temporariamente
4. Teste outra porta HDMI (HDMI 4 as vezes e mais compativel)

---

## Tipos de Cabos para SNES

### Hierarquia de Qualidade

| Posicao | Tipo | Qualidade | Preco BR |
|---------|------|-----------|----------|
| 1o | **RGB SCART** | Excelente | R$ 89 |
| 2o | **Component (YPbPr)** | Excelente | R$ 150-250 |
| 3o | **S-Video** | Muito Boa | R$ 75-125 |
| 4o | **Composite (RCA)** | Basica | Incluso no SNES |

### Cabo SCART RGB Recomendado (Brasil)
- **Vendedor:** VALIM (Mercado Livre)
- **Preco:** R$ 89
- **Avaliacoes:** 4,7/5 (+100 vendidos)
- **Compatibilidade:** SNES, N64, GameCube

---

## Onde Comprar

### Brasil (Mercado Livre)
| Produto | Vendedor | Preco |
|---------|----------|-------|
| RetroScaler 2X | pascolishop | R$ 478 |
| Cabo SCART RGB | VALIM | R$ 89 |
| Conversores genericos | Varios | R$ 50-150 |

### Internacional
| Loja | Produtos | Envio BR |
|------|----------|----------|
| videogameperfection.com | OSSC | Sim (DHL) |
| retrotink.com | RetroTINK | Sim |
| AliExpress | Clones OSSC | Sim (30-60 dias) |

### Custos de Importacao
- Imposto: ~60% sobre (produto + frete)
- ICMS: 17-25% dependendo do estado
- **Total estimado:** Produto + 80-100%

---

## Dicas Importantes

### SNES 1CHIP vs 2-CHIP
- **1CHIP (UN3):** Melhor qualidade de video nativo
- **2-CHIP (UN1, UN2):** Imagem um pouco mais borrada
- Diferenca e sutil, upscaler compensa bem

### Configuracoes da TV
- Sempre ative **Game Mode** para reduzir input lag
- Desabilite motion smoothing e processamento de imagem

### O que Evitar
- Conversores genericos abaixo de R$ 100 (alta taxa de falha)
- Soprar nos cartuchos (umidade oxida contatos)
- Adaptadores que fazem o contrario (HDMI→RCA)

### RGB Nativo
O SNES original (SNS-001) ja tem RGB nativo - so precisa do cabo certo!

---

## Status Atual - COMPRADO

### Setup Adquirido
| Item | Produto | Preco | Status |
|------|---------|-------|--------|
| **Upscaler** | RetroScaler 2X | R$ 478 | ✅ Comprado |
| **Cabo** | S-Video + Audio | ~R$ 40 | ✅ Comprado |
| **Total** | - | **R$ 518** | Aguardando entrega |

### Configuracao Final
```
SNES → Cabo S-Video → RetroScaler 2X (entrada S-Video) → HDMI → TV Samsung QN90C
```

### Qualidade Esperada
| Aspecto | Conversor Generico | RetroScaler 2X + S-Video |
|---------|-------------------|--------------------------|
| Sinal entrada | Composite | **S-Video** |
| Processamento | Nenhum | **Line doubling** |
| Pixels | Borrados | **Definidos** |
| Qualidade | ⭐⭐ | **⭐⭐⭐⭐** |

### Equipamento Anterior (Backup)
| Item | Status |
|------|--------|
| Conversor generico HDMI | Manter como backup |
| Adaptador HDMI→RCA | Devolver (compra errada) |

### Upgrade Futuro (Opcional)
Se quiser melhorar ainda mais:

| Opcao | Melhoria | Preco adicional |
|-------|----------|-----------------|
| Cabo Component | S-Video → Component | ~R$ 50 |
| OSSC + SCART | Setup completo RGB | ~R$ 1.300 |

---

**Fontes:** RetroRGB.com, VideoGamePerfection, Mercado Livre

**Ultima atualizacao:** 29 de Janeiro de 2026
**Status:** ✅ RetroScaler 2X + Cabo S-Video comprados
