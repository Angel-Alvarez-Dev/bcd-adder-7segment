# Actividad III - Sistemas Digitales

## 🧩 Descripción General

Este repositorio contiene el desarrollo completo de la Actividad III del curso de **Sistemas Digitales**, cuyo objetivo es **diseñar un sistema digital para realizar la suma BCD de dos números** y visualizar el resultado en **dos displays de 7 segmentos**, utilizando **Logisim Evolution** y **KiCad** como herramientas de diseño y simulación.

---

## 🎯 Objetivos de la Actividad

- Desarrollar la habilidad para calcular los **parámetros de corriente, voltaje y potencia** en un sistema digital real.
- Diseñar un **sumador BCD** con detección de exceso y corrección automática (+6).
- Mostrar el resultado de la suma en **dos displays de 7 segmentos** (unidades y decenas).
- Implementar el diseño utilizando **circuitos TTL** y simularlo con herramientas CAD como **KiCad**.
- Validar el funcionamiento lógico mediante tablas de verdad y lógica combinacional.

---

## 📁 Contenido del Repositorio

| Archivo | Descripción |
|--------|-------------|
| `sumador_bcd_LOGISIM.txt` | Tabla de verdad para el sumador binario de dos dígitos BCD (8 bits de entrada → 5 bits de salida). |
| `detector_exceso_bcd_LOGISIM.txt` | Lógica para detectar cuando la suma excede 9. |
| `corrector_bcd_LOGISIM.txt` | Lógica para aplicar la corrección (+6) si hay exceso. |
| `display_decenas_LOGISIM.txt` | Tabla binario a 7 segmentos para la decena del resultado. |
| `display_unidades_LOGISIM.txt` | Tabla binario a 7 segmentos para la unidad del resultado. |
| `image.png` | Diagrama lógico general del sistema. |
| `actividad 3.pdf` | Documento oficial con instrucciones y requisitos de la actividad. |

---

## ⚙️ Especificaciones Técnicas

- **Alimentación**: +5V CC.
- **Entradas**: Conmutadores (switches) con divisores de tensión:
  - VIL = 0.7V
  - VIH = 2.75V
- **Salidas**: Displays de 7 segmentos (catodo común).
- **Familia lógica sugerida**: TTL.

---

## 🧠 Proceso de Diseño

1. **Tablas de verdad** de cada módulo: sumador, detector de exceso, corrector y displays.
2. **Obtención de funciones lógicas** mediante simplificación.
3. **Diseño modular** en Logisim Evolution.
4. **Cálculos eléctricos** de resistencias, corrientes y potencia.
5. **Implementación electrónica** en KiCad.
6. **Simulación y verificación** del sistema completo.


## 📄 Entrega

Este repositorio contiene tanto los archivos lógicos como el reporte requerido en PDF. También el archivo `.circ` de Logisim y el proyecto de KiCad.

