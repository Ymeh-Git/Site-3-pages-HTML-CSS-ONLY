# Site-3-pages-HTML-CSS-ONLY -- ECO'RANDO

Small project, 3 pages, using only HTML & CSS
A project to raise awaireness about forest and activities around it, to appreciate our environment and nature's beauty. 

Sorry for my Frenglish

We will go though this project step by step 🐌

**If you are eager to see the result, clone it or download .zip, extract it and open it in your browser**
## Tree structure :

```
~site-3-pages-HTML-CSS-ONLY
            |__css
            |    |__accueil
            |    |    |__accueil-mobile.css
            |    |    |__accueil.css
            |    |__activite
            |    |    |__activite-mobile.css
            |    |    |__activite.css
            |    |__ecosysteme
            |    |    |__ecosysteme-mobile.css
            |    |    |__ecosysteme.css
            |    |__layout
            |    |    |__footer
            |    |    |    |__footer-mobile.css
            |    |    |    |__footer.css
            |    |    |__header
            |    |         |__header-mobile.css
            |    |         |__header.css
            |    |__style.css
            |__img
            |    |__preparation
            |        |__[...]
            |    |__[...]
            |__pages
            |    |__activite.html
            |    |__ecosysteme.html
            |__index.html
            |__README.md
```

<hr>

## Wireframes

### Desktop

#### Homepage
![Desktop-accueil](./img/preparation/Accueil-desktop.jpg)
#### Activite
![Desktop-activite](./img/preparation/Activite-desktop.jpg)
#### Ecosysteme
![Desktop-ecosysteme](./img/preparation/Ecosysteme-desktop.jpg)

### Mobile

#### Homepage
![Mobile-accueil](./img/preparation/Accueil-mobile.jpg)
#### Activity
![Mobile-activite](./img/preparation/Activite-mobile.jpg)
#### Ecosystem
![Mobile-ecosystem](./img/preparation/Ecosysteme-mobile.jpg)

<hr>

## Layout

### Header

```
<header>
    <div class="header-name-logo">
        <img 
        src="./img/logo/mickeylit-ai-generated-pixabay.png" 
        alt="Logo arbre générée par IA - Logo de Mickeylit - Pixabay.com" 
        class="header-logo">
        <h1>Eco'Rando</h1>
        <p>Plus proche de nos forêt, plus proche de nous même</p>
    </div>
    <nav class="header-nav">
        <a href="./index.html" class="btn text-white active">Accueil</a>
        <a href="./pages/activite.html" class="btn text-white">Actvités</a>
        <a href="./pages/ecosysteme.html" class="btn text-white">Écosystème</a>
    </nav>
</header>
```

### Footer

```
<footer class="flex-row-space-between">
    <section class="contact flex-row-space-between">
        <h2>Contact</h2>
        <div class="phone">
            <img 
            src="./img/logo/telephone-ADI_ICONS-flaticon.png" 
            alt="Logo Téléphone - Logo de ADI_ICONS - Flaticon.com" 
            class="footer-img">
            <a href="phoneto:0102030405" class="btn btn-text-white">+33 1 02 03 04 05</a>
        </div>
        <div class="email flex-row-space-between">
            <img 
            src="./img/logo/email-freepik-flaticon.png" 
            alt="Logo Mail - Logo de Freepik - Flaticon.com" 
            class="footer-img">
            <a href="mailto:faux.mail@gmail.com" class="btn btn-text-white">faux.mail@gmail.com</a>
        </div>
        <a href="#modal-mentions-légale" class="btn">Mentions légales</a>
    </section>
    <img 
    src="./img/logo/mickeylit-ai-generated-pixabay.png" 
    alt="Logo Eco'Rando arbre générée par IA - Logo de Mickeylit - Pixabay.com" 
    class="logo footer-logo">
    <section class="reseau">
        <h2>Réseaux sociaux</h2>
        <div class="facebook flex-row-space-between">
            <img 
            src="./img/logo/freepik-facebook-flaticon.png" 
            alt="Logo Facebook - Logo de Freepik - Flaticon.com" 
            class="footer-img">
            <a href="https://www.facebook.com" class="btn btn-text-white">Eco'Rando</a>
        </div>
        <div class="instagram flex-row-space-between">
            <img 
            src="./img/logo/Laisa-islam-instagram-flaticon.png" 
            alt="Logo Instagram - Logo de Laisa Islam - Flaticon.com" 
            class="footer-img">
            <a href="https://www.instagram.com" class="btn btn-text-white">@Eco_Rando</a>
        </div>
    </section>
</footer>
```

<hr>

## Accueil

### Hero section

Between \<header> and \<main>

```
<section class="hero">
    <video src="" class="background-hero"></video>
    <img 
    src="./img/logo/mickeylit-ai-generated-pixabay.png" 
    alt="Logo arbre générée par IA - Logo de Mickeylit - Pixabay.com" 
    class="logo hero-logo">
    <h2 class="name">ECO'RANDO</h2>
    <p class="intro">La préservation des forêts est notre priorité, profitez gratuitement d'activités physique en groupe le tout en vous instruisant et sensibilisant à la protection de nos forêts, commencez l'aventure !</p>
</section>
```

After that all will be in \<main>

### Ecosystem section

