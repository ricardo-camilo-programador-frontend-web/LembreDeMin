# Novos Cenários - LembreDeMin

## Visão Geral
Este documento descreve novos cenários e caminhos narrativos para expandir a história do jogo.

---

## Cenário 1: A Floresta dos Ecos

### Contexto
O protagonista encontra uma floresta misteriosa onde vozes do passado ecoam entre as árvores.

### Decisões
```
┌─────────────────────────────────────────────────────────┐
│  Ao ouvir uma voz familiar chamando seu nome:          │
│                                                         │
│  [A] Seguir a voz em direção à floresta densa          │
│      → Revela memórias reprimidas                       │
│      → +10 pontos Luz (coragem de enfrentar o passado) │
│                                                         │
│  [B] Ignorar e continuar pelo caminho seguro           │
│      → Mantém memórias ocultas                          │
│      → +5 pontos Sombra (evitar confronto)             │
│                                                         │
│  [C] Gritar de volta perguntando quem é                │
│      → A voz responde com um enigma                     │
│      → Abre caminho para o Cenário 2                   │
└─────────────────────────────────────────────────────────┘
```

### Diálogos

**Se escolher [A]:**
```
player "Preciso descobrir quem está me chamando..."

narrator "A floresta se abre revelando clareiras de memórias antigas."
narrator "Você vê flashes de momentos que preferia esquecer."
narrator "Mas enfrentá-los traz uma estranha paz."

voice "Você finalmente voltou... Eu sabia que viria."

player "Quem é você? Por que me conhece?"

voice "Sou parte de você. A parte que você deixou para trás."
```

---

## Cenário 2: O Enigma do Espelho Partido

### Contexto
Após responder ao enigma da voz, o protagonista encontra um espelho quebrado que mostra fragmentos de realidades alternativas.

### Decisões
```
┌─────────────────────────────────────────────────────────┐
│  O espelho mostra três reflexos diferentes de você:    │
│                                                         │
│  [A] O reflexo sorridente em um jardim florido         │
│      → Revela o que poderia ter sido                    │
│      → +15 pontos Luz (esperança)                       │
│      → Desbloqueia final alternativo "Jardim Eterno"   │
│                                                         │
│  [B] O reflexo sombrio em uma sala vazia               │
│      → Mostra medos internos                            │
│      → +10 pontos Sombra (aceitação da escuridão)      │
│      → Desbloqueia final "Solidão Confortadora"        │
│                                                         │
│  [C] Tentar colar os pedaços do espelho                │
│      → Ação de reparação                                │
│      → +20 pontos Luz (determinação em curar)          │
│      → Desbloqueia final "Restauração"                 │
└─────────────────────────────────────────────────────────┘
```

### Diálogos

**Se escolher [C]:**
```
player "Talvez se eu juntar os pedaços..."

narrator "Você começa a recolher os fragmentos afiados."
narrator "Suas mãos sangram, mas você não para."

mirror "Por que se esforça tanto por algo quebrado?"

player "Porque nada está realmente perdido enquanto tentamos consertar."

narrator "O espelho começa a brilhar."
narrator "As rachaduras se transformam em linhas de luz dourada."
```

---

## Cenário 3: A Biblioteca das Almas

### Contexto
Um local onde cada livro contém a história de uma alma que passou pelo mesmo caminho.

### Decisões
```
┌─────────────────────────────────────────────────────────┐
│  Três livros chamam sua atenção:                       │
│                                                         │
│  [A] "O Viajante da Luz" - capa dourada                │
│      → Conta histórias de almas que escolheram a luz   │
│      → +5 pontos Luz (inspiração)                       │
│      → Revela dicas sobre escolhas futuras             │
│                                                         │
│  [B] "Sombras do Passado" - capa negra                 │
│      → Conta histórias de almas que abraçaram a escur. │
│      → +5 pontos Sombra (compreensão)                   │
│      → Revela segredos sobre a natureza das sombras    │
│                                                         │
│  [C] "O Equilíbrio" - capa cinza                       │
│      → Conta histórias de almas que encontraram balanço│
│      → +10 pontos Luz E +10 pontos Sombra              │
│      → Desbloqueia final "Harmonia Perfeita"           │
└─────────────────────────────────────────────────────────┘
```

### Diálogos

**Interação com o Bibliotecário:**
```
show librarian at center

librarian "Bem-vindo à Biblioteca das Almas."
librarian "Cada livro aqui contém uma jornada como a sua."

player "Por que eu posso ler sobre os outros?"

librarian "Porque suas escolhas ainda não foram escritas."
librarian "Aqui você pode aprender... ou se perder."
librarian "Depende do que você busca."

menu:
    "Quero entender o caminho da luz.":
        librarian "Então comece pelo dourado."
        librarian "Mas cuidado: a luz pode cegar tanto quanto a escuridão."
    
    "Quero conhecer minhas sombras.":
        librarian "Corajoso. Poucos enfrentam o que estão dispostos a ser."
        librarian "O livro negro o aguarda."
    
    "Quero encontrar equilíbrio.":
        librarian "Interessante..."
        librarian "Esse é o caminho mais difícil de todos."
        librarian "Pois exige aceitar que você é ambos."
```

