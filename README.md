<div align="center">

![Security](https://img.shields.io/badge/SECURITY-ACTIVE-orange?style=for-the-badge&logo=hackthebox)

</div>

<p align="center">
  <img src="Ego_hackers_greatest_weakness.PNG" alt="Hacker Diagram" width="450">
</p>


<div align="center">

<p><em>© 2025 Virginie Lechene 
.</p>

<a href="https://creativecommons.org/licenses/by-nd/4.0/" target="_blank" rel="noopener noreferrer">
  <img src="https://licensebuttons.net/l/by-nd/4.0/88x31.png" 
       alt="Licence Creative Commons BY-ND 4.0">
</a> 

</div>

----
<h2 align="center">EGO - La vraie faiblesse des hackers</h2>

Dans le domaine de la cybersécurité, on imagine souvent les hackers comme des fantômes impossibles à tracer.  
La réalité est beaucoup plus humaine : **leur ego les trahit**.

Ce document explique pourquoi *EGO* est un titre parfaitement pertinent - techniquement, psychologiquement et opérationnellement.  

---  

## 🔐 MICE - Pourquoi parler d’EGO ?

Le modèle **MICE** décrit les motivations humaines :
- **Money** (argent)
- **Ideology** (idéologie)
- **Compromise** (compromission)
- **Ego**

Je mets l’accent sur **EGO**, car c’est la faiblesse la plus visible : l’ego pousse à se mettre en avant, à prendre des risques et finit par briser l’OpSec. C’est souvent ce qui trahit les hackers.

> **OpSec (Operational Security)** : ensemble de pratiques techniques et comportementales qui visent à limiter au maximum les fuites d’informations et à empêcher un adversaire de comprendre qui vous êtes, ce que vous faites et comment vous le faites.

---

## ✅ L’ego provoque des erreurs d’OpSec

➡️ Malgré l’emploi de techniques d’anonymisation, un attaquant peut laisser des indices en :

- réutilisant un outil, un pseudonyme ou une infrastructure ;
- se reconnectant à un système déjà surveillé ;
- mélangeant ses identités personnelles et opérationnelles ;
- conservant des habitudes techniques ou horaires reconnaissables ;
- révélant accidentellement une adresse IP ou des métadonnées.

Ces éléments ne permettent pas toujours d’identifier une personne. Leur recoupement entre plusieurs incidents peut toutefois aider les enquêteurs à relier différentes opérations à un même acteur.

L’excès de confiance peut favoriser certaines erreurs, mais il n’en est pas l’unique cause.


                     ┏━━━━━━━━━━━━━━━━━━━━━━┓
                     ┃       PROFIL         ┃
                     ┃       Hacker         ┃
                     ┗━━━━━━━━━━━━━━━━━━━━━━┛
                               ↑
                               │
                               │
        ┏━━━━━━━━━━━━━━━━━━┓       ┏━━━━━━━━━━━━━━━━━━┓
        ┃   Le curieux     ┃  ←→   ┃   L’obsessif     ┃
        ┗━━━━━━━━━━━━━━━━━━┛       ┗━━━━━━━━━━━━━━━━━━┛
                               │
                               ↓
                     ┏━━━━━━━━━━━━━━━━━━┓
                     ┃  L’opportuniste  ┃
                     ┗━━━━━━━━━━━━━━━━━━┛
                               │
                               ↓
                     ┏━━━━━━━━━━━━━━━━━━┓
                     ┃   Le stratège    ┃
                     ┗━━━━━━━━━━━━━━━━━━┛
                               │
                               ↓
                     ┏━━━━━━━━━━━━━━━━━━┓
                     ┃  Le mercenaire   ┃
                     ┗━━━━━━━━━━━━━━━━━━┛


---   

# Comment les hackers restent (presque) invisibles en ligne   

## Comment certains attaquants dissimulent leur origine en ligne

Les attaquants peuvent utiliser différents intermédiaires afin de compliquer leur identification. Ces méthodes ne les rendent toutefois pas invisibles et peuvent laisser des traces exploitables.

### 1️⃣ L’adresse IP observée n’est pas nécessairement celle de l’attaquant

Une connexion malveillante peut notamment transiter par :

- un appareil ou un routeur compromis ;
- une machine appartenant à un botnet ;
- un VPN ou un proxy ;
- le réseau Tor ;
- plusieurs infrastructures intermédiaires.

➡️ L’adresse IP visible peut donc appartenir à un intermédiaire. Elle reste néanmoins un indice utile pour l’enquête.

---   

### 2️⃣ Les traces peuvent être réparties entre plusieurs services et juridictions

Lorsqu’une connexion passe par plusieurs intermédiaires, les informations utiles peuvent être détenues par différents fournisseurs de VPN, opérateurs, hébergeurs ou services en ligne, parfois situés dans plusieurs pays.

Pour tenter de reconstituer le parcours, les enquêteurs peuvent devoir :

- identifier les intermédiaires concernés ;
- obtenir et comparer des journaux de connexion horodatés ;
- adresser des demandes légales aux entreprises ou aux autorités compétentes ;
- agir avant l’expiration ou la suppression des données.

➡️ La conservation limitée des journaux, le chiffrement, l’absence de données et les délais de coopération peuvent compliquer ou empêcher la remontée jusqu’à l’origine.

---   

### 3️⃣ Le pays depuis lequel un attaquant opère peut compliquer les poursuites

La localisation réelle d’un attaquant et celle des infrastructures utilisées peuvent relever de juridictions différentes.

Une enquête peut devenir plus difficile lorsque :

- les autorités doivent transmettre une demande d’entraide internationale ;
- les lois, les procédures ou les délais de conservation des données diffèrent ;
- les fournisseurs concernés ne disposent plus des journaux nécessaires ;
- la coopération entre les pays est limitée ou lente ;
- l’auteur bénéficie d’une protection ou d’une tolérance locale.

➡️ La localisation à l’étranger ne garantit pas l’impunité, mais elle peut ralentir ou compliquer l’identification, l’arrestation et l’extradition d’un suspect.

---   

### 4️⃣ La défense et l’attaque sont asymétriques

Une organisation doit protéger de nombreux comptes, appareils et services. Un attaquant cherche seulement un point d’entrée exploitable : service mal configuré, mot de passe compromis, logiciel non corrigé ou erreur humaine.

Cette asymétrie peut avantager l’attaquant, mais le défenseur n’a pas besoin d’être parfait. La segmentation, l’authentification multifacteur, la surveillance et la réponse aux incidents peuvent prévenir certaines intrusions ou limiter les conséquences d'une conpromission.

---

### 5️⃣ La répétition de certaines habitudes peut faciliter l’attribution

Certains attaquants peuvent :

- réutiliser les mêmes outils, pseudonymes ou infrastructures ;
- reproduire des techniques et des configurations particulières ;
- revenir sur des systèmes déjà surveillés ;
- conserver des habitudes techniques ou horaires reconnaissables ;
- sous-estimer les capacités d’analyse et de recoupement.

➡️ Ces ressemblances constituent des indices. Elles ne prouvent pas, à elles seules, que plusieurs opérations ont été menées par le même acteur ou le même groupe.

---   

> ⚠️ **NOTE IMPORTANTE**  
> Évitez de communiquer le mot de passe du Wi-Fi principal à des personnes ou à des appareils non maîtrisés. Utilisez plutôt un réseau invité correctement isolé.

## Pourquoi protéger l’accès au Wi-Fi principal

Connaître le mot de passe du Wi-Fi principal permet à un appareil situé à portée de rejoindre ce réseau. Selon sa configuration et les protections en place, cet appareil peut alors :

- détecter certains appareils et services accessibles sur le réseau local ;
- tenter d’exploiter des équipements vulnérables ou mal configurés ;
- accéder à des ressources partagées insuffisamment protégées ;
- observer certaines informations réseau, sans nécessairement pouvoir lire le contenu chiffré des communications ;
- servir de point de départ à d’autres attaques.

➡️ Un appareil compromis connecté au réseau principal augmente le risque pour les autres systèmes, mais ne compromet pas automatiquement tout le réseau.

---

## Pourquoi éviter de connecter des appareils externes au Wi-Fi principal

L’appareil d’un visiteur peut être compromis sans que son propriétaire le sache. Une fois connecté au réseau principal, il peut notamment :

- communiquer avec un logiciel malveillant déjà présent ;
- rechercher des appareils ou des services vulnérables ;
- tenter d’accéder à des ressources locales insuffisamment protégées ;
- faciliter la propagation d’une infection si les protections du réseau sont insuffisantes.

➡️ Le risque ne vient pas nécessairement de la personne, mais de l’état de son appareil et de la configuration du réseau.

---

## Pourquoi configurer un Wi-Fi invité

Un réseau invité correctement configuré permet de fournir un accès à Internet tout en séparant les appareils externes du réseau principal.

Il peut notamment offrir :

- un accès limité à Internet ;
- une isolation entre les invités et les appareils internes ;
- une réduction du risque de propagation vers le réseau principal ;
- un mot de passe distinct, qui peut être changé sans modifier celui du Wi-Fi principal.

➡️ Cette protection dépend de la configuration du routeur : le réseau invité doit être isolé du réseau local et, si possible, les appareils invités doivent aussi être isolés les uns des autres.

---   

## Résumé

- Un réseau invité correctement isolé sépare les appareils externes du réseau principal.
- Il réduit les risques d’accès aux ressources internes et de propagation d’une infection.
- Un appareil compromis connecté au Wi-Fi principal augmente le risque sans compromettre automatiquement tout le réseau.
- L’efficacité de cette protection dépend de la configuration du routeur et des règles d’isolation.

---


        ┌───────────────────────────────┐
        │          ATTAQUANT            │
         (n’utilise jamais sa propre IP)│
        └───────────────────────────────┘
                     │
                     v
        ┌───────────────────────────────┐
        │Wi-Fi compromis/Hotspot public │
        │ (café, voisin, victime, 
                 lieu ouvert)           │
        └───────────────────────────────┘
                     │
                     v
        ┌───────────────────────────────┐
        │        Routeur compromis      │
        │       (appareil utilisé 
                  comme relais)         │
        └───────────────────────────────┘
                     │
                     v
        ┌───────────────────────────────┐
        │       Machine zombie          │
        │      (PC infecté / botnet)    │
        └───────────────────────────────┘
                     │
                     v
        ┌───────────────────────────────┐
        │          VPN #1               │
        │       (premier rebond)        │
        └───────────────────────────────┘
                     │
                     v
        ┌───────────────────────────────┐
        │           VPN #2              │
        │ (cascade / changement de pays)│
        └───────────────────────────────┘
                     │
                     v
        ┌───────────────────────────────┐
        │            TOR                │
        │    (multi-rebonds anonymes)   │
        └───────────────────────────────┘
                     │
                     v
        ┌───────────────────────────────┐
        │       Chaîne de proxys        │
        │(multiples relais additionnels)│
        └───────────────────────────────┘
                     │
                     v
        ┌───────────────────────────────┐
        │       SERVEUR CIBLE           │
        │    (entreprise / site attaqué)│
        └───────────────────────────────┘

        ---

🔴 L’attaquant le plus difficile à identifier est celui qui laisse le moins d’indices exploitables.

----

✍️ Auteur : *Virginie Lechene*

---

## Licence
Le script est publié sous la licence MIT.

## À propos de l’usage
Ce projet est destiné exclusivement à des fins pédagogiques, notamment dans le cadre de :
- d’une formation en cybersécurité,
- de tests d’intrusion légaux (pentest),
- d’analyses réseau dans un environnement contrôlé.

⚠️ L’auteure ne cautionne ni n’autorise l’utilisation de ce script en dehors d’un cadre légal strictement défini.
Toute utilisation non conforme est interdite et relève uniquement de la responsabilité de l’utilisateur.

## 📷 Droits sur les visuels

Les visuels de ce dépôt sont protégés par la licence CC BY-ND 4.0.
Attribution obligatoire – Modification interdite.

© 2026 Virginie Lechene





