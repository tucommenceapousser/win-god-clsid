# 🖤 Windows Super God Mode - trhacknon

Bienvenue dans **Windows Super God Mode** par **trhacknon**, dev anonymous black hat 🖤.  
Ce projet permet de **scanner, lister et créer tous les CLSID Windows**, avec des options **interactives, complètes ou différées**.
![https://github.com/tucommenceapousser/win-god-clsid]

---

### Zip of folder with some clsid ready to use on your desktop

```
https://github.com/tucommenceapousser/win-god-clsid/releases/download/1.0/clsid.zip
```


## 📂 CLSID cachés Windows
 
 
À utiliser comme : `Nom.{CLSID}`
 
 
### ⚙️ Réglages & configuration
 
 
- **GodMode (tous les réglages)** `{ED7BA470-8E54-465E-825C-99712043E01C}`
 
- **Panneau de configuration** `{21EC2020-3AEA-1069-A2DD-08002B30309D}`
 
- **Paramètres PC (Windows 10/11)** `{F1B32785-6FBA-4FCF-9D55-7B8E7F157091}`
 

 
### 🖥️ Système
 
 
- **Centre Réseau et partage** `{8E908FC9-BECC-40F6-915B-F4CA0E70D03D}`
 
- **Connexions réseau** `{7007ACC7-3202-11D1-AAD2-00805FC1270E}`
 
- **Gestionnaire de périphériques** `{74246bfc-4c96-11d0-abef-0020af6b0b7a}`
 
- **Outils administratifs** `{D20EA4E1-3957-11D2-A40B-0C5020524153}`
 
- **Gestion des disques** `{74246bfc-4c96-11d0-abef-0020af6b0b7a}`
 

 
### 📑 Fichiers & bibliothèques
 
 
- **Mes Documents** `{450D8FBA-AD25-11D0-98A8-0800361B1103}`
 
- **Mes Images** `{7BD29E00-76C1-11CF-9DD0-00A0C9034933}`
 
- **Téléchargements** `{374DE290-123F-4565-9164-39C4925E467B}`
 

 
### 🛠️ Divers outils
 
 
- **Programmes et fonctionnalités (désinstaller)** `{7b81be6a-ce2b-4676-a29e-eb907a5126c5}`
 
- **Pare-feu Windows** `{4026492F-2F69-46B8-B9BF-5654FC07E423}`
 
- **Tâches planifiées** `{D6277990-4C6A-11CF-8D87-00AA0060F5BF}`
 
- **Journal des événements** `{F3A614DC-ABE0-11D1-8FB1-00A0C90F26F9}`
 
- **Politiques de sécurité locales** `{62D8ED13-C9D0-4CE8-A914-47DD628FB1B0}`
 
- **Gestion de l’ordinateur** `{20D04FE0-3AEA-1069-A2D8-08002B30309D}`
 

 
### 🎵 Multimédia
 
 
- **Périphériques audio** `{0F6F268D-6D61-4B15-B06C-9381D06236CC}`
 
- **Caméras et scanners** `{6bdd1fc6-810f-11d0-bec7-08002be2092f}`

---

## 📂 Contenu du projet

| Script | Description |
|--------|-------------|
| `makemegod.bat` | Version **la plus complète et interactive**. Extraction des CLSID, sélection cocher/décocher, installation directe ou via fichier `.txt`. |
| `dump-clsid.bat` | Dump **tous les CLSID** du registre Windows **sans PowerShell** dans `clsid_full.txt`. |
| `dump-clsid-pwsh.bat` | Dump **tous les CLSID** du registre Windows **via PowerShell**, plus rapide et complet. |
| `trkn-god.bat` | Crée des CLSID depuis une **liste `.txt`** sur Windows (Batch). |
| `trkn-god.sh` | Crée des CLSID depuis une **liste `.txt`** sur Linux (Bash). |

---

## ⚡ Fonctionnalités clés

- Extraction **automatique des CLSID** depuis le registre (`HKEY_CLASSES_ROOT\CLSID`)  
- Menu **pseudo-graphique et interactif**  
- Sélection **cocher/décocher** pour choisir quels CLSID créer  
- Installation **directe** sur le Bureau ou **différée** via un fichier `.txt`  
- Compatible **Windows XP → 11**  
- Style hacker : console **verte sur noir**, mention du dev **trhacknon**  

---

## 🖥️ Utilisation

### 1️⃣ Dump CLSID

**Sans PowerShell :**

```bash
dump-clsid.bat
```

**Avec PowerShell :**

```bash
dump-clsid-pwsh.bat
```

Les scripts génèrent un fichier `clsid_full.txt` contenant tous les CLSID du système au format :

NomLisible|{CLSID}

---

### 2️⃣ Créer des CLSID

**Interactif et complet :**

```bat
makemegod.bat
```

Options disponibles :  
- Créer **un seul CLSID**  
- Créer **plusieurs CLSID**  
- Créer **tous les CLSID**  
- Créer **à partir d’une liste `.txt`**

**Depuis une liste `.txt` :**

```bash
trkn-god.bat   # Windows Batch
trkn-god.sh    # Linux Bash
```

Chaque ligne du fichier correspond à un CLSID à créer.

---

## 📝 Exemple de fichier `.txt` pour installation différée

GodMode
MesDocuments
Videos

Chaque nom correspondra à un CLSID créé sur le Bureau.

---


## ⚠️ Notes

- Certains CLSID peuvent ne pas apparaître si **apps manquantes ou droits limités**  
- Les scripts **ne nécessitent pas d’installation externe**  
- Testé sur **Windows 10/11**, compatible avec **XP et versions supérieures**  
- Linux Bash (`trkn-god.sh`) nécessite un environnement supportant `mkdir` et lecture de `.txt`

---
## Super God Mode

### download

```
https://github.com/ThioJoe/Windows-Super-God-Mode/releases/download/v1.2.2/SuperGodMode-EasyLauncher.bat
```
```
https://github.com/ThioJoe/Windows-Super-God-Mode/releases/download/v1.2.2/Super_God_Mode.ps1
```

### execute

```
SuperGodMode-EasyLauncher.bat
```

---

## 🔗 Liens utiles

- Inspiration : https://github.com/tucommenceapousser/Windows-Super-God-Mode  
- Contact dev : trhacknon