```
<section class="ecosysteme">
    <h2 class="section-title">Notre écosystème</h2>
    <!-- PRESENTATION ARTICLE -->
    <article class="flex-row">
        <img 
        src="./img/logo/mickeylit-ai-generated-pixabay.png"
        alt="Logo Eco'Rando arbre générée par IA - Logo de Mickeylit - Pixabay.com" 
        class="logo ecosysteme-img">
        <div class="ecosysteme-text">
            <h3>Eco'Rando</h3>
            <p>
                Fondée en 2026, Eco'Rando est un rassemblement de passionnés de la nature, voués à partager et sensibiliser le plus grand nombre, en commençant avec des programmes pour les plus jeunes jusqu'aux plus anciens cherchant de nouveaux horizons. Pour ceux en capacités des activités sportives en plein air dont randonnées abordées sous un autre angle.
            </p>
            <div class="flex-end">
                <a href="#modal-eco-rando" class="btn btn-full">En savoir plus</a>
            </div>
        </div>
        <div class="emptiness-equal-to-ecosysteme-img"></div>
    </article>
    <!-- REVERSE ARTICLE -->
    <article class="flex-row-reverse">
        <img 
        src=""
        alt="" 
        class="ecosysteme-img">
        <div class="ecosysteme-text">
            <h3>Titre</h3>
            <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Incidunt reiciendis id unde ipsa? Non sit repellendus, facere excepturi ad corrupti tenetur voluptatum at, quo, molestiae deleniti tempora reprehenderit praesentium? Id.
            </p>
            <div class="flex-end">
                <a href="#modal-eco-rando" class="btn btn-full">En savoir plus</a>
            </div>
        </div>
        <div class="emptiness-equal-to-ecosysteme-img"></div>
    </article>
    <!-- NORMAL ARTICLE -->
    <article class="flex-row">
        <img 
        src=""
        alt="" 
        class="ecosysteme-img">
        <div class="ecosysteme-text">
            <h3>Titre</h3>
            <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Incidunt reiciendis id unde ipsa? Non sit repellendus, facere excepturi ad corrupti tenetur voluptatum at, quo, molestiae deleniti tempora reprehenderit praesentium? Id.
            </p>
            <div class="flex-end">
                <a href="#modal-eco-rando" class="btn btn-full">En savoir plus</a>
            </div>
        </div>
        <div class="emptiness-equal-to-ecosysteme-img"></div>
    </article>
    <!-- REVERSE ARTICLE -->
    <article class="flex-row-reverse">
        <img 
        src=""
        alt="" 
        class="ecosysteme-img">
        <div class="ecosysteme-text">
            <h3>Titre</h3>
            <p>
                Lorem, ipsum dolor sit amet consectetur adipisicing elit. Incidunt reiciendis id unde ipsa? Non sit repellendus, facere excepturi ad corrupti tenetur voluptatum at, quo, molestiae deleniti tempora reprehenderit praesentium? Id.
            </p>
            <div class="flex-end">
                <a href="#modal-eco-rando" class="btn btn-full">En savoir plus</a>
            </div>
        </div>
        <div class="emptiness-equal-to-ecosysteme-img"></div>
    </article>
</section>
```

### Activity section

```
<section class="activite flex-column-center-center">
    <h2 class="section-title">Activités</h2>
    <nav class="cards-container">
        <!-- CARD RANDO -->
        <a href="./pages/activite.html#rando" class="card">
            <div class="card-content">
                <img 
                src="./img/randonnee-yevhenii-dubrovskyi--unsplash.jpg" 
                alt="Trois personnes sur un chemin pentu en randonnée dans une forêt - Image de Yevhenii Dubrovskyi - Unsplash.com" 
                class="card-background-img">
                <h3 class="card-title">Randonnées</h3>
            </div>
        </a>
        <!-- CARD KAYAK -->
        <a href="./pages/activite.html#kayak" class="card">
            <div class="card-content">
                <img 
                src="./img/kayak-philippe-oursel-Oer7jCMqZtk-unsplash.jpg" 
                alt="Deux personnes faisant du kayak sur une rivière au centre d'une forêt - Image de Philippe Oursel - Unsplash.com" 
                class="card-background-img">
                <h3 class="card-title">Kayak</h3>
            </div>
        </a>
        <!-- CARD KAYAK -->
        <a href="./pages/activite.html#kayak" class="card">
            <div class="card-content">
                <img 
                src="./img/canyoning-josh-fotheringham-GwRlyykKg-M-unsplash.jpg" 
                alt="Deux personnes marchant dans une rivière en équipement de canyoning - Image de Josh Fotheringham - Unsplash.com" 
                class="card-background-img">
                <h3 class="card-title">Canyoning</h3>
            </div>
        </a>
        <!-- CARD CYCLING -->
        <a href="./pages/activite.html#velo" class="card">
            <div class="card-content">
                <img 
                src="./img/velo-jorgen-hendriksen-xu2pJBFTW-M-unsplash.jpg" 
                alt="Une personne faisant du vélo au sein d'une forêt d'automne - Image de Jorgen Hendriksen - Unsplash.com" 
                class="card-background-img">
                <h3 class="card-title">Vélo</h3>
            </div>
        </a>
    </div>
</section>
```

<hr>

##

## Special thanks to :
### logos : 
-   [Flaticon](https://www.flaticon.com/fr/) :
    - Freepik,
    - Laisa Islam,
    - ADI_ICONS,

- [Pixabay](https://pixabay.com/fr/) : 
    - Mickeylit,

- [Unsplash](https://unsplash.com/fr) :
    - Josh Fotheringham,
    - Philippe Oursel,
    - Yevhenii Dubrovskyi,
    - Jorgen Hendriksen,