---

## Cenário 4: O Jardim Secreto

### Contexto
Um jardim oculto onde flores crescem de emoções cultivadas.

### Mecânica: Sistema de Cultivo
```
┌─────────────────────────────────────────────────────────┐
│  Você pode plantar sementes de emoções:                │
│                                                         │
│  🌸 Semente da Esperança → Floresce em momentos bons   │
│  🌺 Semente da Coragem → Floresce em desafios          │
│  🥀 Semente da Tristeza → Floresce em aceitação        │
│  🌿 Semente da Calma → Floresce em equilíbrio          │
│                                                         │
│  Cada flor colhida concede bônus nas escolhas finais.  │
└─────────────────────────────────────────────────────────┘
```

### Decisões
```
┌─────────────────────────────────────────────────────────┐
│  Uma planta está morrendo. Você pode:                  │
│                                                         │
│  [A] Regar com lágrimas de memórias tristes            │
│      → A planta sobrevive mas muda de cor               │
│      → +5 pontos Sombra                                 │
│      → A flor se torna "Rosa da Saudade"               │
│                                                         │
│  [B] Cantar uma canção de esperança                     │
│      → A planta floresce intensamente                   │
│      → +10 pontos Luz                                   │
│      → A flor se torna "Girassol da Alegria"           │
│                                                         │
│  [C] Aceitar que seu ciclo terminou                     │
│      → A planta morre, mas suas sementes são coletadas │
│      → +5 Luz +5 Sombra (ciclo natural)                │
│      → Ganha 3 sementes para plantar depois            │
└─────────────────────────────────────────────────────────┘
```

---

## Cenário 5: O Encontro Final

### Contexto
O momento antes de chegar ao espelho mágico final. Todas as escolhas anteriores convergem aqui.

### Personagem: O Guardião
```
guardian "Você percorreu um longo caminho."
guardian "Cada escolha moldou quem você é agora."
guardian "Mas ainda há uma última decisão."

player "O que devo fazer?"

guardian "O espelho mostrará sua verdade."
guardian "Mas você pode escolher como enfrentá-la."

menu final_choice:
    "Quero ver toda a verdade, por mais dolorosa que seja.":
        guardian "Coragem verdadeira..."
        # Mostra todos os momentos Sombra
        # +20 pontos Sombra (aceitação total)
        # Final "Verdade Absoluta"
    
    "Quero ver apenas a luz que cultivei.":
        guardian "Uma escolha gentil..."
        # Mostra apenas momentos Luz
        # +20 pontos Luz (foco no positivo)
        # Final "Luz Interior"
    
    "Quero ver o equilíbrio entre ambas.":
        guardian "A sabedoria mais rara..."
        # Mostra momentos de ambos
        # Requer: ter pelo menos 30 pontos de cada
        # Final "Harmonia Perfeita"
```

---

## Finais Desbloqueáveis

### Final 1: Luz Radiante
- **Requisito:** 80+ pontos Luz
- **Descrição:** O espelho revela uma alma pura, iluminada por todas as escolhas bondosas. O protagonista encontra paz eterna.

### Final 2: Sombra Acolhedora
- **Requisito:** 80+ pontos Sombra
- **Descrição:** O espelho revela uma alma que abraçou sua escuridão. Não há condenação, apenas aceitação de quem se é.

### Final 3: Harmonia Perfeita
- **Requisito:** 40-60 pontos em ambos (equilíbrio)
- **Descrição:** O espelho mostra uma alma completa, que aceita tanto luz quanto sombra como partes essenciais de si.

### Final 4: Jardim Eterno
- **Requisito:** Escolher [A] no Cenário 2 + cultivar 5+ flores
- **Descrição:** O protagonista transcende o espelho e encontra um jardim onde todas as almas em harmonia habitam.

### Final 5: Restauração
- **Requisito:** Escolher [C] no Cenário 2
- **Descrição:** O espelho partido se cura completamente, revelando que o protagonista também pode se curar.

### Final 6: Verdade Absoluta
- **Requisito:** Escolher ver toda a verdade no Cenário 5
- **Descrição:** Uma revelação profunda sobre a natureza dual de todas as almas. O mais filosófico dos finais.

---

## Sistema de Pontuação

```
Escolhas Luz:
- Coragem de enfrentar o passado
- Esperança e otimismo
- Ajuda ao próximo
- Honestidade
- Perdão

Escolhas Sombra:
- Auto-preservação
- Aceitação da escuridão
- Honestidade brutal
- Vingança ou justiça
- Solidão escolhida

Equilíbrio:
- Aceitação de ambas as naturezas
- Escolhas que reconhecem complexidade
- Não negar nem luz nem sombra
```

---

## Próximos Passos de Implementação

1. [ ] Criar arquivos .rpy para cada cenário
2. [ ] Definir sprites para novos personagens (Bibliotecário, Guardião)
3. [ ] Criar backgrounds (Floresta, Biblioteca, Jardim)
4. [ ] Implementar sistema de pontuação
5. [ ] Testar todos os caminhos e finais
6. [ ] Adicionar músicas para cada cenário
