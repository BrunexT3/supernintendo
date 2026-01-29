# Guia de Manutencao Preventiva - Super Nintendo

## Checklist Rapido

| Frequencia | Tarefa |
|------------|--------|
| 6 meses | Limpar exterior do console (pano umido) |
| 6 meses | Verificar cabos e conexoes |
| 1 ano | Limpar slot de cartuchos |
| 1 ano | Limpar contatos de jogos mais usados |
| 5 anos | Testar saves de jogos com bateria |
| Quando necessario | Clarear plastico amarelado (Retr0bright) |
| 25+ anos | Considerar recap de capacitores |

---

## 1. Limpeza do Console

### Exterior
**Materiais:** Pano de microfibra, cotonetes, alcool isopropilico 90%+

**Procedimento:**
1. Desligue e desconecte o console
2. Use pano levemente umedecido com agua para poeira superficial
3. Para sujeira persistente, use agua com detergente neutro
4. Seque completamente antes de reconectar

### Slot de Cartuchos
**Ferramentas:** Chave gamebit 4.5mm

**Procedimento:**
1. Abra o console (6 parafusos na base)
2. Limpe pinos com cotonete + alcool isopropilico 90%+
3. Passe na direcao dos pinos, nunca contra
4. Seque 5-10 minutos antes de fechar

**Frequencia:** A cada 6-12 meses ou quando jogos apresentarem falha de leitura

---

## 2. Limpeza de Cartuchos

### Produtos Recomendados

| Produto | Uso |
|---------|-----|
| Alcool Isopropilico 90%+ | Limpeza padrao |
| Alcool Isopropilico 99% | Ideal |
| Borracha escolar branca | Oxidacao leve |
| Limpa-contatos eletronico | Casos graves |

### O que NUNCA usar
- Alcool 70% (muita agua, causa oxidacao)
- Soprar nos cartuchos (umidade da respiracao oxida)
- Produtos abrasivos
- Agua
- WD-40 ou oleos

### Tecnica Correta
1. Umedeca cotonete com alcool isopropilico 90%+
2. Passe suavemente nos contatos dourados
3. Alterne para lado seco do cotonete
4. Repita ate cotonete sair limpo
5. Aguarde 2-3 minutos para secar

### Limpeza Profunda
**Ferramenta:** Chave gamebit 3.8mm

Remova os 2 parafusos, separe as metades, limpe com mais acesso.

---

## 3. Troca de Bateria CR2032

### Jogos que Precisam de Bateria

| Categoria | Exemplos |
|-----------|----------|
| RPGs | Chrono Trigger, Final Fantasy, Secret of Mana, Earthbound, Super Mario RPG |
| Acao/RPG | Zelda: A Link to the Past, Soul Blazer, Illusion of Gaia |
| Simulacao | SimCity, Harvest Moon |

### Sinais de Bateria Fraca
- Saves desaparecem ao desligar
- "Save data corrupted"
- Jogo nao consegue salvar

### Durabilidade
- **Vida util:** 15-25 anos
- Cartuchos de 1990-1996 ja estao com baterias vencidas

### Ferramentas Necessarias
1. Chave gamebit 3.8mm
2. Ferro de solda (20-40W)
3. Solda de estanho fina
4. Sugador de solda ou malha dessoldadora
5. Bateria CR2032 com terminais soldaveis
6. Fita adesiva (metodo sem solda)

### Procedimento com Solda (Recomendado)
1. Abra o cartucho com chave 3.8mm
2. Identifique a bateria soldada na placa
3. Aqueca pontos de solda e remova bateria antiga
4. Limpe pontos com sugador ou malha
5. Solde nova bateria CR2032 com terminais
6. **Polaridade: + para cima (lado visivel)**
7. Feche e teste

### Metodo Sem Solda (Alternativo)
- Use suporte de bateria com terminais de pressao
- Ou fixe com fita isolante mantendo contato
- Menos confiavel

---

## 4. Mods e Melhorias Populares

### Modelos do SNES e Qualidade

| Modelo | Qualidade Video | Identificacao Serial |
|--------|-----------------|----------------------|
| 2-Chip (original) | Baixa (borrada) | UN1, UN2 |
| **1CHIP-01/02/03** | **Alta** | UN3 (geralmente) |
| SNES Mini/Jr (SNS-101) | Alta (com mod) | Modelo compacto |

### Como Confirmar se e 1CHIP (abrindo o console)
1. Remova os 6 parafusos da base com chave gamebit 4.5mm
2. Procure na placa-mae, proximo ao slot de cartuchos
3. **1CHIP**: Tera escrito "1CHIP-01", "1CHIP-02" ou "1CHIP-03" na placa
4. **2-CHIP**: Tera "SHVC-CPU-01" ou similar, com varios chips separados

> **Dica visual:** 1CHIP tem menos chips na placa (mais integrado). 2-CHIP tem mais chips espalhados.

### Mods de Video

**RGB Bypass**
- Melhora drasticamente a imagem
- Para uso com CRT ou upscaler
- Dificuldade: Media/Alta

**Correcao Linha Vertical**
- Problema: Linha branca descendo no centro
- Solucoes:
  1. Trocar regulador 7805 por ST L78S05CV-DG
  2. Adicionar capacitor 470uF/16V no regulador
  3. Adicionar capacitores 220uF no chip S-RGB

### Recap de Capacitores

Capacitores degradam em 20-30 anos. Console5 Wiki tem listas por revisao.

