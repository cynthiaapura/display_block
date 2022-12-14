# Les display-block CSS

Cours sur les display-block et inline.

[Lien vers le projet](https://capura94.github.io/display-block-22/)

>Exemple de code HTML
```html 
<div class="gallery-primary" role="group" aria-labelledby="pictures">
    <ul id="pictures">
        <li><img src="./asset/pisa.jpg" alt="ville de pise"></li>
        <li><img src="./asset/paris.jpg" alt="ville de paris"></li>
        <li><img src="./asset/newyork2.jpg" alt="ville de new york"></li>
        <li><img src="./asset/sanfran.jpg" alt="ville de los angeles"></li>
        <!-- two pictures -->
        <li><img src="./asset/newyork2.jpg" alt="ville de new york"></li>
        <li><img src="./asset/pisa.jpg" alt="ville de pise"></li>
                <!-- last image -->
        <li><img src="./asset/02.jpg" alt="ville de los angeles"></li>
    </ul>
</div>
```
>Exemple de code CSS
```css
html{
    font-size: 62.5%;
    background-color: #222;
}
body{
    font: 1.6rem "Roboto Slab", sans-serif;
    margin: 0;
    line-height: 1.6;
    letter-spacing: .1rem;
}
h1,h2,h3,h4,h5,h6,
ul,ol,p,figure{
    margin: 0;
    padding: 0;
    list-style: none;   
}
```