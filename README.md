# Bertrand Beaujard

Hello à tous !

**Développeur full stack C# / .NET en formation** · Licence pro Métiers de l'informatique à UHA 4.0 (Université de Haute-Alsace, Mulhouse)

 **Je cherche un stage de 6 mois en développement logiciel à partir de janvier 2027**.

Ancien technicien supérieur en chimie et biotechnologie (5 ans en laboratoire + halle chimie), je me suis reconverti dans le développement. Mon objectif : concevoir des logiciels internes pour l'industrie en C# / .NET, et à terme revenir vers la chimie avec un bagage de développeur.

[Portfolio](https://bertrandbj.github.io/) · [LinkedIn](https://www.linkedin.com/in/bertrand-beaujard/)

---

 Stack technique

| Domaine | Technologies |
|---|---|
| **Langages** | C# (LINQ), TypeScript, JavaScript, SQL, PHP, HTML / CSS |
| **Back-end** | .NET 8, ASP.NET Core (API REST), NestJS, Node.js |
| **Front-end** | Blazor WebAssembly, Next.js (React), .NET MAUI / XAML |
| **Données** | SQL Server, PostgreSQL, MongoDB, SQLite, Entity Framework Core, Prisma |
| **Conception** | POO, patrons de conception, UML, MVVM, MVC, architecture en couches |
| **Qualité** | Tests unitaires et d'intégration (xUnit), analyse statique SonarQube, `dotnet format` en CI |
| **DevOps** | Docker, Docker Compose, GitLab CI, GitHub Actions, déploiement SSH |
| **Outils** | Visual Studio, Rider, Git, Swagger / OpenAPI |
| **Méthodes** | Scrum (rôle de Scrum Master), Jira, Confluence, methode agile |

**Langues :** français (langue maternelle), anglais (C2)

---

##  Projets

### [TMS2000](https://github.com/BertrandBJ/TMS2000) · projet individuel, en cours
Jeu de trading sur mobile : les joueurs achètent et revendent des ressources dont le prix évolue en continu, et un administrateur fixe les règles du marché (taxes, blocages, limites de quantité).
- API REST **ASP.NET Core (.NET 8)** + **MongoDB**, architecture en couches (Shared / Core / Server / Tests / Mobile)
- Authentification JWT avec refresh tokens, erreurs métier renvoyées en `ProblemDetails`
- Test d'integration couvrant l'API et la logique métier.
- Pipeline **GitLab CI** (build, contrôle du formatage, tests, déploiement), analyse **SonarQube** via GitHub Actions, et déploiement automatique sur un serveur de l'UHA avec **Docker Compose**
- En cours : client **.NET MAUI** (Android) avec base **SQLite** locale, utilisable hors ligne et synchronisé avec le serveur

### [Portfolio](https://github.com/BertrandBJ/bertrandbj.github.io) · projet individuel
Site portfolio en **Blazor WebAssembly** (.NET 8), CSS sans framework.
- Contenu des projets chargé depuis un JSON, derrière une interface `IProjectService` (remplaçable par une API sans toucher aux composants)
- Chaque projet a sa propre URL partageable
- Publication et déploiement sur **GitHub Pages** via **GitHub Actions** à chaque merge sur `main`

### SCHMIDT Groupe · projet client, équipe de 5 · 2025 – 2026
Application interne de gestion de stock et de commandes, développée sur le socle technique MES de l'entreprise.
- Modélisation de la base avec **Entity Framework Core** sur **SQL Server** (migrations, seeding)
- Fonctionnalités CRUD de bout en bout : API REST ASP.NET Core, DTO, formulaires **Blazor**
- Recueil des besoins et tests utilisateurs sur site, refactoring pour respecter l'architecture existante

### YouRHway · projet client, équipe de 5, Scrum Master · 2026
Reprise et évolution d'une application SaaS de sondage en **TypeScript** (**Next.js** + **NestJS**, **PostgreSQL**, **Prisma**, Docker).
- Refonte du système de rôles : nouveau rôle avec restrictions d'accès, évolution du schéma de base
- Parcours complet de réinitialisation de mot de passe avec envoi d'e-mails transactionnels
- Règles métier sur les objectifs et le recalcul des cotations

### HoplaCup · projet associatif, équipe de 5 · 2025
Plugin **WordPress** (PHP, JavaScript, SQL) pour la gestion de tournois internationaux de water-polo.

---

*Le code des projets clients n'est pas public.*
