# TryHackMe: Search Skills - Write-up 🔍

### 📝 Összefoglaló
A kiberbiztonság egyik legfontosabb eszköze nem egy bonyolult szoftver, hanem a hatékony információkeresés. Ebben a modulban megtanultam, hogyan használjam a keresőmotorokat (Google, DuckDuckGo) profi szinten, hogy célzott adatokat találjak.

### 🛠️ Amit tanultam (Google Dorking alapok)
A "Google Dorking" speciális operátorok használatát jelenti, amivel olyan információkat is elérhetünk, amiket a fejlesztők nem szándékoztak publikussá tenni.

**Legfontosabb operátorok, amiket kipróbáltam:**
* `site:example.com` – Csak az adott weboldalon keres.
* `filetype:pdf` – Csak adott fájlformátumokat listáz (pl. elfelejtett dokumentációk, számlák).
* `intitle:"index of"` – Nyitott könyvtárakat keres, ahol sokszor bizalmas fájlok érhetőek el.
* `""` – Pontos kifejezésre való keresés.

### 💡 Miért fontos ez egy Pentesternek?
A felderítési szakaszban (Reconnaissance) így találhatjuk meg a leggyorsabban a célpont gyenge pontjait, például régi aldomaineket, tesztoldalakat vagy publikusan maradt konfigurációs fájlokat anélkül, hogy közvetlenül megtámadnánk a szervert.
