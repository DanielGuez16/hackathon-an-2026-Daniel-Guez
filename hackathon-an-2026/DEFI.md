# DEFI.md

### Nom du défi
TALIA — Un copilote IA fiable pour préparer une intervention parlementaire

### Description courte
Un copilote IA qui aide un député à maîtriser un sujet juridique technique en quelques heures : retrouver les bons textes, garantir la version en vigueur à la date utile, et sourcer chaque affirmation par un lien officiel vérifiable — sans jamais halluciner le droit.

### Porteur
TALIA

### Description longue
**Le problème.** Un député doit souvent maîtriser un sujet juridique technique en 24 ou 48 heures pour une commission ou une séance. Entre le dépôt d'un texte et son examen, l'élu et ses collaborateurs doivent absorber un sujet complexe, en maîtriser les sources — loi, jurisprudence, doctrine, droit européen — puis produire une note structurée avec des citations primaires vérifiables. Le tout sous une exigence absolue : **ne jamais se tromper sur le droit.**

**Pourquoi les IA généralistes échouent.** Elles hallucinent des textes qui n'existent pas, citent des versions périmées d'un article, ou affirment sans source. Dans un cadre où l'erreur n'est pas permise, elles sont inutilisables.

**Le défi.** Concevoir un copilote qui *augmente* le travail parlementaire sans jamais en compromettre la fiabilité. Concrètement, il devrait :

- **Retrouver les textes pertinents** face à une question juridique (loi, code, jurisprudence, doctrine, droit de l'Union européenne).
- **Signaler la version en vigueur** à la date utile, et distinguer clairement ce qui est abrogé, modifié ou consolidé.
- **Distinguer les natures de source** — loi, jurisprudence, doctrine — sans les mélanger ni les confondre en autorité.
- **Sourcer chaque affirmation** par un lien officiel vérifiable (Légifrance, Journal officiel, dossiers législatifs), avec citation primaire.
- **Restituer une note structurée** exploitable directement pour une intervention en commission ou en séance.

**L'enjeu.** Il ne s'agit pas de remplacer le jugement de l'élu, mais de lui rendre du temps en sécurisant sa recherche. La question centrale : comment construire une IA juridique à laquelle un parlementaire pourrait *vraiment* se fier — c'est-à-dire une IA qui préfère dire « je ne sais pas » plutôt que d'inventer, et qui rend chaque affirmation traçable jusqu'à sa source officielle ?

**Notre approche.** _(à compléter : architecture RAG ancrée sur sources primaires, vérification de la version en vigueur, refus de répondre hors sources, citations cliquables vers les textes officiels, etc.)_

### Image principale
![Image principale](images/cover.png)

### Contributeurs
- Daniel Guez

### Ressources utilisées
Cochez les ressources utilisées en remplaçant `[ ]` par `[x]`.

- [ ] `openfisca-france-parameters` — Base de données de paramètres ✺ OpenFisca
- [ ] `an-dossiers-legislatifs` — Dossiers législatifs de l'Assemblée nationale (législature courante) ✺ Assemblée nationale
- [ ] `an-amendements-xvii` — Amendements déposés à l'Assemblée nationale (législature actuelle) ✺ Assemblée nationale
- [ ] `an-comptes-rendus` — Comptes rendus de la séance publique à l'Assemblée nationale (législature actuelle) ✺ Assemblée nationale
- [ ] `an-votes-xvii` — Votes des députés (législature actuelle) ✺ Assemblée nationale
- [ ] `an-deputes-en-exercice` — Députés en exercice ✺ Assemblée nationale
- [ ] `an-deputes-historique` — Historique des députés ✺ Assemblée nationale
- [ ] `an-deputes-senateurs-ministres-par-legislature` — Députés, sénateurs et ministres d'une législature ✺ Assemblée nationale
- [ ] `an-agenda-reunions` — Agenda des réunions à l'Assemblée nationale (législature courante) ✺ Assemblée nationale
- [ ] `an-questions-gouvernement` — Questions de l'Assemblée nationale au Gouvernement ✺ Assemblée nationale
- [ ] `an-questions-gouvernement-ecrites` — Questions écrites de l'Assemblée nationale au Gouvernement ✺ Assemblée nationale
- [ ] `an-questions-gouvernement-orales` — Questions orales de l'Assemblée nationale au Gouvernement ✺ Assemblée nationale
- [ ] `premier-ministre-legi` — Codes, lois et règlements consolidés ✺ Premier ministre
- [ ] `premier-ministre-dole` — Dossiers législatifs Légifrance ✺ Premier ministre
- [ ] `premier-ministre-jorf` — Édition ''Lois et décrets'' du Journal officiel ✺ Premier ministre
- [ ] `senat-dispositifs-textes` — Dispositifs des textes déposés ou adoptés au Sénat ✺ Sénat
- [ ] `senat-dossiers-legislatifs` — Dossiers législatifs du Sénat ✺ Sénat
- [ ] `senat-amendements` — Amendements déposés au Sénat ✺ Sénat
- [ ] `senat-senateurs` — Sénateurs ✺ Sénat
- [ ] `senat-questions-gouvernement` — Questions orales et écrites du Sénat au Gouvernement ✺ Sénat
- [ ] `senat-comptes-rendus` — Comptes rendus de la séance publique au Sénat ✺ Sénat
- [ ] `an-et-co-database-regroupement-toutes-donnees` — Base de données unifiée Parlement / Législation / Service Public ✺ Assemblée nationale & communauté
- [ ] `an-et-co-serveur-mcp-regroupement-toutes-donnees` — Serveur MCP  - Accès unifié Parlement / Législation / Service Public ✺ Assemblée nationale & communauté
- [ ] `an-et-co-api-regroupement-toutes-donnees` — API - Accès unifié Parlement / Législation / Service Public ✺ Assemblée nationale & communauté
- [ ] `legiwatch-api-parlement` — API Parlement ✺ LegiWatch
- [ ] `legiwatch-database-parlement` — Base de données Parlement ✺ LegiWatch
- [ ] `legiwatch-serveur-mcp-parlement` — Serveur MCP Parlement ✺ LegiWatch

### Galerie
- [Image 1](images/image-1.png)
- [Image 2](images/image-2.png)

### Documents
- [Tableur 1](docs/Classeur1.xlsx)
- [Document 2](docs/document-2.pdf)

### URL de démonstration
https://votre-application.example.com

### Diapositives de présentation
[Diapositives de présentation](docs/diapositives.pdf)
