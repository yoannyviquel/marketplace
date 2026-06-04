# Marketplace Claude Code — yoannyviquel

Catalogue de plugins Claude Code. Chaque plugin vit dans **son propre repo** et se met à jour
indépendamment : ce repo ne porte que le `marketplace.json`.

## Utilisation

```
/plugin marketplace add yoannyviquel/marketplace
/plugin install memory
/plugin install it-agents
```

Mettre à jour un plugin (tire depuis son repo source, ce catalogue n'a pas besoin de changer) :

```
/plugin update memory
```

## Plugins

| Plugin | Repo source | Description |
|---|---|---|
| `memory` | [yoannyviquel/memory](https://github.com/yoannyviquel/memory) | Mémoire persistante (SQLite local, BM25 + sémantique). |
| `it-agents` | [yoannyviquel/agents](https://github.com/yoannyviquel/agents) | Agents/skills de développement (dotnet, react, architecte). |
