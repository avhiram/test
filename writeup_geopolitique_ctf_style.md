
# 📝 Writeup – Challenge OSINT : Casamance Investigation  
**Morad Halmi – Ecole2600 – CTF OSINT**

---

## 🌍 Étape 1 – Identifier la région

On commence par le mot-clé principal : **Casamance**.  
Une recherche rapide sur Wikipedia :  
👉 https://fr.wikipedia.org/wiki/Casamance  

Nous apprend qu’il s’agit d’une région située au **sud du Sénégal**, connue pour ses tensions séparatistes depuis plusieurs années. Ok, première brique en place.

---

## 🏟️ Étape 2 – Trouver la date via le match

Dans l’énoncé, on nous parle de la “qualification des Reds contre I Giallorossi”.

- “**I Giallorossi**” → ça correspond à l’**AS Roma**
- “**The Reds**” → c’est le surnom du club de **Liverpool**

En cherchant **"Liverpool qualified against AS Roma"**, je tombe sur l’historique des confrontations UEFA :  
👉 https://www.uefa.com/uefachampionsleague/history/h2h/7889/50137/

Même si Liverpool perd le match retour (4-2), ils se qualifient quand même. Et ce match retour a eu lieu le **2 mai 2018**.  
Donc, on garde la **date du 3 mai 2018** comme piste de l’événement.

---

## 🕵️ Étape 3 – Lien entre Casamance et cette date

Je cherche donc :  
**"Casamance" "pont" "3 Mai 2018"**

Je tombe sur un article de presse locale :  
👉 https://www.senenews.com/actualites/attaques-de-rebelles-en-casamance-la-zone-de-nyassia-en-eaux-troubles_234813.html

Il parle d’une **attaque armée** dans la zone de **Nyassia**, près du **pont de Niambalang**. On avance bien.

---

## 🧠 Étape 4 – Quel groupe est impliqué ?

Je lance une dernière recherche avec les mots-clés :  
**"Niambalang groupe rebelle"**

Et là je trouve un rapport Amnesty qui mentionne le **MFDC** (Mouvement des Forces Démocratiques de Casamance) :  
👉 https://www.refworld.org/reference/countryrep/amnesty/1997/fr/22296

C’est un groupe séparatiste actif dans la région depuis longtemps. C’est notre dernier élément.

---

## 🏁 Flag

```
BzhCTF{Niambalang_03052018_MFDC}
```

---

## 🎯 Conclusion

Ce challenge OSINT m’a permis de bosser une vraie logique de recherche :

- Partir d’un indice géo (Casamance)
- Identifier un événement à travers un match de foot
- Suivre une piste de date + lieu jusqu’à une attaque réelle
- Identifier le groupe responsable à travers des sources fiables

Une belle enquête à base de recherche Google bien ciblée. Super intéressant à résoudre !

---
