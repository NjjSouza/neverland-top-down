### Top-down Unreal Project Game - C++ ♡

> **Status:** Em Desenvolvimento / Estudo Ativo  
> **Stack:** Unreal Engine 5 (C++ Native), C++20  
> **Conceito:** Protótipo Top-Down 2D focado no aprendizado prático de Arquitetura de Games, Unreal C++ e Resolução Algorítmica de Problemas.

### ───⟢⊱  ۫ ׅ ♡
---

## Sobre o Projeto

Este projeto é meu primeiro contato com desenvolvimento Top-Down e Unreal Engine C++. Diferente de um jogo tradicional, a motivação principal aqui é aplicar conceitos de estruturas de dados e algoritmos por necessidade prática: o jogo gera desafios de gameplay e arquitetura, que são resolvidos com conceitos fundamentais de Ciência da Computação.

### Filosofia de Desenvolvimento
- **Problem-Driven Learning:** A mecânica cria o problema real no jogo -> O algoritmo necessário é estudado e modelado -> A solução é implementada em C++ puro -> Integração à Unreal Engine.
- **Isolamento de Algoritmos:** Algoritmos complexos são desenvolvidos e testados separadamente (*Algorithm Lab*) antes de serem desacoplados e plugados nas entidades (`AActor`, `UActorComponent`) do jogo.

### ───⟢⊱  ۫ ׅ ♡
---

## 🏗️ Arquitetura & Módulos

O repositório é dividido entre a aplicação Unreal Engine e um módulo nativo de algoritmos e estruturas de dados:

```text
├── Source/
│   ├── Game/                 # Classes Unreal (Actors, Components, GameModes)
│   │   ├── Core/             # Base PlayerController, GameModeBase, Character
│   │   ├── Entities/         # Player, Enemy, Item, Interatíveis
│   │   └── Subsystems/       # Managers de Estado, Spawners, Eventos
│   │
│   └── AlgorithmLab/         # Módulo C++ Nativo (Desacoplado da UE)
│       ├── DataStructures/   # Heap, Graph (Adjacency List), Queue, DSU
│       ├── Pathfinding/      # BFS, Dijkstra, A*
│       ├── Generation/       # Algoritmos de Geração Procedural / Grafos
│       └── Tests/            # Unittests e Benchmarks de performance
```
### ───⟢⊱  ۫ ׅ ♡
