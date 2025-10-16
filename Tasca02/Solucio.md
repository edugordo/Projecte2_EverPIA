## ✅ Solució

# T02 - Selecció d'un SAI per una empresa client  
**Autor:** Edu Gordo – SMXA 2  

---

## Descripció de la tasca  
**Empresa:** *TecnoGestio – Gestió documental i assessorament informàtic.*  
Aquesta empresa compta amb un despatx amb els següents dispositius:

- 4 ordinadors de sobretaula  
- 1 impressora fotocopiadora multifunció  
- 1 router d’accés a internet  

**Situació elèctrica:**  
> CONSTANTS INCIDÈNCIES AMB EL SUBMINISTRAMENT ELÈCTRIC A LA ZONA

**Objectiu del SAI:**  
- Garantir la continuïtat dels projectes  
- Protegir els equips  

---

## 1. Inventari d’equips  

| **DISPOSITIU**              | **QUANTITAT** | **OBSERVACIONS** |
|-----------------------------|----------------|------------------|
| Ordinadors de sobretaula    | 4              |                  |
| Monitors                    | 4              |                  |
| Router                      | 1              |                  |
| Impressora                  | 1              | No es connectarà al SAI, ja que no és un dispositiu crític. |

---

## 2. Estudi del consum de cada dispositiu  

- **Ordinador:** PC HP OmniDesk M02-0023ns  
- **Monitor:** HP Pavilion 23xig  
- **Router:** Vodafone Gigabox SHG3000  

---

## 3. Càlcul de potència total (amb el 20% de reserva)

| **Dispositiu** | **Consum per unitat (W)** | **Quantitat** | **Total (W)** |
|----------------|---------------------------|----------------|----------------|
| Ordinadors     | 180                       | 4              | 720            |
| Monitors       | 30                        | 4              | 120            |
| Router         | 20                        | 1              | 20             |
| **Total**      |                           |                | **860 W**      |

**Reserva del 20%:**  
860 W × 1,2 = **1032 W → 1100 W totals**

---

## 4. Determinació de l’autonomia  

El temps mínim que el SAI ha de mantenir els equips en funcionament és de **15 - 20 minuts**.  
Aquesta autonomia és suficient per **guardar i finalitzar les tasques més importants** mentre es restableix el subministrament elèctric.

---

## 5. Recerca de models de SAI  

| **Model** | **Potència (W/VA)** | **Autonomia** | **Sortides** | **Relació W/VA** | **Transferència** | **Preu** |
|------------|--------------------|----------------|----------------|------------------|------------------|-----------|
| **Eaton 5P 1440VA / 1100W – Rack/Torre** | 1100 W / 1440 VA | 15–20 min | 10 | 0,8 | 4 ms | 1000 € |
| **Tripp Lite SMART1500LCDT** | 900 W / 1500 VA | 10 min | 10 | 0,7 | 4 ms | 350 € |
| **CyberPower CP1500PFCLCD** | 900 W / 1500 VA | 10 min | 12 | 0,7 | 4 ms | 380 € |

---

## 6. Informe tècnic  

### Models analitzats  
Els tres models proposats a l’apartat anterior compleixen amb les característiques més importants determinades durant l’estudi.  
Són opcions adequades segons:  
- Les necessitats de l’empresa  
- Els dispositius a protegir  
- El temps d’autonomia requerit  

---

## 7. Justificació de la selecció final  

Després d’analitzar i comparar els tres models, el **SAI seleccionat** és el:

### ✅ **CyberPower CP1500PFCLCD**

**Motivació de la tria:**
- Té més **sortides de connexió (12)** que els altres models.  
- Ofereix una **bona potència (900 W)** suficient per a les necessitats de l’empresa.  
- Té una **bateria amb càrrega ràpida i fàcil substitució**.  
- Presenta una **excel·lent relació qualitat/preu**: tot i oferir característiques similars al primer model, el seu cost és molt més baix.  

**Conclusió:**  
El **CyberPower CP1500PFCLCD** és la millor opció per instal·lar a TecnoGestio, ja que garanteix la protecció dels equips, una autonomia adequada i una inversió ajustada al pressupost.
