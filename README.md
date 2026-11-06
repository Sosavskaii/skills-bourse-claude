# Claude, analyste de bourse : presque 100 skills de trading gratuites

Deux collections de skills réunies dans un seul dépôt. Avec elles, Claude analyse une action, lit une courbe, teste une stratégie et vérifie ton plan avant chaque achat.

> ⚠️ **Pas un conseil financier.** Ces skills servent à analyser et à apprendre. Elles ne passent aucun ordre et ne garantissent aucun gain. Tu restes seul juge de tes décisions.

## Ce qu'il y a dedans

### `trading-skills/` (74 skills, par TraderMonty)
- **Lire une courbe** (`technical-analyst`) : envoie une capture d'un graphique, Claude repère les figures et donne 2 à 4 scénarios avec un pourcentage chacun.
- **Humeur du marché** : `market-breadth-analyzer`, `us-market-bubble-detector`, `market-top-detector`, `macro-regime-detector`.
- **Tester une stratégie sur le passé** : `backtest-expert`.
- **La skill qui dit non** (`pre-trade-discipline-gate`) : avant chaque achat, elle vérifie ton plan, ton stop et ta taille de position, et répond GO ou NO_GO.
- **Gérer le risque** : `position-sizer`, `drawdown-circuit-breaker`, `portfolio-manager`.
- Et des dizaines de filtres d'actions (dividendes, croissance, momentum…).

### `finance-skills/` (environ 25 skills, par Alex Yang)
- **Résultats d'entreprise** : `earnings-preview`, `earnings-recap`, `estimate-analysis`.
- **Ce que disent les gens** : `finance-sentiment` (Reddit, X, news), `twitter-reader`, `opencli-reader`.
- **Valoriser une entreprise** : `company-valuation`.
- **Données de marché** : `yfinance-data`, `tradingview-mcp`.

## Installer (Claude Code)

1. Télécharge ce dépôt (bouton vert **Code** → **Download ZIP**) et dézippe-le.
2. Copie les dossiers de skills qui t'intéressent dans `~/.claude/skills/` :
   - depuis `trading-skills/skills/` (un dossier = une skill)
   - depuis `finance-skills/plugins/` (les skills sont rangées par groupe)
3. Relance Claude Code et demande par exemple : « analyse cette capture de courbe » ou « vérifie mon plan avant d'acheter ».

Sur claude.ai : les fichiers `.skill` prêts à importer sont dans `trading-skills/skill-packages/`.

Certaines skills demandent une clé d'API gratuite ou payante (FMP, Finviz, Adanos…) : c'est indiqué dans leur fichier `SKILL.md`. La plupart sont pensées pour la bourse américaine.

## Crédits et licences

- `trading-skills/` : copie de [tradermonty/claude-trading-skills](https://github.com/tradermonty/claude-trading-skills), licence MIT, © 2026 TraderMonty.
- `finance-skills/` : copie de [himself65/finance-skills](https://github.com/himself65/finance-skills), licence MIT, © 2025 Alex Yang.

Les licences d'origine sont gardées dans chaque dossier. Pour les mises à jour, va voir les dépôts d'origine.

---
Rassemblé par [@sosav.ai](https://instagram.com/sosav.ai).
