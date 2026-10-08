# Jonathan Youssef

**Administrateur systèmes, réseaux et sécurité**

Linux et Windows Server · Active Directory · Réseau · Sécurité des infrastructures

[LinkedIn](https://www.linkedin.com/in/jonathan-youssef-0501ba14a) · [Consulter mon CV](https://github.com/joyou78/joyou78/blob/main/CV_Jonathan_Youssef.pdf) · [Me contacter](mailto:y.jonathan2402@gmail.com)

## Mon parcours

Mon parcours associe plusieurs années de support technique chez Centrapel et Protelco à une reconversion en administration systèmes, réseaux et sécurité.

Le diagnostic d'incidents de connectivité, l'assistance aux utilisateurs et la gestion des situations critiques m'ont donné une approche concrète de la disponibilité des services. Mes projets de formation prolongent cette expérience par la conception d'infrastructures, l'administration Windows/Linux et l'analyse des risques de sécurité.

Ce portfolio présente des **projets de formation et des études de cas**, avec leurs rapports, leurs choix techniques et leurs limites. Je m'attache à expliquer ce qui a été testé, ce qui a été conçu et ce qui reste à valider.

## Compétences et domaines travaillés

| Domaine | Technologies et sujets |
| --- | --- |
| **Systèmes** | Windows Server, Active Directory, DNS, DHCP, GPO, Debian, Ubuntu, services web Apache/Nginx |
| **Réseau** | TCP/IP, adressage, VLAN, routage, VPN IPsec, pfSense, Cisco Packet Tracer, Wireshark |
| **Scripting** | PowerShell, Bash, documentation des procédures d'administration |
| **Audit de sécurité** | Nmap, CrackMapExec, enum4linux, ldapdomaindump, Impacket, Mimikatz, Rubeus |
| **Exploitation** | Diagnostic d'incidents, GLPI, supervision, sauvegardes et préparation de la reprise d'activité |
| **Architecture et durcissement étudiés** | IaaS/PaaS, OVHcloud, répartition de charge, haute disponibilité, segmentation, LAPS, gMSA, MFA et protection des comptes à privilèges |

Les technologies d'architecture et de durcissement sont présentées dans les projets avec leur statut : solution étudiée, recommandation ou résultat documenté.

## Projets à découvrir

### 1. Audit de sécurité Active Directory

**Pentest interne et plan de remédiation — novembre 2025**

Étude d'un domaine Windows dans un scénario de clinique, avec un contrôleur de domaine, un serveur de fichiers et un poste utilisateur.

- **Travail réalisé :** reconnaissance réseau, analyse des identifiants et des permissions, tests de mouvement latéral et rédaction d'un rapport de pentest.
- **Résultats documentés :** 11 constats de sécurité et un chemin de compromission jusqu'aux privilèges Domain Admin.
- **Remédiation proposée :** 20 recommandations hiérarchisées, portant notamment sur les secrets exposés, les permissions, LAPS et la protection des comptes à privilèges.
- **Compétences mises en évidence :** audit AD, analyse de risques, priorisation et restitution à une DSI.

Le dépôt publie les résultats de l'audit et les recommandations. La mise en œuvre des corrections et leur validation par contre-audit restent à documenter.

[Explorer le dépôt](https://github.com/joyou78/Projet-Audit-Active-Directory) · [Rapport de pentest](https://github.com/joyou78/Projet-Audit-Active-Directory/blob/main/Youssef_Jonathan_1_rapport_pentest_112025.pdf) · [Plan d'action](https://github.com/joyou78/Projet-Audit-Active-Directory/blob/main/Youssef_Jonathan_2_plan_action_112025.pdf) · [Restitution](https://github.com/joyou78/Projet-Audit-Active-Directory/blob/main/Youssef_Jonathan_3_restitution_112025.pptx)

### 2. Préparation d'une migration cloud

**Application Patronus : veille, architecture et plan de migration — octobre 2025**

Étude de migration d'une application reposant sur Apache, MySQL et un stockage CIFS/SMB, dans le scénario Nimbus Corp.

- **Travail réalisé :** comparaison des fournisseurs, analyse des points de défaillance, conception de la cible et préparation de la migration.
- **Cible proposée :** instances web derrière un répartiteur de charge, base MySQL managée et stockage partagé, avec des objectifs de disponibilité et de scalabilité.
- **Dossier produit :** stratégie de replatforming, analyse des risques, phases de migration, estimation des ressources et du budget.
- **Compétences mises en évidence :** architecture cloud, comparaison IaaS/PaaS, arbitrages techniques et planification.

OVHcloud est le fournisseur retenu dans l'étude. Le dépôt présente une préparation de migration ; les performances, la disponibilité et les coûts en exploitation restent à valider par un déploiement et des tests.

[Explorer le dépôt](https://github.com/joyou78/Projet-Migration-Cloud) · [Veille technologique](https://github.com/joyou78/Projet-Migration-Cloud/blob/main/Youssef_Jonathan_1_resultat-veille_102025.pdf) · [Dossier de migration](https://github.com/joyou78/Projet-Migration-Cloud/blob/main/Youssef_Jonathan_2_migration_Patronus_102025.pdf) · [Présentation](https://github.com/joyou78/Projet-Migration-Cloud/blob/main/Youssef_Jonathan_3_diaporama_102025.pdf)

### 3. Conception d'un réseau sécurisé

**Segmentation et recommandations ANSSI — septembre 2025**

Proposition d'évolution du réseau du département R&D d'Open Pharma, avec une enveloppe budgétaire de 10 000 € HT dans le scénario.

- **Travail réalisé :** cartographie de la cible, choix des mesures de sécurité, chiffrage prévisionnel et documentation des usages.
- **Architecture proposée :** VLAN par zone et par usage, DMZ, reverse proxy, bastion et séparation de l'administration.
- **Mesures étudiées :** Fortinet FortiGate 60F, VPN IPsec avec MFA, RADIUS/802.1X, sauvegardes, journalisation et supervision.
- **Compétences mises en évidence :** conception réseau, sécurité des accès, préparation de l'exploitation et communication aux utilisateurs.

Le dépôt contient un dossier de conception fondé sur des recommandations de sécurité. La référence à l'ANSSI ne constitue pas une certification ni une validation de conformité.

[Explorer le dépôt](https://github.com/joyou78/Projet-Securisation-Reseau-ANSSI) · [Cartographie](https://github.com/joyou78/Projet-Securisation-Reseau-ANSSI/blob/main/Youssef_Jonathan_1_cartographie_092025.pdf) · [Plan projet](https://github.com/joyou78/Projet-Securisation-Reseau-ANSSI/blob/main/Youssef_Jonathan_2_plan_projet_092025.docx.pdf) · [Documentation](https://github.com/joyou78/Projet-Securisation-Reseau-ANSSI/blob/main/Youssef_Jonathan_3_documentation_092025.pdf)

## Autres sujets abordés dans mon parcours

- Services Windows et Linux : annuaire, résolution DNS, stratégies de groupe et hébergement web.
- Réseaux locaux et interconnexion de sites : adressage, segmentation et VPN IPsec.
- Exploitation : gestion de parc, ticketing, supervision, sauvegardes et restauration.
- Documentation : schémas d'architecture, procédures techniques et supports de restitution.

## Mon approche

**Diagnostiquer, sécuriser et documenter.** Je relie les choix techniques aux besoins des utilisateurs, aux contraintes d'exploitation et aux risques identifiés. Une configuration doit pouvoir être comprise, maintenue et transmise à l'équipe.

## Contact et opportunités

Je souhaite contribuer à des missions d'**administration systèmes et réseaux**, de **sécurisation des infrastructures** et d'**exploitation**, avec une évolution vers l'automatisation et le cloud.

- [LinkedIn](https://www.linkedin.com/in/jonathan-youssef-0501ba14a)
- [y.jonathan2402@gmail.com](mailto:y.jonathan2402@gmail.com)
- [CV au format PDF](https://github.com/joyou78/joyou78/blob/main/CV_Jonathan_Youssef.pdf)
