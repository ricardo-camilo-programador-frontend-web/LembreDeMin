# Arquivos de Cenários - Ren'Py
# Estes arquivos devem ser colocados em game/tl/pt_BR/ ou game/

## Estrutura de Arquivos

```
game/
├── scripts/
│   ├── scenario1_forest.rpy      # A Floresta dos Ecos
│   ├── scenario2_mirror.rpy      # O Enigma do Espelho Partido
│   ├── scenario3_library.rpy     # A Biblioteca das Almas
│   ├── scenario4_garden.rpy      # O Jardim Secreto
│   └── scenario5_final.rpy       # O Encontro Final
├── images/
│   ├── bg/
│   │   ├── forest_echo.png
│   │   ├── broken_mirror.png
│   │   ├── library_souls.png
│   │   └── secret_garden.png
│   └── characters/
│       ├── librarian/
│       └── guardian/
└── audio/
    ├── music/
    │   ├── forest_ambience.ogg
    │   ├── mystery.ogg
    │   └── final_revelation.ogg
    └── sfx/
        ├── mirror_crack.ogg
        └── page_turn.ogg
```

## Variáveis de Estado

```renpy
# Em game/scripts/variables.rpy
default soul_light = 0
default soul_shadow = 0
default flowers_collected = []
default scenarios_visited = []
default endings_unlocked = []
```

## Labels Principais

```renpy
# Estrutura de navegação
label start:
    # Introdução existente
    jump scenario_choice

label scenario_choice:
    # Menu de escolha de cenários
    # Baseado em progresso
    return
```
