# 📮 Base enrichie des codes postaux – France, DOM-TOM & Monaco

Enrichissement du fichier fourni par **La Poste** avec :

* les **noms de régions, départements et communes** en minuscules,
* les **codes INSEE**,
* et diverses métadonnées utiles (coordonnées, libellés, article, etc.).

📦 Source officielle :
[https://www.data.gouv.fr/fr/datasets/base-officielle-des-codes-postaux/](https://www.data.gouv.fr/fr/datasets/base-officielle-des-codes-postaux/)

---

## 📑 Description du fichier

Fichier CSV de correspondance entre les **codes communes (INSEE)** et les **codes postaux**.

Champs contenus :

* `code_commune_INSEE`
* `nom_commune_postal`
* `code_postal`
* `libelle_acheminement`
* `ligne_5`
* `latitude`
* `longitude`
* `code_commune`
* `article`
* `nom_commune`
* `nom_commune_complet`
* `code_departement`
* `nom_departement`
* `code_region`
* `nom_region`

---

## 📘 Exemple

```csv
Code_commune_INSEE,Nom_commune,Code_postal,Libelle_acheminement,Ligne_5,longitude,latitude,code_commune,article,nom_commune,nom_commune_complet,code_departement,nom_departement,code_region,nom_region
1001,L ABERGEMENT CLEMENCIAT,1400,L ABERGEMENT CLEMENCIAT,,46.1534255214,4.92611354223,1,L',Abergement-Clémenciat,L'Abergement-Clémenciat,1,Ain,84,Auvergne-Rhône-Alpes
1002,L ABERGEMENT DE VAREY,1640,L ABERGEMENT DE VAREY,,46.0091878776,5.42801696363,2,L',Abergement-de-Varey,L'Abergement-de-Varey,1,Ain,84,Auvergne-Rhône-Alpes
1004,AMBERIEU EN BUGEY,1500,AMBERIEU EN BUGEY,,45.9608475114,5.3729257777,4,,Ambérieu-en-Bugey,Ambérieu-en-Bugey,1,Ain,84,Auvergne-Rhône-Alpes
```

---

## 🌍 Couverture

* France métropolitaine
* Départements d’outre-mer (DOM)
* Territoires d’outre-mer (TOM)
* **Monaco**

---

## 🔎 Ressources associées

* Contours géographiques des communes (à partir des codes INSEE) :
  [https://www.data.gouv.fr/fr/](https://www.data.gouv.fr/fr/)

* Formats additionnels, outils de visualisation et API :
  [https://datanova.legroupe.laposte.fr/](https://datanova.legroupe.laposte.fr/)

---

## 📦 Exemple de réutilisation

### Copriciel — Logiciel de gestion de copropriété

Le projet **[copriciel.com](https://www.copriciel.com)** utilise cette base enrichie pour :

* afficher correctement les **adresses**,
* automatiser la **création des fiches immeubles**,
* valider les informations **INSEE**,
* et améliorer la **cohérence des données** dans les modules de gestion des copropriétés.

Copriciel s’appuie sur ces correspondances pour éviter les erreurs usuelles sur les communes, les codes postaux et les rattachements administratifs (départements, régions).

---

## 💓 Support

Envie de soutenir le travail ? Un café, c’est toujours apprécié ☕👇

* **PayPal** : [https://paypal.me/m0hamedbadaoui](https://paypal.me/m0hamedbadaoui)
* **GitHub Sponsors** : [https://github.com/sponsors/mohamed-badaoui](https://github.com/sponsors/mohamed-badaoui)

Merci 🙏
