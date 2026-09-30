==========================================================================
                      README & RAPPORT DE QUALITÉ
==========================================================================
Projet : Portfolio Personnel Éco-conçu
Étudiante : Anny Muende
Semaine : 6 - Projet Final

--------------------------------------------------------------------------
1. INSTRUCTIONS D'INSTALLATION ET EXÉCUTION
--------------------------------------------------------------------------
- Pour voir le site en local : 
  Entrez dans le dossier "site/", puis double-cliquez sur le fichier "index.html". Le site s'ouvrira directement dans votre navigateur web habituel.
- Pour consulter le prototype interactif : 
  Ouvrez le dossier "figma/" et lisez le fichier "lien_figma.txt".

--------------------------------------------------------------------------
2. MINI-RAPPORT : LES 8 AMÉLIORATIONS QUALITÉ ET ÉCOCONCEPTION
--------------------------------------------------------------------------
Conformément aux exigences du sujet, voici la documentation des 8 améliorations techniques intégrées au projet, réparties en trois piliers :

THÈME A : ACCESSIBILITÉ (a11y)
1. HTML5 Sémantique : Utilisation stricte des balises structurelles (<header>, <nav>, <main>, <section>, <article>, <footer>) assurant une lecture logique et propre par les technologies d'assistance (lecteurs d'écran).
2. Navigation au clavier fluide : Tous les liens interactifs de la barre de navigation possèdent des états distinctifs ":focus" en CSS, permettant une navigation séquentielle parfaite à l'aide de la touche TAB.
3. Formulaire robuste et accessible : Chaque champ du formulaire (<input> et <textarea>) est explicitement lié à son étiquette textuelle via des attributs "id" et "for". Aucun placeholder n'est utilisé seul comme étiquette.

THÈME B : PERFORMANCE EXTRÊME & ÉCOCONCEPTION
4. Frugalité typographique : Utilisation exclusive des polices système standard (Arial, Helvetica) déclarées en CSS natif. Le poids des fichiers de police téléchargés sur le réseau est strictement égal à 0 ko.
5. Gestion responsable du JavaScript : Le script de validation est placé tout en bas du document HTML, juste avant la fermeture de </body>, évitant ainsi le blocage du rendu visuel lors du chargement.
6. Design sobre et durable (Green IT) : Palette de couleurs bicolore à fort contraste (fond blanc pur, texte noir profond #1a1a1a). Absence totale d'images d'arrière-plan lourdes, réduisant la consommation électrique de l'écran de l'utilisateur.

THÈME C : ROBUSTESSE & FIABILITÉ TECHNIQUE (JavaScript)
7. Interception de sécurité (preventDefault) : Le script JavaScript bloque le rechargement forcé de la page lors de la soumission du formulaire, assurant une expérience utilisateur stable de type Single Page Application (SPA).
8. Validation et nettoyage des données : Utilisation de la méthode ".trim()" pour éliminer les espaces superflus et application d'une expression régulière (RegEx) stricte pour vérifier la validité syntaxique de l'adresse e-mail avant tout envoi fictif.

==========================================================================