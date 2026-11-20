# HablaFluido — Inglés con IA

App en Flutter para aprender inglés con un tutor de IA: pronunciación, dictado, lectura, escritura, conversación y repaso con repetición espaciada (SM-2). Incluye un **proxy en Node** (`proxy/`) para no exponer la llave de la IA.

Proyecto hecho con **TDD** (primero la prueba en rojo, luego el código para ponerla en verde) siguiendo el manual de la materia.

## Cómo correr las pruebas

```
flutter test
```

Pruebas del proxy:

```
cd proxy
node --test
```

## La app funcionando en el celular

<img src="capturas_app/app_01.jpg" alt="App en el celular" width="300">

---

## Evidencias TDD (rojo → verde)

**Alumna:** Yaneli Sánchez Cárdenas · **Grupo:** GTID244

Cada ronda muestra primero la prueba en **rojo** (falla porque el código todavía no existe) y después en **verde** (pasa ya con el código hecho).

### Ronda 1

**Rojo — la prueba falla**

![Ronda 1 en rojo](capturas_tdd/01_roja.png)

**Verde — la prueba pasa**

![Ronda 1 en verde](capturas_tdd/01_verde.png)

### Ronda 2

**Rojo — la prueba falla**

![Ronda 2 en rojo](capturas_tdd/02_roja.png)

**Verde — la prueba pasa**

![Ronda 2 en verde](capturas_tdd/02_verde.png)

### Ronda 3

**Rojo — la prueba falla**

![Ronda 3 en rojo](capturas_tdd/03_roja.png)

**Verde — la prueba pasa**

![Ronda 3 en verde](capturas_tdd/03_verde.png)

### Ronda 4

**Rojo — la prueba falla**

![Ronda 4 en rojo](capturas_tdd/04_roja.png)

**Verde — la prueba pasa**

![Ronda 4 en verde](capturas_tdd/04_verde.png)

### Ronda 5

**Rojo — la prueba falla**

![Ronda 5 en rojo](capturas_tdd/05_roja.png)

**Verde — la prueba pasa**

![Ronda 5 en verde](capturas_tdd/05_verde.png)

### Ronda 6

**Rojo — la prueba falla**

![Ronda 6 en rojo](capturas_tdd/06_roja.png)

**Verde — la prueba pasa**

![Ronda 6 en verde](capturas_tdd/06_verde.png)

### Ronda 7

**Rojo — la prueba falla**

![Ronda 7 en rojo](capturas_tdd/07_roja.png)

**Verde — la prueba pasa**

![Ronda 7 en verde](capturas_tdd/07_verde.png)

### Ronda 8

**Rojo — la prueba falla**

![Ronda 8 en rojo](capturas_tdd/08_roja.png)

**Verde — la prueba pasa**

![Ronda 8 en verde](capturas_tdd/08_verde.png)

### Ronda 9

**Rojo — la prueba falla**

![Ronda 9 en rojo](capturas_tdd/09_roja.png)

**Verde — la prueba pasa**

![Ronda 9 en verde](capturas_tdd/09_verde.png)
