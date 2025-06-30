# -Simulacin-de-hogares-con-anlisis-e-interpretacin-econmica
# 🏡 Simulación de Hogares y Análisis Económico

**Autor**: Edward Ugarte  
**Fecha**: 29 de junio de 2025  
**Versión**: Compatible con Gretl 2025b

Este repositorio contiene un script en Gretl que genera una base sintética de hogares con características económicas y sociodemográficas. Incluye análisis de consumo, ahorro, educación y segmentación por formalidad laboral, todo con regresiones explicadas y tasas exportables para su interpretación.

---

## 🎯 Objetivos

- Simular 500 hogares con ingresos, consumo, deuda, educación, tamaño y edad del jefe/a de hogar.
- Ejecutar modelos econométricos en niveles y en logaritmos.
- Medir elasticidades ingreso–consumo.
- Comparar patrones entre hogares formales e informales.
- Calcular tasas de ahorro promedio según educación.

---

## ⚙️ ¿Qué hace este script?

- Genera una base de datos: `simulacion_EL.gdt`.
- Ejecuta 4 modelos de regresión:
  - Modelo 1: consumo ~ ingresos + deuda + nmiembros + formalidad
  - Modelo 2: log(consumo) ~ log(ingresos) + deuda + nmiembros + formalidad
  - Modelo 3: solo formales
  - Modelo 4: solo informales
- Calcula y exporta a CSV las tasas promedio de ahorro por nivel educativo.
- Imprime mensajes interpretativos en consola (coeficientes, significancia, R²).

---

## 📁 Archivos generados

| Archivo                       | Contenido                                       |
|------------------------------|--------------------------------------------------|
| `simulacion_EL.gdt`          | Base sintética de hogares en formato Gretl      |
| `tasas_ahorro_resumen.csv`   | Tasa de ahorro promedio por nivel educativo     |
| `README.md`                  | Descripción completa del proyecto                |

---

## 💡 Aplicaciones sugeridas

- Prácticas de enseñanza en econometría aplicada
- Comparación de segmentación socioeconómica
- Laboratorios reproducibles para microeconomía
- Prototipo de análisis para encuestas sociales (como CASEN o censos)

---

## 📄 Licencia

Este proyecto se distribuye bajo la [Licencia MIT](LICENSE).  
Se espera reconocimiento si se reutiliza parte del código o su estructura.


> — Edward Ugarte

---

## 👤 Autor

**Edward Ugarte**  
Economista. Programador. Especialista en claridad técnica.  