**Quando fazer:**
- Audio com ruidos/distorcao
- Video intermitente
- Console 25+ anos

### Outros Mods

| Mod | Descricao |
|-----|-----------|
| S-Video (SNES Mini) | Restaura saida removida |
| Audio Digital (SPDIF) | Saida optica |
| Controle Wireless | Receptor 8BitDo para Bluetooth |

---

## 5. Clareamento e Prevencao de Amarelamento

O amarelamento do plastico e causado pelo **retardante de chamas (brometo)** no ABS reagindo com luz UV e oxigenio. E um problema classico do SNES.

### Metodo Retr0bright (Clarear Plastico Amarelado)

**Ingrediente principal:** Peroxido de hidrogenio (agua oxigenada)

| Opcao | Produto | Onde Encontrar | Preco |
|-------|---------|----------------|-------|
| **Recomendado** | Creme oxidante 40 volumes | Farmacia | R$ 15-25 |
| Alternativa | Agua oxigenada 40 vol liquida | Farmacia | R$ 10-15 |

**Procedimento:**
1. Desmonte a carcaca (**remova a placa eletronica!**)
2. Lave bem com agua e detergente neutro
3. Aplique o creme oxidante 40 vol em camada uniforme
4. Cubra com filme plastico (evita secar)
5. Exponha ao **sol direto** por 4-8 horas
6. Enxague bem com agua
7. Repita se necessario

**Cuidados:**
- Use luvas (peroxido irrita a pele)
- So aplique na carcaca, **NUNCA na placa eletronica**
- Nao deixe secar - reaplique ou use filme plastico
- Sol nublado funciona (UV atravessa nuvens)

**Resultados esperados:**
- Amarelamento leve: 1 sessao
- Amarelamento forte: 2-3 sessoes

### Prevencao de Amarelamento

| Acao | Eficacia |
|------|----------|
| Guardar longe da luz solar | Alta |
| Guardar em local escuro/armario | Alta |
| Usar capa protetora | Media |
| Evitar calor/umidade | Media |

### Produtos para Limpeza da Carcaca

| Produto | Uso | Observacao |
|---------|-----|------------|
| Pano microfibra + agua | Limpeza basica | Suficiente para manutencao |
| Detergente neutro diluido | Sujeira pesada | Enxaguar bem |
| 303 Aerospace Protectant | Protetor UV | Importado, ~US$ 15-20 |

### O que NAO Usar na Carcaca
- Alcool (pode deixar opaco/esbranquicado)
- Produtos abrasivos
- Cera automotiva com silicone (fica pegajoso)
- WD-40

---

## 6. Armazenamento Correto

### Console
- **Posicao:** Horizontal, superficie plana
- **Local:** Ambiente seco, sem luz solar direta
- **Temperatura:** 15-25C
- **Umidade:** Baixa (usar sachets de silica gel)
- **Cobertura:** Usar capa protetora contra poeira

### Cartuchos
- **Posicao:** Vertical, etiqueta visivel
- **Contatos:** Sempre para baixo ou cobertos
- **Caixas:** Usar caixas de armazenamento universais
- **Protecao:** Protetores plasticos nos contatos

### Evitar
- Locais umidos
- Exposicao solar direta
- Variacoes de temperatura
- Proximidade de imas
- Fumar perto dos equipamentos

---

## 7. Diagnostico de Problemas

| Sintoma | Causa Provavel | Solucao |
|---------|----------------|---------|
| Tela preta | Cartucho/slot sujo, fonte | Limpar contatos, testar fonte |
| Imagem piscando | Contatos oxidados | Limpeza profunda |
| Linha vertical | Regulador de voltagem | Adicionar capacitor |
| Imagem com neve | Capacitores, cabo AV | Recap, trocar cabo |
| Audio distorcido | Capacitores de audio | Recap |
| Saves perdidos | Bateria esgotada | Trocar CR2032 |
| Jogo trava | Cartucho sujo | Limpar |
| Console desliga | Superaquecimento | Verificar ventilacao |

---

## 8. Ferramentas Essenciais

| Ferramenta | Uso | Onde Comprar |
|------------|-----|--------------|
| Chave Gamebit 3.8mm | Cartuchos | AliExpress, Amazon |
| Chave Gamebit 4.5mm | Console | AliExpress, Amazon |
| Chave Philips pequena | Geral | Qualquer loja |
| Alcool isopropilico 90%+ | Limpeza | Farmacia, eletronicas |
| Cotonetes de algodao | Limpeza | Farmacia |
| Panos de microfibra | Limpeza | Qualquer loja |
| Ferro de solda 30W | Troca bateria | Eletronicas |

---

## Meu Inventario de Ferramentas

| Item | Tenho? | Observacao |
|------|--------|------------|
| Chave Gamebit 3.8mm | [ ] | Para abrir cartuchos |
| Chave Gamebit 4.5mm | [ ] | Para abrir console |
| Alcool isopropilico 90%+ | [ ] | - |
| **Limpa contato Wurth** | ✅ Sim | Versao sem oleo - OK para uso |
| Ferro de solda | [ ] | Para troca de bateria |
| Baterias CR2032 | [ ] | Com terminais soldaveis |
| Creme oxidante 40 vol | [ ] | Para Retr0bright |

---

## Historico de Manutencao

| Data | Acao | Observacao |
|------|------|------------|
| - | - | - |

---

**Fontes:** RetroRGB.com, Console5 Wiki, Hackaday

**Ultima atualizacao:** Janeiro 2026
