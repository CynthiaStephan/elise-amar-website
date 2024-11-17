# Elise Amar - Psychologue  

Ce projet à été réalisé dans le cadre de ma formation Front-End à l'IMTS, il consiste à la création d'un site web statique pour présenter le cabinet de la psychologue Elisa Amar


<a href="https://www.figma.com/design/cKNEiqm5wlN7iL7hcSPBRm/Psychologue_FrontEnd?node-id=0-1&t=reqt9Kl52JCiTTwD-1" target="_blank" style="display: inline-block; padding: 6px 16px; background-color: #8EC4CB; color: #1B1B1B; font-weight:500; text-decoration: none; border-radius: 4px; font-size: 16px; cursor: pointer;">
  Voir la maquette ⬈
</a>
<a href="https://cynthia.errhub404.fr/elise-psychologue/" target="_blank" style="display: inline-block; padding: 6px 16px; background-color: #BAC25F; color: #1B1B1B; font-weight:500; text-decoration: none; border-radius: 4px; font-size: 16px; cursor: pointer;">
  Voir le site ⬈
</a>



## Contexte du projet  
Le projet a été réalisé en deux étapes principales :  
1. **Maquettage** : Conception des pages en respectant les principes d’ergonomie, de lisibilité, et de cohérence graphique.  
2. **Intégration** : Développement du site en HTML5 et CSS3 en respectant la maquette établie.  

## Technologies utilisées  
- **HTML5** : Pour la structure des pages en intégrant les principes de l'accéssibilité.  
- **CSS3** : Pour la mise en page et le design responsive en utilisant Flexbox.  
- **Google Maps** : Intégration des cartes pour la page de contact à l'aide des ```<iframe>```.  

## Processus de conception  

### Étape 1 : Maquettage  
- **Benchmark** : Analyse des sites similaires pour identifier les meilleures pratiques.
- **Wireframe** : Création d’un plan structuré du site pour définir l’agencement des éléments.
- **Design** : Réalisation de la maquette sur Figma avec des couleurs pastelles et un design épuré, en accord avec la demande pour un site  rassurant et accueillant.
- **Adaptation technique** : La maquette a été conçue en prenant en compte son intégration future par mes camarades de formation. J’ai organisé le design sur Figma pour qu’il corresponde à une structure CSS basée sur le flexbox, facilitant ainsi le processus d’intégration. 


### Étape 2 : Intégration  
- Traduction de la maquette en code, avec attention particulière à la structure, à l'accessibilité et à l’expérience utilisateur.  
- Utilisation de CSS responsive pour garantir un rendu optimal sur tous types d’appareils.  

## Structure du site  

### Pages principales  
1. **Accueil** : Présentation générale et CTA pour les rendez-vous via Doctolib.  
2. **Qui suis-je ?** : Informations sur le parcours et les engagements d’Elise Amar.  
3. **Pour qui ?** : Description des types de thérapies (individuelles, familiales, etc.).  
4. **Le cabinet** : Informations pratiques (adresse, horaires, accessibilité).  
5. **Blog** : Articles récents avec affichage en grille et sidebar pour les catégories.  
6. **Contact** : Formulaire sécurisé, cartes des cabinets et coordonnées.  

### Footer  
- Liens vers les mentions légales.  
- Affichage des numéros SIRET et ADELI.  

## Identité visuelle  

### Palette de couleurs  
- **#8ec4cb** : Bleu clair.  
- **#2d5194** : Bleu profond.  
- **#bac25f** : Vert clair.  
- **#53adac** : Bleu-vert.  

### Images  
Les photographies sont issues de la banques d’images libres de droits [Pexels](https://www.pexels.com/).

## Fonctionnalités principales  
- **Réservation via Doctolib** : Intégration d’un bouton Doctolib.  
- **Responsive Design** : Compatibilité avec les écrans de toutes tailles.  
- **Navigation fluide** : Liens internes entre les pages pour une meilleure expérience utilisateur.  

## Installation et utilisation  

### Étapes  
1. Clonez ce dépôt à l’aide de la commande suivante :  
   ```bash  
   git clone https://github.com/CynthiaStephan/elise-amar-website.git  
   ```  

## Arborescence du projet  
```plaintext  
elise-amar-website/  
│  
├── index.html              # Page d'accueil  
├── Qui suis je ?
|   └── therapie.html.html
|   └── engagements.html
|   └── parcours.html
├── Pour qui ?
|   └── adolescent.html
|   └── individuelles.html
|   └── conjugales.html
|   └── familiales.html
├── cabinet.html
├── blog.html
|   └── articles.html
├── contact.html
│  
├── css/  
│   └── styles.css
│  
└── images/
```  
