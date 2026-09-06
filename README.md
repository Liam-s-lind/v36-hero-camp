# CSS-arv i min Hero

css-arv betyder att vissa egenskaper förs vidare från en föälder till elementen inuti den. Då slipper jag sätta samma textfärg på varje element.

1. **CSS-arv:** 
CSS-arv betyder att vissa egenskaper, som color och font-family,
förs vidare från föräldern till barnen. Däremot ärvs inte padding
och background-color, utan de stannar på elementet där de sätts.

I min Hero sätter jag textfärg och typsnitt på .hero i style.css.
Rubriken h1 och styckena .datum, .plats och .tagline har inga egna
regler för dessa egenskaper och ärver därför dem från .hero.
Om jag ändrar textfärgen på .hero följer barnens text med,
medan bakgrunden och padding fortfarande hör till förälderns låda.