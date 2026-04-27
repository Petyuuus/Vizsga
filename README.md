# Hálózatépítő Szakmai Vizsga - Projekt Repozitórium

Ebben a repozitóriumban a szakmai vizsgámhoz tartozó hálózati tervezési dokumentációk, eszközkonfigurációk és szimulációs fájlok találhatóak. A projekt egy komplex (kórházi és EESZT) hálózati infrastruktúra felépítését, biztonságossá tételét és redundáns működését mutatja be.

## 🗂️ A repozitórium felépítése (Kattintható linkek)

Az átláthatóság érdekében az anyagokat az alábbi mappastruktúra szerint rendszereztem. Kattints a mappa nevére a fájlok megtekintéséhez:

* 📁 **[Dokumentációk](./Dokumentaciok)** *A vizsgamunkához tartozó hálózatépítési és logikai tervek (pl. [Terv.docx](./Dokumentaciok/Terv.docx)).*

* 📁 **[Konfigurációk](./Konfiguraciok)** *A hálózati eszközök (Routerek, Switchek, WLC, ASA tűzfal) kimentett konfigurációs szövegfájljai.*

* 📁 **[Packet Tracer fájlok](./Packet_Tracer)** *A megvalósított hálózati topológiák és szimulációk (.pkt formátumban).*

* 📁 **[Tesztelés és igazolás](./Teszteles)** *Képernyőképek a hálózat működéséről, ping tesztekről és VPN alagutak állapotáról.*

## 🛠️ Alkalmazott technológiák és protokollok

A hálózati topológia kialakítása során az alábbi főbb vizsgakövetelményeket és technológiákat alkalmaztam:

* **Irányítás és redundancia:** OSPF routing protokoll, HSRP (Hot Standby Router Protocol).
* **Biztonság és VPN:** IPsec VPN hálózatok, GRE Tunneling, Cisco ASA tűzfal konfiguráció.
* **Vezeték nélküli hálózat:** WLC (Wireless LAN Controller) és LAP beállítások.
* **Topológia és Layer 2:** Hub and Spoke topológia, VLAN kialakítások.

## 🚀 Használat és tesztelés

1. A hálózati szimulációk futtatásához töltsd le a fájlokat a **[Packet_Tracer](./Packet_Tracer)** mappából.
2. A megnyitáshoz legalább **Cisco Packet Tracer 8.x** verzió szükséges.
3. Az eszközök részletes beállításai a **[Konfiguraciok](./Konfiguraciok)** mappában lévő szöveges fájlokban olvashatóak vissza.
