
# 🧭 Writeup – Où va Eduardo O'Sullivan ? – BreizhCTF 2025 – OSINT  
**Morad Halmi – Ecole2600 – CTF OSINT**

---

## 🏝️ Étape 1 – Point de départ : l’île d’Egueye

Le challenge mentionne un campement sur l’**île d’Egueye**. Une recherche rapide permet de retrouver un **avis TripAdvisor** laissé en mars 2024 par la mère d’Eduardo, localisé dans la ville de **Diakene Ouolof** (Sénégal).

> “Nous y sommes allés avec mon fils il y a quelques années, l'endroit est bucolique et reposant… Plus de photos rapidement sur mon instagram : @ladaronneaedy”

Premier pivot trouvé : le compte **Instagram** de la mère : `@ladaronneaedy`.

---

## 📸 Étape 2 – Instagram de la mère

Sur le compte `@ladaronneaedy`, plusieurs photos sont visibles.  
Notamment une avec la légende :

> “J'ai enfin pu visiter le lieu de travail de mon fils Eduardo mais je dois rentrer en France demain 01/03/2018.”

Pas de localisation directe sur cette photo, mais on prend note de la date.

Une autre photo datée du **25/03/2012** mentionne un **voyage au Pays de Galles** avec la famille, avec une image clairement identifiable : le **château de Cardiff**.

---

## 🔍 Étape 3 – Compte Instagram d’Eduardo

Parmi les abonnements de @ladaronneaedy, on trouve le profil **@edy.sully**, celui d’Eduardo.

Voici les publications qu’on peut identifier, par ordre chronologique :

1. 🌅 Un coucher de soleil – description :  
   *“Une magnifique région…”*  
   La ville est taguée : **Ziguinchor** *(Sénégal)*

2. 🏛️ **Statue de Lénine à Hanoi** *(Vietnam)*  
3. 🏙️ **Oriental Pearl TV Tower à Shanghai** *(Chine)*  
4. 🏺 **Musée de l'Acropole à Athènes** *(Grèce)*  
5. 🏨 **Ancien hôtel Rothes Haus à Düsseldorf** *(Allemagne)*  
6. 🏰 **Château de Cardiff** *(Pays de Galles)*  
   > Cette photo avait déjà été vue sur l’Instagram de la mère, datée de 2012. Elle ne correspond donc pas à un voyage d’Eduardo.  
7. 🦖 **Muséum d’Histoire Naturelle de Londres** *(Angleterre)*

---

## 🏁 Flag

```
BZHCTF{ziguinchor_hanoi_shanghai_athenes_dusseldorf_londres}
```

---

## ✅ Conclusion

Un challenge OSINT très sympa où il fallait :

- Identifier des lieux à travers des photos et légendes
- Suivre une piste logique entre différents comptes sociaux
- Éliminer les lieux non pertinents pour construire un flag propre

Les éléments étaient bien ficelés et assez réalistes, parfait pour pratiquer la fouille d’infos en sources ouvertes dans un contexte de cybersécurité.

---
