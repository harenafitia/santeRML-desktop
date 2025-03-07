# Logiciel d'ajout de données contraceptives dans Excel

Ce logiciel permet d'ajouter facilement des données contraceptives dans un fichier Excel structuré.

## 📁 Structure des dossiers

```
📂 Dossier Racine
├── 📄 2025_SDSP_AMBALAVAO_SUIVI.xlsx  # Fichier Excel de destination
├── 📄 gui.exe                         # Exécutable du logiciel
└── 📂 SX/                             # Dossiers des fichiers JSON par semaine
    ├── 📂 S1/
    ├── 📂 S2/
    └── ...
```

**Remarque :** L'utilisateur doit sélectionner le dossier correspondant à la semaine concernée.

## 🖥️ Installation

1. Téléchargez le fichier `gui.exe`
2. Placez-le dans un dossier dédié sur votre ordinateur
   
> 💡 **Astuce :** Évitez de le mettre directement sur le Bureau pour ne pas le perdre.

## 🚀 Utilisation

### Lancement
1. Double-cliquez sur `gui.exe`
2. Si une alerte Windows apparaît, cliquez sur "Plus d'options" puis sur "Exécuter quand même"

### Interface
L'interface comprend :
- **Champ "Message"** : pour saisir manuellement des données contraceptives
- **Bouton "Extraire JSON"** : pour convertir le message en fichier JSON
- **Bouton "Importer JSON et Ajouter à l'Excel"** : pour intégrer des fichiers JSON existants

### Ajout de données
1. Cliquez sur "Parcourir"
2. Sélectionnez le dossier de la semaine désirée (ex: `S4/`)
3. Cliquez sur "Ajouter au fichier Excel"
4. Une confirmation s'affiche lorsque l'opération est réussie

## ✅ Format des messages

Exemples de messages correctement formatés :

### Exemple 1
```
CSB1 Ankarinarivo,25 au 30/1/25.  
NU: mg:10,MT:5, DP:2,SP:1,Spai:0,nxt:0,Lev:0,Diu:0, Diuhor:0,Nat:3,Ccv:0. 
UR:mg:122,Mt:48,Dp:548,SP:43,Spai:0,Nxt:86,Lev:10,Diu:0, Diuhor:0,Nat:47,Ccv:0.  
SDU :mg:42,Mt:9, Dp:75,Sp:7,Spai:0, Nxt:3,Lev:3,Diu:0, Diuhor:0, Condom:206, Collier :0
```

### Exemple 2
```
CSB2 Ambalavao, S4.  
NU: mg:10,MT:5, DP:2,SP:1,Spai:0,nxt:0,Lev:0,Diu:0, Diuhor:0,Nat:3,Ccv:0. 
UR:mg:122,Mt:48,Dp:548,SP:43,Spai:0,Nxt:86,Lev:10,Diu:0, Diuhor:0,Nat:47,Ccv:0.  
SDU :mg:42,Mt:9, Dp:75,Sp:7,Spai:0, Nxt:3,Lev:3,Diu:0, Diuhor:0, Condom:206, Collier :0
```

> ⚠️ **Remarque :** Le format correct est essentiel pour que l'extraction fonctionne.

## 📊 Vérification dans Excel
1. Ouvrez `2025_SDSP_AMBALAVAO_SUIVI.xlsx`
2. Vérifiez que les données apparaissent sous la bonne semaine
   
> Le logiciel vérifie automatiquement les totaux pour validation.

## ❓ Dépannage

| Problème | Solution |
|----------|----------|
| Le logiciel ne s'ouvre pas | Vérifiez que votre antivirus ne bloque pas le fichier |
| Les données ne s'ajoutent pas | Vérifiez que le dossier sélectionné contient des fichiers JSON |
| Erreur de syntaxe | Assurez-vous que les messages respectent le format requis |

## 📞 Contact

- **Auteur :** RAZAFINDRALAMBO Harenafitia Don Kaël
- **Email :** harenafitia2000@gmail.com / r.harenafitia.donkael@gmail.com
- **Adresse :** Ambatolahy V Andrainjato, Fianarantsoa, Madagascar
