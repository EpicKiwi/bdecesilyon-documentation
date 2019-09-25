# Documentation de la vie associative du CESI de Lyon

Bienvenue sur le repository de documentation de la vie associative du CESI de Lyon.
C'est ici que sont rédigés les documents du [Guide de la Vie Asso](https://bdecesilyon.fr/guide) mais aussi d'autres docuents relatifs au [site de la vie asso](https://bdecesilyon.fr/).

* Le dossier `guide` contiens tout les documents du Guide de la vie asso

## Structure des fichiers

La structure interne du dossier `guide` est repris tel quel à l'url [bdecesilyon.fr](https://bdecesilyon.fr/guide). Tout les fichiers Markdown dans ce dossiers sont parsés et affichés formattés sur la page associée.


```
/guide/bde/role-du-secrétaire.md
Disponible à l'adresse https://bdecesilyon.fr/guide/bde/role-du-secrétaire
```

Le document par défaut est `index.md` et sera affiché dans le cas ou l'URL pointe vers le nom du dossier

```
/guide/vie-asso/commission/index.md
Disponible à l'adresse https://bdecesilyon.fr/guide/vie-asso/commission
```

## Règles d'écriture

Ces quelques rêgles doivent être réspectés durant la rédaction pour assurer que le site puisse corrèctement parser le contenu et l'afficher corrèctement aux étudiants

1. **Toujours** débuter un document par un **titre de première importance** (débutant par #). Cela permet de donner le titre à la page.
2. Ne pas **faire de lien absolu** entre les documents. Ils ne seront plus valides sur le site. En revanche il est possible d'utiliser des chemins relatifs.
3. Les fichiers non Markdown seront servis tel quel et peuvent permettre d'héberger des images, documents, etc. 
4. L'utilisation du **HTML est autorisée** mais ne doit pas être utilisé trop souvant. cela peut perturber l'unicité du style et le bon affichage de la page.
5. Le **javascript n'est pas autorisé**.

Quelque règles à propos du ton et de la syntaxe

1. Soyez encourageant dans les démarches et les explications afin de ne jamais démotiver le lecteur.
2. Tutoyez le lecteur, c'est le ton généralement employé sur le site.
3. N'hesitez pas à illustrer vos propos avec des images, des exemples, etc.
4. Ne vous prenez pas la tête avec l'orthographe et la grammaire, plusieurs personnes passerons pour relire et corriger ce que vous écrivez.

## Contributions

Toute contribution est bienvenue !
Que ce soit pour corriger des fautes, ajouter des précisions, écrire un panphlet ou simplement répondre aux issues GitHub : Merci !
Le BDE est une association d'étudiant et nous sommes tous très occupés, tout aide est bienvenue.

Les étudiants disposent aussi d'un formulaire permettant de donner leur avis sur la page de documentation qu'ils sont en train de lire.
Le formulaire crée une issue dans ce repository.

## Modèles HTML

Les modèles suivants permettent d'ajouter plus de focntionnalités a un document.
Il est conseillé de se restreindre aux modèles suivants et de ne pas essayer d'utiliser du HTML en dehors de ces cas d'utilisation.

### Sauts

Les sauts permettent d'insèrer un espace vide dans le document.
Les tailles de chaque saut dépend du style du site et son disponible en 3 version.

Pour un grand saut

```html
<div class="bigskip"></div>
```

Pour un saut de taille moyenne

```html
<div class="mdeskip"></div>
```


Pour un petit saut

```html
<div class="smallskip"></div>
```
