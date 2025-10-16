**T03 - SEGURETAT LÒGICA**
---
![imatge](IMG/1.png)

Abans de començar, anirem als paràmetres de la màquina i posarem el disc dur de seguretat

---

![imatge](IMG/2.png)

Al entrar a la màquina de Zorin, mantindrem el “shift” (↑) per accedir a aquest menú y anirem a les opcions avançades

---

![imatge](IMG/3.png)

A les opcions avançades, hem de sel·eccionar la segona opció

---

![imatge](IMG/4.png)

Anirem a l'opció de “root”

---

![imatge](IMG/5.png)

Amb el següent comandament podrem veure i identificar el nom de l’usuari. I amb la comanda “passwd (nom d’usuari)” podem canviar la contrasenya

---

![imatge](IMG/6.png)

![imatge](IMG/7.png)

Quan haguem canviat la contrasenya podrem continuar en el menú anterior a la primera opció; “resume”

---

![imatge](IMG/8.png)

Tornarem a iniciar la màquina pero aquesta vegada podrem posar la contrasenya que haguem posat en l'usuari per iniciar sessió

---

![imatge](IMG/9.png)

I ja haurem accedit a l’escriptori i haurem canviat la contrasenya de l’usuari

---

![imatge](IMG/10.png)

Quan ja estiguem dintre, obrim la terminal i amb la següent comanda ens donarà el hash de la nostra contrasenya

---

![imatge](IMG/11.png)

Farem “sudo nano /etc/grub.d/40_custom” i escriurem el hash que ens havia donat la comanda anterior

---

![imatge](IMG/12.png)


![imatge](IMG/13.png)


![imatge](IMG/14.png)

Actualitzarem grub amb la primera comanda, després posarem una de les dues comandes següents. Serveixen per crear un nou arxiu de configuració

---

![imatge](IMG/16.png)

Tornem a iniciar la màquina i veurem que ens surt una terminal on ens demana l’usuari i la contrasenya

---

![imatge](IMG/17.png)

I si posem l’usuari i la contrasenya correctament ens deixarà iniciar sessió en la màquina virtual de Zorin

---
