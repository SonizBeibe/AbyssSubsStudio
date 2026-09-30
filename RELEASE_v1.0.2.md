# 🌌 AbyssSubs Studio v1.0.2

> ⬇️ **¿No la tenés?** Bajá `AbyssSubs-Studio-Instalador-v1.0.2.exe`.
> 🔄 **¿Ya la tenés?** Bajá `AbyssSubs-Studio-Actualizacion-v1.0.2.exe` y abrilo: actualiza en segundos sin volver a bajar el motor de IA.

## 🔧 Arreglos
- El runtime de Visual C++ ahora se copia al lado de cada librería, así llvmlite/numba, onnxruntime y torch cargan en cualquier PC (antes: «Numba could not be imported», «llvmlite.dll … 0xc0e90002»).
- Las descargas verifican que estén completas; los modelos que quedaron a medias se detectan y se vuelven a bajar (antes: «PytorchStreamReader failed reading zip archive»). Si un modelo dañado se cuela, la app lo borra solo y lo baja al reabrir.
- Cuando algo falla, se abre una ventana con el error completo y un botón para copiarlo.
- El asistente muestra el avance real (MB, paso, tiempo) y deja elegir el disco y el motor (procesador / NVIDIA).

## ✨ Nuevo
- Soporte para placas **AMD/Intel** (DirectML): aceleran la separación de la voz. El asistente ofrece elegir el motor (NVIDIA / AMD-Intel / procesador).

## 💻 Requisitos mínimos
Windows 10/11 de 64 bits · 4 núcleos · 8 GB de RAM · ~4 GB libres + 1,2 GB por idioma · placa NVIDIA opcional.
