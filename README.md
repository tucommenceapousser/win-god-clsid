# 🖤 Windows Super God Mode - trhacknon

Bienvenue dans **Windows Super God Mode** par **trhacknon**, dev anonymous black hat 🖤.  
Ce projet permet de **scanner, lister et créer tous les CLSID Windows**, avec des options **interactives, complètes ou différées**.
![https://github.com/tucommenceapousser/win-god-clsid]

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

## 🔗 Liens utiles

- Inspiration : https://github.com/tucommenceapousser/Windows-Super-God-Mode  
- Contact dev : trhacknon
