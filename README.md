# adidas — Pàgina Web amb Bootstrap, SCSS i Accessibilitat WAI-ARIA

Aquest projecte consisteix en una pàgina web promocional de l'empresa Adidas, desenvolupada amb HTML5, Bootstrap 5.3, SCSS i bones pràctiques d'accessibilitat utilitzant atributs WAI-ARIA. El disseny és responsiu i inclou diverses seccions com serveis, testimonis, preguntes freqüents (FAQ) i un formulari de contacte.

## Índex

- [Característiques](#característiques)
- [Tecnologies utilitzades](#tecnologies-utilitzades)
- [Accessibilitat](#accessibilitat)
- [Instal·lació](#instal·lació)

## Característiques

- Navegació responsiva amb barra superior col·lapsable.
- Carrusel d’imatges principal amb etiquetatge accessible.
- Secció de serveis amb targetes informatives.
- Testimonis en format de bloc de cites.
- FAQ implementat amb l'accordion de Bootstrap i etiquetatge WAI-ARIA.
- Formulari de contacte amb camps bàsics.
- Peu de pàgina amb enllaços a xarxes socials.
- Disseny adaptat a dispositius mòbils.

## Tecnologies utilitzades

- HTML5
- Bootstrap 5.3 (via CDN)
- SCSS personalitzat
- Font Awesome 6.5 per icones socials
- JavaScript per funcionalitats del Bootstrap

## Accessibilitat

El projecte fa ús dels atributs WAI-ARIA per garantir una millor experiència per a usuaris amb discapacitats. S’han aplicat etiquetes com `aria-label`, `aria-labelledby`, `aria-controls`, `aria-expanded`, entre d'altres. Totes les regions tenen un rol semàntic definit (`navigation`, `region`, `contentinfo`, `form`, etc.).

## Instal·lació

1. Clona aquest repositori:

   ```bash
   git clone https://github.com/EduardAltes/widgets.git
   cd widgets

   npm install

