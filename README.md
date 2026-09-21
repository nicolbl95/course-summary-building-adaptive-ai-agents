# Building Adaptive AI Agents — Résumé de cours

Ce dépôt présente une synthèse structurée en français du cours **Building Adaptive AI Agents**, consacré aux mécanismes permettant à des agents d’intelligence artificielle d’apprendre de leurs expériences, de développer des compétences réutilisables, de structurer leurs connaissances et d’adapter leur comportement au fil du temps.

Cours officiel : [Building Adaptive AI Agents — DeepLearning.AI](https://www.deeplearning.ai/courses/building-adaptive-ai-agents)

## Thèmes étudiés

- fonctionnement d’un agent IA, `agent loop` et rôle du `harness` ;
- mémoire de travail, mémoire épisodique, sémantique et procédurale ;
- traces d’exécution et apprentissage à partir de l’expérience ;
- `skill induction`, `human-in-the-loop` et `Skill Box` ;
- `Code Knowledge Graph`, recherche structurée et `retrieval` ;
- relations `import`, `call` et `co-edit`, `anchor` et PageRank ;
- mise à jour incrémentale d’un graphe de code ;
- adaptation dans le `token space` et le `weight space` ;
- fine-tuning, LoRA, quantization, adapters et router.

## Sommaire

1. [Agents, mémoire et traces](cours/01-agents-memory-and-traces.md)
2. [Skill induction](cours/02-skill-induction.md)
3. [Code Knowledge Graphs](cours/03-code-knowledge-graphs.md)
4. [Construction et retrieval dans un Code Knowledge Graph](cours/04-building-and-retrieving-code-graphs.md)
5. [Weight-space adaptation : LoRA, quantization et router](cours/05-weight-space-lora-quantization.md)

## Organisation du dépôt

```text
cours/   → synthèses détaillées du cours
assets/  → captures d’écran, schémas et illustrations
```

Les chiffres et résultats mentionnés sont ceux des expériences présentées dans le cours. Ils servent à comprendre les compromis et ne constituent pas une promesse générale de performance.
