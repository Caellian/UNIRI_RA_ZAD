# Popis likova

## Mudrac

![prikaz mudraca](./likovi/mudrac.svg)

Mudrac je dobrotvoran lik koji nastoji uvesti red u kaos.

Lik s nepoznatom prošlošću - pretpostavlja se da je izučavao matematiku od samog
Alonza Churcha zbog specijalizacije, no pojavljuje se u povijesnim knjigama od
prije 1556 god. PK, tako da je moguće da Alonzo nije bio njegov prvi mentor.

Mladolikog je izgleda iako je zapravo iznimno star.

## Brojevi

Definirani Churchevom notacijom za brojeve:

- 0 - λfx.x
- 1 - λfx.f(x)
- 2 - λfx.f(f(x))
- 3 - λfx.f(f(f(x)))

Generalno:

<math xmlns="http://www.w3.org/1998/Math/MathML"><msup><mi>f</mi><mrow><mo>&#x2218;</mo><mi>n</mi></mrow></msup><mo>=</mo><munder accentunder='false'><munder accentunder='true'><mrow><mi>f</mi><mo>&#x2218;</mo><mi>f</mi><mo>&#x2218;</mo><mo>&#x22ef;</mo><mo>&#x2218;</mo><mi>f</mi></mrow><mo>&#x23df;</mo></munder><mrow><mi>n</mi><mo>&#xA0;</mo><mi>s</mi><mi>t</mi><mi>a</mi><mi>v</mi><mi>k</mi><mi>i</mi></mrow></munder></math>

<sub>Ako prikaz formule ne radi, vratite se za 20-40 godina kada preglednici napokon budu podržavali osnovnu MathML specifikaciju.</sub>

## Kombinatori

### Ida - λx.x

![prikaz ide](./likovi/kombinator.svg)

Predstavlja funkciju identitete koja vraća argument koji joj je dan.

### Apu - λfx.f(x)

Predstavlja aplikator - funkciju koja uzima kao argument drugu funkciju i
vrijednost te primjeni dobivenu funkciju na danu vrijednost.

### **Da**do - λab.a

Prestavlja logičku istinu.

### **Ne**do - λab.b

Prestavlja logičku laž.

### Sudac - λpab.pab

Uzima sud `p`, ako je istinit, vraća `a`, inače `b`.

### Drugi

Navedeno je nekoliko primjera, nije odlučeno kakav će biti konačan izraz na
zadnjoj sceni te je zbog toga nemoguće navesti sve likove. Prethodni su navedeni
kao primjeri.

Konačan izraz će biti neki jednostavan primjer, a koristimo [Eric Breyer - An
Introduction to the Lambda Calculus, Church Encodings, and the Y
Combinator](https://www.ericbreyer.com/static/introtolc.pdf) za pronalaženje
prikladnih kombinatora za kod koji nam je blizak.
