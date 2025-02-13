# **PR - Hivatalos Vizsgafeladat**

**Tantárgy:** Szerverek és felhőszolgáltatások

**Vizsgázó neve:**  _______________________________

**Dátum:**  _______________________________

**Instrukciók:**

- Minden feladat elvégzése kötelező.
- A dolgozat során csak a megadott hálózati tartományt és konfigurációs beállításokat használja.
- A vizsga teljes időtartama: 120 perc.
- Minden részfeladatra a megfelelő pontszámot írja be a megoldólapra.
- A végén ellenőrizze az összes beállítást és dokumentálja az eredményeket.

---

## **Feladatok és követelmények:**

### **1. VirtualBox konfiguráció (1 pont)**
- Hozzon létre egy virtuális környezetet, amely biztosítja a szerver és a kliensgépek megfelelő működését.

### **2. Alapvető kliensbeállítások (3 pont)**
- Állítsa be a megfelelő hálózati interfészeket. (2p)
- A számítógép azonosító neve legyen: „FeladatK”. (1p)

### **3. Alapvető szerverbeállítások (9 pont)**
- Állítsa be a megfelelő hálózati interfészeket. (1p)
- A szerver IP-címe a hálózat utolsó kiosztható címe legyen. (2p)
- A szerver neve legyen: „FeladatSZ”. (1p)
- Telepítse a szükséges szoftvereket és szolgáltatásokat. (3p)

### **4. Active Directory tartományvezérlő telepítése és konfigurálása (3 pont)**
- A tartomány neve legyen: „wess.lan”. (1p)
- Adja hozzá a következő felhasználókat: (1p)
  - Teszt Géza
  - Teszt Iván
  - Teszt Emese
- Hozzon létre egy megosztott mappát, amely csak írási joggal rendelkezik és automatikusan felcsatolásra kerül. (1p)

### **5. Tartományba léptetés (2 pont)**
- Lépje be a klienseket az Active Directory tartományba és ellenőrizze az erőforrások elérését.

### **6. DHCP és hatókör beállítása (3 pont)**
- Biztosítsa, hogy a DHCP szerver ne oszthasson ki 10-nél több IP-címet. (1p)
- Az első három kiosztható IP-cím tiltólistára kerüljön. (1p)
- Állítsa be az alapértelmezett átjárót. (1p)

### **7. Távoli asztal elérés konfigurálása és tesztelése (1 pont)**
- Engedélyezze a távoli asztali kapcsolatot és ellenőrizze annak működését.

### **8. Nyomtatószerver beállítása (2 pont)**
- Telepítse és konfigurálja a nyomtatószervert.
- Biztosítsa a hálózati nyomtatók megfelelő kezelését.

### **9. Windows Server Backup konfigurálása (2 pont)**
- Hozzon létre egy meghajtót a biztonsági mentésekhez.
- Állítsa be az automatikus mentéseket.

---

## **Hálózati kiosztás 10.10.10.0/28 (255.255.255.240)**

| Eszköz              | IP-cím      | Megjegyzés                      |
| ------------------- | ----------- | ------------------------------- |
| Tiltott IP 1        | 10.10.10.1  | Tiltott IP-cím                  |
| Tiltott IP 2        | 10.10.10.2  | Tiltott IP-cím                  |
| Tiltott IP 3        | 10.10.10.3  | Tiltott IP-cím                  |
| FeladatK (kliens)   | 10.10.10.5  | Kliensgép a feladat szerint     |
| FeladatSZ (szerver) | 10.10.10.14 | Szerver az utolsó kiosztott cím |

---

**Megjegyzések és értékelés:**

| Feladat                  | Max. Pont | Elért Pont |
| ------------------------ | --------- | ---------- |
| VirtualBox konfiguráció  | 1         |            |
| Kliensbeállítások        | 3         |            |
| Szerverbeállítások       | 9         |            |
| AD tartományvezérlő      | 3         |            |
| Tartományba léptetés     | 2         |            |
| DHCP konfigurálása       | 3         |            |
| Távoli asztal beállítása | 1         |            |
| Nyomtatószerver          | 2         |            |
| Windows Server Backup    | 2         |            |
| **Összesen**             | **26**    | **/**      |

**Vizsgáztató aláírása:** _______________________________

**Megjegyzések:**

---

A vizsga befejezése után kérjük, hogy adja le a dokumentációt és az ellenőrzési jegyzőkönyvet a vizsgáztatónak.
