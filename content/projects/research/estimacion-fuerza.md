---
title: "Estimación de Fuerza en Soft Fingers"
date: 2025-09-19
description: "Desarrollo de sensores táctiles para robótica suave."

#cover:
#    image: "/images/robot-tesis.jpg" # Imagen que guardaste en static/images/
#    alt: "Prototipo de dedo robótico"
#    caption: "Prototipo final probado en laboratorio"
#    relative: false # Para que use la ruta absoluta desde static
---

``` C++
// Ejemplo: Control de posición simple para tu tesis
float Kp = 1.5;
float setpoint = 90.0;

void loop() {
    float actual = leerSensor();
    float error = setpoint - actual;
    float output = Kp * error;
    aplicarPWM(output);
    // Aquí empieza el código
    int sensorPin = A0;
    void setup() {
    Serial.begin(9600);
}
``` 
&lt; -- ESTO ES LO QUE TE FALTA: Tres tildes en una línea nueva.

Ahora ya puedo escribir texto normal, explicar mi tesis 
o mis avances en la IEEE sin que se vea como código.
&lt;/pre&gt;

-----

### 3 Reglas de oro para que no te vuelva a pasar:

1.  **Línea independiente:** Las tildes de cierre deben estar en su propia línea. No escribas texto justo después de ellas en el mismo renglón.
2.  **Sin espacios:** Asegúrate de que no haya espacios antes de las tildes. Deben estar pegadas al margen izquierdo.
3.  **El lenguaje solo arriba:** Solo pones `cpp`, `python` o `bash` en las tildes de **apertura**. Las de cierre van siempre solas (` ``` `).

-----

### Tip para ingenieros: Resaltado de líneas

Ya que lograste cerrar el bloque, te paso un truco para cuando quieras explicar una parte específica de tu código de control en tus reportes. Puedes resaltar líneas añadiendo `{hl_lines=[numero]}`:

void loop() {
    float data = leerSensor();
    float filtrado = aplicarFiltro(data); // Esta línea saldrá resaltada
    enviarDatos(filtrado);
}

&lt; -- ESTO ES LO QUE TE FALTA: Tres tildes en una línea nueva.

Ahora ya puedo escribir texto normal, explicar mi tesis 
o mis avances en la IEEE sin que se vea como código.
&lt;/pre&gt;

-----

### 3 Reglas de oro para que no te vuelva a pasar:

1.  **Línea independiente:** Las tildes de cierre deben estar en su propia línea. No escribas texto justo después de ellas en el mismo renglón.
2.  **Sin espacios:** Asegúrate de que no haya espacios antes de las tildes. Deben estar pegadas al margen izquierdo.
3.  **El lenguaje solo arriba:** Solo pones `cpp`, `python` o `bash` en las tildes de **apertura**. Las de cierre van siempre solas (` ``` `).

-----


```c++
i++
j++

i*j

``` 
&lt; -- ESTO ES LO QUE TE FALTA: Tres tildes en una línea nueva.

Ahora ya puedo escribir texto normal, explicar mi tesis 
o mis avances en la IEEE sin que se vea como código.
&lt;/pre&gt;

-----

### 3 Reglas de oro para que no te vuelva a pasar:

1.  **Línea independiente:** Las tildes de cierre deben estar en su propia línea. No escribas texto justo después de ellas en el mismo renglón.
2.  **Sin espacios:** Asegúrate de que no haya espacios antes de las tildes. Deben estar pegadas al margen izquierdo.
3.  **El lenguaje solo arriba:** Solo pones `cpp`, `python` o `bash` en las tildes de **apertura**. Las de cierre van siempre solas (` ``` `).

-----
