T'n'T Gym Ljubljana
Spletna stran kluba T'n'T Gym Ljubljana v Črnučah. Vključuje predstavitev programov in trenerjev, urnik, cenik ter obrazec za prijavo na prvi trening.

Tehnologije in gostovanje
Stran uporablja HTML, CSS in JavaScript, brez ogrodja in brez koraka za gradnjo (build). Namenjena je objavi na obstoječem statičnem gostovanju z nginx.

Obrazec trenutno uporablja Formspree. Za njegovo delovanje ni potreben lasten backend. Pred objavo je treba preveriti nastavitve obrazca in prejemnika sporočil.

Struktura
index.html - glavna stran
bjj.html, mma.html, boks.html, kickbox.html, otroci.html - programi
urnik.html - urnik treningov
cenik.html - članarine
trenerji.html - predstavitev trenerjev
kontakt.html - kontaktni podatki in prijavni obrazec
css/style.css - slogi
js/main.js - navigacija, obrazec in druga interaktivnost
js/schedule-data.js - podatki za urnik
assets/images/ - fotografije in grafike
Lokalni ogled
Projekt odprite v VS Code in zaženite index.html z razširitvijo Live Server ali drugim lokalnim statičnim strežnikom.

Posodabljanje vsebine
Urnik
Termini so zapisani v js/schedule-data.js. Tam se urejajo dnevi, ure, programi, trenerji in drugi podatki o treningih.

Besedila in cene
Besedila se urejajo neposredno v pripadajočih HTML datotekah. Cenik je v cenik.html, predstavitve trenerjev pa v trenerji.html.

Če se isti podatek pojavi na več straneh, ga je treba posodobiti povsod.

Fotografije
Fotografije so v assets/images/. Ob spremembi imena ali vrste datoteke je treba popraviti tudi pripadajoče poti v HTML oziroma CSS datotekah.

Objava
Na gostovanje se prenesejo HTML datoteke ter mape css/, js/ in assets/. Datoteka index.html mora biti v korenski mapi spletnega mesta.

Pred zamenjavo obstoječe strani:

naredite varnostno kopijo trenutne različice;
potrdite vsebino in dogovorite termin objave;
preverite nastavitve ter prejemnika prijavnega obrazca.
Po objavi preverite:

povezave, fotografije in prikaz na telefonu;
urnik in cenik;
pošiljanje obrazca in prejem obvestila;
delovanje strani prek HTTPS.
