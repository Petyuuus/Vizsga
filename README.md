# Hálózatépítő Szakmai Vizsga - Projekt Repozitórium

Ebben a repozitóriumban a szakmai vizsgánkhoz tartozó hálózati tervezési dokumentációk, eszközkonfigurációk és szimulációs fájlok találhatóak. A projekt egy komplex (kórházi,rendelői és EESZT) hálózati infrastruktúra felépítését, biztonságossá tételét és redundáns működését mutatja be.

## ⚡ Gyors elérések

Ha azonnal a legfontosabb fájlokra vagy kíváncsi, itt egy kattintással elérheted őket:

* 🚀 **[Legújabb vizsga verzió (v2.4)](./PKT/szakmai%20vizsga2.5.pkt)** - *A végleges, legfrissebb Packet Tracer projekt.*
* 🏗️ **[Első verzió (Alap topológia)](./PKT/szakmai%20vizsga1.0.pkt)** - *A hálózat kiinduló, alapértelmezett állapota.*
* 📄 **[Hivatalos Vizsga Dokumentáció](./Dokumentacio/vizsga_dokumentacio%20(1).docx)** - *A projekt részletes logikai és hálózatépítési terve.*
* 📋 **[Tesztelési Dokumentáció](./Dokumentacio/Tesztelesi_Dokumentacio.docx)** - *A hálózat működésének, a ping teszteknek és a biztonsági beállításoknak az ellenőrzése.*

## 🗂️ A repozitórium felépítése

Az átláthatóság érdekében az anyagokat az alábbi mappastruktúra szerint rendszereztük. Kattints a mappa nevére a fájlok megtekintéséhez:

* 📁 **[Dokumentációk](./Dokumentacio)** *A vizsgamunkához tartozó hálózatépítési és logikai tervek.*

* 📁 **[Konfigurációk](./Konfigok)** *A hálózati eszközök kimentett konfigurációs szövegfájljai.*

* 📁 **[Packet Tracer fájlok](./PKT)** *A megvalósított hálózati topológiák és szimulációk (.pkt formátumban).*

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
