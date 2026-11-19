<div align="center">

# 🎸 Guitar Academy

**Academia musical interactiva para Android: aprende música y guitarra desde cero hasta nivel profesional.**

[![Última versión](https://img.shields.io/github/v/release/CamiloFerreira/GuitarAcademy-releases?label=versi%C3%B3n&color=ffb300)](https://github.com/CamiloFerreira/GuitarAcademy-releases/releases/latest)
[![Descargas](https://img.shields.io/github/downloads/CamiloFerreira/GuitarAcademy-releases/total?label=descargas&color=4fd1c5)](https://github.com/CamiloFerreira/GuitarAcademy-releases/releases)
![Android](https://img.shields.io/badge/Android-8.0%2B-3ddc84?logo=android&logoColor=white)
![Offline](https://img.shields.io/badge/funciona-sin%20conexi%C3%B3n-7c9cff)

### [⬇️ Descargar la última versión (APK)](https://github.com/CamiloFerreira/GuitarAcademy-releases/releases/latest/download/GuitarAcademy.apk)

</div>

---

Guitar Academy no es una colección de vídeos ni de acordes sueltos: es un **plan de estudios progresivo** en el que cada concepto responde *qué es, por qué existe, cómo funciona, cómo se aplica en la guitarra, cómo se practica y cómo comprobar que lo aprendiste*. Sirve para guitarra **eléctrica, acústica y clásica**, en teléfonos y tablets.

Este repositorio solo contiene las **versiones publicadas (APK)**. El código fuente es privado.

## ✨ Qué incluye

| | |
|---|---|
| 🗺️ **Ruta de aprendizaje** | Plan completo del Nivel 0 (fundamentos absolutos) al Nivel 5 (dominio profesional): 39 módulos y 190 lecciones. Las lecciones se desbloquean por **competencias**: hay que aprobar las evaluaciones de lo anterior. |
| 📚 **Lecciones interactivas** | 47 lecciones publicadas (Nivel 0 completo y teoría del Nivel 1), con teoría, ejemplos, diagramas, tablaturas, pentagramas, ejercicios con tempo, errores frecuentes, resumen, evaluación con explicación de cada respuesta y desafío práctico. Puedes **escuchar** cada tablatura y pentagrama. |
| 🎯 **Diapasón interactivo** | Escalas, acordes, intervalos y notas en todo el mástil, con nombres, grados o intervalos; cajas pentatónicas, 3 notas por cuerda, formas CAGED y digitaciones calculadas. 10 afinaciones, modo zurdo, y cada traste suena al tocarlo. |
| 📖 **Biblioteca** | 22 escalas y modos, 36 tipos de acorde, intervalos, progresiones y las 12 tonalidades con su armadura y campo armónico. Buscador y favoritos. |
| 🎙️ **Afinador real** | Afinador cromático por micrófono (detección de tono YIN, precisión de ±1 cent), con la cuerda más cercana según tu afinación y referencia La configurable. |
| ⏱️ **Metrónomo** | Compases simples, compuestos (6/8, 9/8, 12/8) e irregulares (5/8, 7/8), subdivisiones, acentos y *tap tempo*, con temporización exacta. |
| 👂 **Entrenamiento auditivo** | Alturas, notas, intervalos, acordes y escalas en 3 niveles, con ejercicios generados al azar. Cuando fallas, te explica la diferencia concreta. |
| 📝 **Exámenes** | Examen al final de cada módulo y evaluación general por nivel, con preguntas nuevas en cada intento y nota mínima configurable. |
| 🔁 **Repaso espaciado** | Lo que fallas vuelve en el momento adecuado (algoritmo SM-2), para que no se olvide. |
| 📊 **Progreso** | Competencias dominadas y débiles, errores recurrentes, historial de exámenes, racha y tiempo de estudio, y recomendaciones de qué estudiar después. |

Todo el contenido musical (escalas, acordes, digitaciones, tablaturas) se genera o se verifica automáticamente con un motor de teoría musical probado, para que no haya fórmulas ni diagramas incorrectos.

## 📲 Instalación

1. Desde el móvil, descarga **[GuitarAcademy.apk](https://github.com/CamiloFerreira/GuitarAcademy-releases/releases/latest/download/GuitarAcademy.apk)**.
2. Ábrelo. Si Android lo pide, permite **"Instalar aplicaciones desconocidas"** para tu navegador o gestor de archivos.
3. Pulsa **Instalar**.

**Requisitos:** Android 8.0 o superior. Unos 15 MB de espacio.

## 🔄 Actualizaciones

- La app comprueba si hay una versión nueva al abrirse (se puede desactivar en *Ajustes → Actualizaciones*, donde también puedes buscar manualmente).
- Si hay una versión nueva, la descarga, **verifica su integridad (SHA-256)** y Android te pide confirmar la instalación. Tu progreso se conserva.
- Las **actualizaciones de seguridad obligatorias** bloquean la app hasta que se instalan, para que nadie se quede con una versión vulnerable.

## 🔒 Privacidad y permisos

| Permiso | Para qué se usa |
|---|---|
| Micrófono | Solo el afinador. El audio se analiza en el dispositivo y **nunca se guarda ni se envía**. |
| Internet | Solo para comprobar y descargar actualizaciones desde este repositorio. |
| Instalar aplicaciones | Solo para instalar las actualizaciones de la propia app. |

No hay cuentas, anuncios ni analítica. Tu progreso se guarda únicamente en tu dispositivo.

## ✅ Verificar la descarga (opcional)

Cada versión publica su hash SHA-256 en las notas de la release y en `update.json`. Todas las versiones están firmadas con el mismo certificado:

```
SHA-256 del certificado: c3:8d:68:8a:0c:ea:66:5e:6d:d4:af:44:4a:91:b1:bc:61:42:a7:20:fc:ea:03:45:4a:08:91:2f:b7:ee:81:24
```

```bash
sha256sum GuitarAcademy.apk
apksigner verify --print-certs GuitarAcademy.apk
```

## 📅 Versiones

| Versión | Novedades |
|---|---|
| **0.4.0** | Exámenes de módulo y de nivel, repaso espaciado, panel de progreso y desbloqueo por competencias. |
| **0.3.0** | Afinador por micrófono, metrónomo, entrenamiento auditivo, botones para escuchar las lecciones y botón "Siguiente lección". |
| **0.2.1** | Teoría del Nivel 1: intervalos, escalas mayor y menor, tonalidades, armaduras y círculo de quintas (16 lecciones). |
| **0.2.0** | Motor de lecciones, Nivel 0 completo (31 lecciones), diapasón, biblioteca y actualizaciones automáticas. |

Detalle de cada versión en [Releases](https://github.com/CamiloFerreira/GuitarAcademy-releases/releases).

## 🛣️ Próximamente

- **0.5:** parte práctica del Nivel 1: ritmo con detección de ataques por micrófono, acordes abiertos, técnica con progresión de tempo, generador de progresiones y acompañamientos, grabación de prácticas, objetivos diarios y logros.
- **0.6 en adelante:** Niveles 2 a 5 (armonía, CAGED, pentatónicas, modos, improvisación, composición, producción, jazz y dominio profesional) y optimización para tablets.

## 💬 Sugerencias y errores

Si encuentras un error musical o técnico, o tienes una sugerencia, abre un [issue](https://github.com/CamiloFerreira/GuitarAcademy-releases/issues) indicando la versión de la app (*Ajustes*, al final) y el modelo de tu teléfono.
