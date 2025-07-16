#digital-vcards


download link: https://idev4u.github.io/digital-vcards/cards/diecoole1.vcf

NamingConvention: 
https://<username>.github.io/digital-vcards/cards/${vorname}-${nachname}.vcf

## 🚀 Minimal Setup: GitHub Pages für vCards + Bitly Link

### 1. **GitHub Repo anlegen**

Name z. B.: `digital-vcards`
Inhalte:

```bash
cards/
  └── vorname-nachname.vcf
index.html (optional)
README.md
```

### 2. **GitHub Pages aktivieren**

* Gehe zu `Settings > Pages`
* Wähle `main` als Branch und `/ (root)` oder `cards/`
* URL wird: `https://<username>.github.io/digital-vcards/cards/vorname-nachname.vcf`

### 3. **vCard manuell erstellen (Beispiel: Horst Hansen)**

Datei: `cards/horst-hansen.vcf`

```vcf
BEGIN:VCARD
VERSION:3.0
N:Hansen;Horst;;;
FN:Horst Hansen
TITLE:Product Manager
ORG:Company AG
TEL;TYPE=work,voice:+49 123 456789
EMAIL:horst.hansen@company.io
URL:https://company.io
END:VCARD
```

### 4. **Bit.ly Link erstellen**

* Ziel: `https://<username>.github.io/digital-vcards/cards/horst-hansen.vcf`
* Erstelle: `bit.ly/norman-card`
