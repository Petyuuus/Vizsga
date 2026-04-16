# Szakmai Vizsga - Hálózatépítési Projekt 🌐

Ez a repozitórium a szakmai vizsgám hálózati topológiáját, konfigurációs fájljait és a működést igazoló teszteket tartalmazza. A projekt célja egy komplex, biztonságos vállalati hálózat (pl. kórház, központ és telephelyek) felépítése volt.

## 📁 Vizsgafájlok (Cisco Packet Tracer)
A hálózat tervezése és szimulációja Cisco Packet Tracer segítségével készült. A repóban megtalálhatóak a fejlesztés fázisai, a végső verzió a legfrissebb fájlban található.

* [**`szakmai vizsga2.1.pkt`**](szakmai%20vizsga2.1.pkt) - **A VÉGSŐ, TELJES VERZIÓ**
* [`szakmai vizsga1.6 demo.pkt`](szakmai%20vizsga1.6%20demo.pkt) - Demo verzió
* [`szakmai vizsga1.7.pkt`](szakmai%20vizsga1.7.pkt) - Utolsó előtti verzió
* [`szakmai vizsga (1).pkt`](szakmai%20vizsga%20(1).pkt) - Legelső alap verzió

*(A többi korábbi verzió `1.0`-tól `1.5`-ig szintén megtalálható a fájlok között a repóban).*

## ⚙️ Konfigurációs fájlok
Az eszközök (routerek, switchek, WLC) beállításai kimentve szöveges formátumban, technológiák szerint csoportosítva.

* **Alap és Layer 2:**
  * [`layer 2 config kórházba.txt`](layer%202%20config%20kórházba.txt)
  * [`WCL, LAP config.txt`](WCL,%20LAP%20config.txt) (Vezeték nélküli hálózat)
* **Routing és Magas Rendelkezésre Állás:**
  * [`EESZT OSPF.txt`](EESZT%20OSPF.txt)
  * [`HSRP_OSPF_HOSPITAL_CONF.txt`](HSRP_OSPF_HOSPITAL_CONF.txt)
* **VPN és Biztonság:**
  * [`HUB and spoke GRE.txt`](HUB%20and%20spoke%20GRE.txt)
  * [`HUB and SPOKE IPSEC.txt`](HUB%20and%20SPOKE%20IPSEC.txt)
  * [`GRE-IPSEC config állítása R3-4.txt`](GRE-IPSEC%20config%20állítása%20R3-4.txt)
* **Dokumentáció:**
  * [`Terv.docx`](Terv.docx) - Projekt tervdokumentáció

## 🖼️ Tesztek és Ellenőrzések (Képek)
A hálózat megfelelő működését bizonyító képernyőmentések a ping és traceroute parancsokról, valamint a VPN tunnel felépüléséről.

* [`IPSEC ellenőrzés.png`](IPSEC%20ellenőrzés.png) - Az IPsec kapcsolat státusza
* [`IPSEC tesztelés(+ping).png`](IPSEC%20tesztelés(%2Bping).png) - Titkosított adatforgalom tesztje
* [`ping_pc8-pc9_tunnel.png`](ping_pc8-pc9_tunnel.png) - Tunnelen keresztüli kapcsolat teszt
* [`tracert_pc8-pc9_tunnel.png`](tracert_pc8-pc9_tunnel.png) - Útvonalkövetés a tunnelen át

---
*Készítette: Petyuuus*
