Ustanavlivaem zaranee node.js
Odin raz ustanavlivaem Jest framework npminstall --save-dev jest, posle cego on ustanavlivaetsa, i bolshe ne nado bivaet eto delat.
Sozdaem papku
Otkrivaem terminal, inicialiiruem proekt npm init, proxodim po voprosam, "test- jest", ukazivaem ssilku na repozitoriy, sozdanniy zranee, avtora najimaem OK
Poluchaem package.json s zapolnennimi polami, kotorie mojno izmenat
Dla testov:
Sozdaem file.js. Zapisivaem funkciyu i eksportiruem- module.exports = sum;
Sozdaem sleduyuwiy file s nazvaniem test.js v kotoriy importiruem exportiruemiy put- const sum = require("./file.js")
S pomowyu komandi npm run test v terminale zapuskaem testi s rezultatom Passed/Failed

