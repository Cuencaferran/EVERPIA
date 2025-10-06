# Informe tècnic per a la selecció d’un Sistema d’Alimentació Ininterrompuda (SAI)

**Empresa:** TecnoGestió S.L.  
**Responsable:** Ferran Cuenca  
**Data:** 30/9/2025

---

## 1. Objectiu  
Garantir la continuïtat del servei i protegir els equips informàtics de TecnoGestió S.L. davant les incidències en el subministrament elèctric mitjançant la instal·lació d’un Sistema d’Alimentació Ininterrompuda (SAI).

---

## 2. Inventari i dispositius a connectar

- 4 ordinadors de sobretaula  
- 4 monitors LCD (22")  
- 1 router d’accés a Internet  
- 1 impressora-fotocopiadora multifunció (no connectada al SAI)

**Justificació:**  
L’impressora-fotocopiadora consumeix una potència elevada i no és essencial per la continuïtat immediata de treball. Per això, es desestima la seva connexió al SAI per maximitzar l’autonomia i la protecció dels equips crítics.

---

## 3. Especificacions tècniques i càlculs de potència

| Equip               | Consum (W) | Factor de potència (cos) | Potència aparent (VA) (unitària) |
|---------------------|------------|--------------------------|----------------------------------|
| Ordinador (x4)      | 150 W      | 0.9                      | 167 VA                          |
| Monitor LCD (x4)    | 30 W       | 0.9                      | 33 VA                           |
| Router              | 15 W       | 0.9                      | 17 VA                           |

**Potència total consumida:**  
- Ordinadors: 4 × 150 W = 600 W  
- Monitors: 4 × 30 W = 120 W  
- Router: 15 W  
- **Total en watts:** 735 W  

**Potència aparent (VA):**  
- Ordinadors + monitors = 800 VA  
- Router = 17 VA  
- **Total VA:** 817 VA  

---

## 4. Reserva de potència (20%)  
Per garantir marge d’operació i evitar sobrecàrregues, s’incrementa la potència total un 20%:  

- Potència en watts amb reserva: 735 W × 1.2 = **882 W**  
- Potència en VA amb reserva: 817 VA × 1.2 = **980 VA**  

---

## 5. Autonomia requerida  
L’autonomia mínima requerida és de **10 minuts** per permetre guardar treballs i apagar correctament els equips en cas de tall de subministrament elèctric.

---

## 6. Models de SAI analitzats

| Model                     | Potència VA / W          | Autonomia estimada              | Tecnologia       | Preu aprox (€) |
|---------------------------|--------------------------|--------------------------------|------------------|----------------|
| APC Back-UPS Pro 1500     | 1500 VA / 865 W          | 10-12 minuts a 800 W            | Line-interactive | 250-300        |
| Eaton 5S 1500VA           | 1500 VA / 900 W          | Uns 10 minuts a 850-900 W       | Line-interactive | 250            |
| CyberPower CP1500EPFCLCD  | 1500 VA / 900 W          | Uns 10 minuts a 850-900 W       | Line-interactive (sortida sinusoïdal pura) | 270  |

---

## 7. Ju
