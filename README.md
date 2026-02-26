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

Depending on which page I'm on, href will changes

### Header (HOMEPAGE)

```
<!-- HEADER -->
<header>
    <div class="header-name-logo">
        <a href="./index.html">
        <img 
        src="./img/logo/mickeylit-ai-generated-pixabay.png" 
        alt="Logo Eco'Rando arbre générée par IA - Logo de Mickeylit - Pixabay.com" 
        class="logo header-logo">
        </a>
        <div class="name-intro">
            <h1>Eco'Rando</h1>
            <p>Plus proche de nos forêt, <br>plus proche de nous même</p>
        </div>
    </div>
    <label for="burger-menu-input">☰</label>
    <input type="checkbox" id="burger-menu-input" />
    <nav class="header-nav">
        <div class="burger-menu-items">
            <a href="./index.html" class="btn-text-white active">Accueil</a>
            <a href="./pages/activite.html" class="btn-text-white">Activités</a>
            <a href="./pages/ecosysteme.html" class="btn-text-white">Écosystème</a>
        </div>
    </nav>
</header>
```

### Footer (HOMEPAGE)

```
<!-- FOOTER -->
<footer class="footer pt-50">
    <!-- CONTACT SECTION -->
    <section class="contact">
        <h2>Contact</h2>
        <div class="phone">
            <a href="phoneto:0102030405">
                <img 
                src="./img/logo/telephone-ADI_ICONS-flaticon.png" 
                alt="Logo Téléphone - Logo de ADI_ICONS - Flaticon.com" 
                class="footer-img">
            </a>
            <a href="phoneto:0102030405" class="btn-text-white">+33 1 02 03 04 05</a>
        </div>
        <div class="email">
            <a href="mailto:faux.mail@gmail.com">
                <img 
                src="./img/logo/email-freepik-flaticon.png" 
                alt="Logo Mail - Logo de Freepik - Flaticon.com" 
                class="footer-img">
            </a>
            <a href="mailto:faux.mail@gmail.com" class="btn-text-white">faux.mail@gmail.com</a>
        </div>
        <a href="#modal-mentions-legale" class="btn-text-white">Mentions légales</a>
    </section>
    <!-- LOGO -->
    
    <a href="./index.html">
        <img 
        src="./img/logo/mickeylit-ai-generated-pixabay.png" 
        alt="Logo Eco'Rando arbre générée par IA - Logo de Mickeylit - Pixabay.com" 
        class="logo footer-logo">
    </a>
    <!-- SOCIAL MEDIA SECTION -->
    <section class="reseau">
        <h2>Réseaux sociaux</h2>
        <div class="facebook">
            <a href="https://www.facebook.com" target="_blank">
                <img 
                src="./img/logo/freepik-facebook-flaticon.png" 
                alt="Logo Facebook - Logo de Freepik - Flaticon.com" 
                class="footer-img">
            </a>
            <a href="https://www.facebook.com" target="_blank" class="btn-text-white">Eco'Rando</a>
        </div>
        <div class="instagram">
            <a href="https://www.instagram.com" target="_blank">
                <img 
                src="./img/logo/Laisa-islam-instagram-flaticon.png" 
                alt="Logo Instagram - Logo de Laisa Islam - Flaticon.com" 
                class="footer-img">
            </a>
            <a href="https://www.instagram.com" target="_blank" class="btn-text-white">@Eco_Rando</a>
        </div>
    </section>
</footer>
```

<hr>

## Homepage

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
    <!-- NORMAL ARTICLE -->
    <article class="normal px-30 py-50">
        <img 
        src="./img/logo/mickeylit-ai-generated-pixabay.png"
        alt="Logo Eco'Rando arbre générée par IA - Logo de Mickeylit - Pixabay.com" 
        class="ecosysteme-img">
        <div class="ecosysteme-text">
            <h3>Eco'Rando</h3>
            <p>
                Fondée en 2026, Eco'Rando est un rassemblement de passionnés de la nature, voués à partager et sensibiliser le plus grand nombre, en commençant avec des programmes pour les plus jeunes jusqu'aux plus anciens cherchant de nouveaux horizons. Pour ceux en capacités, des activités sportives en groupe et en plein air sont programmées régulièrement dont des randonnées, du cyclisme, etc... .
            </p>
        </div>
        <a href="./pages/activite.html" class="btn">Activités</a>
    </article>
    <!-- REVERSE ARTICLE -->
    <article class="reverse p-30 py-50">
        <div class="ecosysteme-text">
            <h3>Connaître son environnement c'est réduire son impact</h3>
            <p>
                Nous vous proposons des activités à but de découverte, de sensibilisation et d'émerveillement face à nos magnifiques forêts. Au préalable nous vous invitons à vous rendre sur notre page <a href="./pages/ecosysteme.html">Écosystème</a> dans laquelle des informations primordiales sur l'écosystème, sa<a href="./pages/ecosysteme.html#ecosysteme" class="btn-text-white underline">définition</a>, son<a href="./pages/ecosysteme.html#forest" class="btn-text-white underline">environnement</a>, sa<a href="./pages/ecosysteme.html#animals" class="btn-text-white underline">faune</a> et les<a href="./pages/ecosysteme.html#rules" class="btn-text-white underline">règles à suivre</a>. Concernant les règles un rappel sera effectué avant réservation d'une activité et avant le départ de celle-ci.
            </p>
        </div>
        <a href="./pages/ecosysteme.html" class="btn">En savoir +</a>
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

        [...] other cards

    </div>
</section>
```

<hr>

## Special thanks to :
### logos & images : 
-   [Flaticon](https://www.flaticon.com/fr/) :
    - Freepik,
    - Laisa Islam,
    - ADI_ICONS,
    - Chattapat,
    - Flat Icons,
    - Vectors,
    - Smashicon,
    - Gowi,
    - Paul J.,
    - Altop7,
    - Ayub Irawan,
    - Smalllikeart,
    - Vector Market,
    - Roundicons,

- [Pixabay](https://pixabay.com/fr/) : 
    - Mickeylit,

- [Unsplash](https://unsplash.com/fr) :
    - Josh Fotheringham,
    - Philippe Oursel,
    - Yevhenii Dubrovskyi,
    - Jorgen Hendriksen,
    - Sebastian Unrau,
    - Mark Duffel,
    - Ivan Bandura,
    - Gaurav Patil,

### video : 
- [Pixabay](https://pixabay.com/fr/) : 
    - Matthias_Groeneveld