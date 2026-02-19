# Site-3-pages-HTML-CSS-ONLY -- ECO'RANDO

Small project, 3 pages, using only HTML & CSS
A project to raise awaireness about forest and activities around it, to appreciate our environment and nature's beauty. 

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

#### Accueil
![Desktop-accueil](./img/preparation/Accueil-desktop.jpg)
#### Activite
![Desktop-activite](./img/preparation/Activite-desktop.jpg)
#### Ecosysteme
![Desktop-ecosysteme](./img/preparation/Ecosysteme-desktop.jpg)

### Mobile

#### Accueil
![Mobile-accueil](./img/preparation/Accueil-mobile.jpg)
#### Activite
![Mobile-activite](./img/preparation/Activite-mobile.jpg)
#### Ecosysteme
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


<hr>

## Special thanks to :
### logos : 
-   Flaticon :
    - Freepik
    - Laisa Islam

- Pixabay : 
    - Mickeylit