---
layout: post
title:  "Explicacio Projecte Final"
description: Explicació del meu projecte de final de curs.
---
Aquesta pàgina web el seu principal objectiu serà facilitar el treball dels treballadors d'un desguàs ajudant-los a portar l'inventari de cotxes facilitant-los també el saber quines mateixes peces d'aquell cotxe són les que estan disponibles i el preu «estàndard» (preu per el qual es sol vendre la peça) per així tindre una referencia, per últim estaria bé implementar una llista de tasques personalitzades per cada un dels treballadors intentant utilitzar el sistema LEAN.
La idea és que hi hagui 3 rols d’usuaris:

  * admin : Usuari que tindrà permisos per realitzar qualsevol mena d'acció, edició de l'inventari de cotxes i peces, igual que el de la taula de tasques i també afegir o eliminar usuaris.
Bàsicament aquest usuari el tindrà el cap del desguàs

  * office : Aquest és semblant l'admin però aquest només podrà dur a terme l'edició de l'inventari de cotxes i peces, igual que el de la taula de tasques. Aquest usuari serà pel treballador o treballadors que treballin a l'oficina els quals s'encarregaran de l'entrada i donada de baixa de vehicles dins del desguàs igual que s'encarregarà de les ventes als clients, per tant hauran d'editar la taula de tasques per dir per exemple necessiten tindre una peça preparada per un dia en concret.

  * worker : Usuari el qual només podrà accedir a l'inventari de peces sense cap mena de control d'edició només podrà veure'l i també podrà editar en les tasques quina tasca a fet i quina està fent. Aquest rol està fet pels treballadors els quals són els encarregats de desmuntar i descontaminar els cotxes, per tant el principal treballador pel qual aniran ambientada les tasques de la taula, que també haurà de comunicar quan hagi realitzat, comenci una tasca, etc.

# Materials els quals tinc pensat utilitzar:
  * SQL per la base de dades.
  * Per la part de programació utilitzaré Java (IDE NetBeans o Eclipse) i faré test a la base de dades i/o pàgina web.
  * Servidor serà Apache i pels mateixos dominis utilitzaré BIND.
  * El projecte a l'estar ambientat en gestió d'un inventari i tasques he pensat que seria millor fer el projecte en Laravel (així tinc la part de M07) i per la part de M06 i M09 tinc pensat utilitzar en les vistes del Laravel Javascript, Jquery o DOM, CSS, Bootstrap i/o AJAX.

# Conclusions
Al tindre la meva família un desguàs potser alguna d'aquestes coses proposades poden arribar a canviar amb el fi d'intentar adaptar el projecte a les necessitats que es creuen o proposin les persones que treballen en aquest sector i que per les quals va dirigida la web.
