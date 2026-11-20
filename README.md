# Matthieu Rivière

*[English version below](#english)*

**Développeur senior depuis 9 ans — backend PHP/Symfony, je conçois aujourd'hui des fonctionnalités d'IA en production.**
Région de Montréal, Québec · Français et anglais · [LinkedIn](https://www.linkedin.com/in/rivierematthieu/) · riviere.matthieu@outlook.com

## Projets phares

| Projet | De quoi il s'agit | Stack | Code |
|---|---|---|---|
| [**vigil**](https://github.com/mriviere-company/vigil) | API de modération de contenu par IA : verdict en 18 ms au p95, ROC-AUC en français passé de 0,783 à 0,983, infrastructure Terraform sur AWS, environ 0,002 $ les 1 000 inférences | Go, Python, FastAPI, ONNX Runtime, Terraform, AWS ECS Fargate | public |
| [**Sextant**](https://github.com/mriviere-company/sextant) | RAG multilingue sur le wiki d'Area Universe (6 langues), construit autour de son évaluation : BM25, recherche vectorielle pgvector, hybride et reranking comparés en nDCG et MRR, avec des règles de décision fixées avant toute mesure. En cours | Python, PostgreSQL, pgvector, embeddings multilingues, DeepSeek | public |
| [**Area Universe**](https://www.areauniverse.com/) | Jeu de stratégie spatiale multijoueur que je développe et exploite seul depuis 2017 (pic de 850 joueurs actifs). La [version originale](https://github.com/mriviere-company/Area) est écrite entièrement à la main, sans IA ; la refonte de 2024 ajoute des bots joueurs pilotés par IA | Symfony 8, Vue 3, TypeScript, Python, DeepSeek, Capacitor, Hetzner | original public, refonte privée |
| [**Slash**](https://slash-game.com/) | Jeu en ligne où l'on se cache dans une foule de PNJ ; un classifieur statistique (régression logistique ridge, test de permutation) tourne en CI et fait échouer le build si les joueurs deviennent reconnaissables | TypeScript, WebSockets, Terraform, Cloudflare | privé |
| **Périples** | Plateforme de livres-jeux avec mécanique RPG : assistant d'écriture Claude pour les auteurs, compagnon de lecture DeepSeek sans spoiler, marketplace Stripe | Symfony 7.4, Vue 3, Ionic, Stripe | privé |

Le code privé peut être montré sur demande.

## Compétences

- **IA et LLM :** Claude, DeepSeek, conception de prompts, sorties JSON structurées, garde-fous de sortie, budgets de coût et de latence, évaluation de modèles (ROC-AUC, F1), ONNX Runtime, Hugging Face
- **Backend :** PHP 8, Symfony, API Platform, Doctrine, Python, FastAPI, Go, API REST
- **Frontend :** Vue 3, TypeScript, React
- **Cloud et DevOps :** AWS (ECS, S3), Terraform, Docker, GitHub Actions, serveurs Linux
- **Qualité et sécurité :** PHPUnit, pytest, Vitest, Playwright, correction d'audits d'intrusion, conformité à la Loi 25

## Expérience

| Période | Entreprise | Poste |
|---|---|---|
| 2026 – aujourd'hui | Groupe Alesco | Développeur Web Senior |
| 2024 – 2026 | Vidéotron | Analyste programmeur expert |
| 2024 | Groupe Investiir | Développeur fullstack, puis directeur technique |
| 2021 – 2024 | Future PLC | Développeur Web (télétravail, équipe au Royaume-Uni) |
| 2019 – 2021 | La Place de l'Immobilier | Développeur Web |
| 2017 – 2019 | Medelse | Développeur Web Junior |

Formation : École 42 Paris (2014 – 2017).

## Ma façon de travailler avec l'IA

Aujourd'hui, je développe avec des agents de code (Claude Code), encadrés par des specs écrites, des plans d'implémentation et des portes de CI que le code doit franchir. Mes projets antérieurs, comme la version originale d'Area Universe, ont été écrits entièrement à la main.

---

<a id="english"></a>

# Matthieu Rivière

**Senior developer, 9 years — PHP/Symfony backend, now building AI features in production.**
Montréal area, Québec · French and English · [LinkedIn](https://www.linkedin.com/in/rivierematthieu/) · riviere.matthieu@outlook.com

## Featured projects

| Project | What it is | Stack | Code |
|---|---|---|---|
| [**vigil**](https://github.com/mriviere-company/vigil) | AI content-moderation API: verdict in 18 ms at p95, French ROC-AUC raised from 0.783 to 0.983, Terraform on AWS, about $0.002 per 1,000 inferences | Go, Python, FastAPI, ONNX Runtime, Terraform, AWS ECS Fargate | public |
| [**Sextant**](https://github.com/mriviere-company/sextant) | Multilingual RAG over the Area Universe wiki (6 languages), built around its evaluation: BM25, pgvector dense search, hybrid and reranked retrieval compared with nDCG and MRR, with decision rules set before any run. In progress | Python, PostgreSQL, pgvector, multilingual embeddings, DeepSeek | public |
| [**Area Universe**](https://www.areauniverse.com/) | Multiplayer space strategy game I have built and run alone since 2017 (peak of 850 active players). The [original version](https://github.com/mriviere-company/Area) was written entirely by hand, with no AI; the 2024 rebuild adds AI-driven player bots | Symfony 8, Vue 3, TypeScript, Python, DeepSeek, Capacitor, Hetzner | original public, rebuild private |
| [**Slash**](https://slash-game.com/) | Online hide-in-the-crowd game; a statistical classifier (ridge logistic regression, permutation test) runs in CI and fails the build if players become distinguishable from NPCs | TypeScript, WebSockets, Terraform, Cloudflare | private |
| **Périples** | Gamebook platform with RPG mechanics: Claude writing assistant for authors, spoiler-free DeepSeek reading companion, Stripe marketplace | Symfony 7.4, Vue 3, Ionic, Stripe | private |

Private code can be shown on request.

## Skills

- **AI and LLMs:** Claude, DeepSeek, prompt design, structured JSON output, output guardrails, cost and latency budgets, model evaluation (ROC-AUC, F1), ONNX Runtime, Hugging Face
- **Backend:** PHP 8, Symfony, API Platform, Doctrine, Python, FastAPI, Go, REST APIs
- **Frontend:** Vue 3, TypeScript, React
- **Cloud and DevOps:** AWS (ECS, S3), Terraform, Docker, GitHub Actions, Linux servers
- **Quality and security:** PHPUnit, pytest, Vitest, Playwright, penetration-test remediation, Québec Law 25 compliance

## Experience

| Period | Company | Role |
|---|---|---|
| 2026 – now | Groupe Alesco | Senior Web Developer |
| 2024 – 2026 | Vidéotron | Expert Analyst Programmer |
| 2024 | Groupe Investiir | Full Stack Developer, then CTO |
| 2021 – 2024 | Future PLC | Web Developer (remote, UK team) |
| 2019 – 2021 | La Place de l'Immobilier | Web Developer |
| 2017 – 2019 | Medelse | Junior Web Developer |

Education: École 42 Paris (2014 – 2017).

## How I work with AI

Today, I develop with coding agents (Claude Code), framed by written specs, implementation plans, and CI gates the code must pass. My earlier projects, like the original Area Universe, were written entirely by hand.
