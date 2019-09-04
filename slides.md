# ![](demos/img/zenika.png)<!-- .element: style="height:1em; vertical-align: -0.28em; border: none; background: none;" --> No JS Games

---

## Pas de JavaScript

Seulement du HTML, du CSS et du SVG

<iframe src="https://codepen.io/jcoulterdesign/full/NOMeEb"></iframe>

---

## De quoi a-t-on besoin <br>pour faire un jeu ?

Dans sa dimension la plus fondamental, <br>un jeu vidéo est un **état** <br>avec lequel on **interagit**, <br>le tout étant habituellement **restitué visuellement**.


## Maintenir un état

 - <!-- .element: class="fragment" --> <code>&lt;input type="checkbox"&gt;</code>
 - <!-- .element: class="fragment" --> <code>&lt;input type="radio"&gt;</code>


## Interagir avec un état

- <!-- .element: class="fragment" --> <code>&lt;label for=""&gt;</code>


## Connecter l'état et le design

- <!-- .element: class="fragment" --> La pseudo-classe <code>:checked</code>
- <!-- .element: class="fragment" --> Le sélecteur combinatoire <code>~</code> (ET)
- <!-- .element: class="fragment" --> Le séparateur de sélecteur <code>,</code> (OU)
- <!-- .element: class="fragment" --> La pseudo-classe <code>:not()</code>


## Une p'tite démo "simple"

<iframe src="demos/taquin.html"></iframe>

---

## Est-ce qu'on peut faire mieux ?

- Plusieurs sources de modification ? <!-- .element: class="fragment" -->
- Interaction temporel ? <!-- .element: class="fragment" -->
- Interaction au clavier ? <!-- .element: class="fragment" -->


## Oui ! Merci SVG.

- <!-- .element: class="fragment" --> 😁 <code>&lt;set begin="{ID}.click"&gt;</code>
- <!-- .element: class="fragment" --> 😁 <code>&lt;set begin="{ID}.end"&gt;</code>
- <!-- .element: class="fragment" --> 🤔 <code>&lt;set begin="2s"&gt;</code>
- <!-- .element: class="fragment" --> 🤩 <code>&lt;set begin="{ID}.{event}+{time}"&gt;</code>
- <!-- .element: class="fragment" --> 🤔 <del><code>&lt;set begin="accessKey(a)"&gt;</code></del> vs HTML <code>accesskey</code>


## Une autre p'tite démo

<iframe src="demos/advanced.html"></iframe>

---

## Conclusion

- Peut-on faire des jeux sans JS ? **[OUI !](https://accodeing.com/blog/2015/css3-proven-to-be-turing-complete)** <!-- .element: class="fragment" -->
- Est-ce que c'est une bonne idée ? **NON !** <!-- .element: class="fragment" -->


# Merci
## 🤯😘❤️🌈🦄
