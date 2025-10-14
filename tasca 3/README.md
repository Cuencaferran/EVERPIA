# Recuperació i Fortificació de l’Accés a Zorin OS

---

## Context

Un client disposa d’un portàtil amb **Zorin OS** (Linux amb entorn gràfic), però ha oblidat la contrasenya d’accés. És necessari recuperar l’accés perquè hi ha documentació molt important.

Per evitar qualsevol dany al sistema original, el disc ha estat clonat en un disc virtual. La tasca és treballar sobre aquest clon.

---

## Objectius

1. Crear una màquina virtual amb el disc clonat.
2. Entrar a la màquina virtual, identificar l’usuari i modificar la seva contrasenya.
3. Verificar que es pot accedir amb la nova contrasenya.
4. Investigar i configurar protecció amb contrasenya a GRUB per evitar reinici de contrasenya no autoritzat.
5. Documentar tot el procés amb imatges i fonts.

---

## Procediment

### 1. Creació de la màquina virtual i connexió del disc clonat

- Crear la màquina virtual amb VirtualBox, VMware o una altra eina.
- Assignar memòria, CPU i altres recursos necessaris.
- Connectar el disc virtual clonat com a disc principal de la màquina virtual.
- Iniciar la màquina virtual.

---

### 2. Accés al sistema i recuperació de la contrasenya

#### Accedir a GRUB i modificar l’arrencada

- A l’inici de la màquina virtual, apareix el menú de GRUB.
- Seleccionar la línia d’arrencada del sistema i prémer `e` per editar.
- Buscar la línia que comença amb `linux` i afegir al final la paraula `single` o `init=/bin/bash`.
- Prémer `Ctrl + X` o `F10` per iniciar amb la modificació.

#### Identificar l’usuari existent

Un cop accedit al sistema en mode single-user:

```bash
ls /home

