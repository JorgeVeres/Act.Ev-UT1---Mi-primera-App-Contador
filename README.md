# 📱 AppContador_UT1

## 🧾 Datos del proyecto
- **Nombre del proyecto:** AppContador_UT1  
- **Autor/a:** [Tu nombre aquí]  
- **Fecha:** 17 de octubre de 2025  
- **Versión de Android:** targetSdk 34  
- **Versión mínima:** minSdk 24  
- **Versión de Kotlin:** 1.9.x  

---

## 💡 Tecnología elegida y por qué
He elegido **Jetpack Compose (Kotlin)** porque permite crear interfaces modernas de Android de forma declarativa y sencilla.  
La sintaxis de Compose facilita el trabajo con estados reactivos (`remember` y `mutableStateOf`), reduciendo el uso de XML y mejorando la productividad en el desarrollo de apps móviles.

---

## ⚙️ Configuración del entorno y ejecución
1. Instalar **Android Studio** (versión Hedgehog o posterior).  
2. Crear un nuevo proyecto con la plantilla **“Empty Compose Activity”**.  
3. Asignar el nombre `AppContador_UT1` y seleccionar el lenguaje **Kotlin**.  
4. Copiar el código del contador en `MainActivity.kt`.  
5. Conectar un **dispositivo físico** o crear un **emulador Android (Pixel 7 API 34)**.  
6. Ejecutar la app con el botón ▶️ **Run**.  
7. Comprobar que los botones “+”, “−” y “Reset” funcionan correctamente.

---

## 🧱 Estructura del proyecto
```
app/
 ├─ java/com/example/appcontador_ut1/
 │   └─ MainActivity.kt        → Lógica principal del contador (Composable + estado).
 │
 ├─ ui/theme/
 │   ├─ Color.kt               → Colores del tema.
 │   ├─ Theme.kt               → Definición del tema Compose.
 │   └─ Type.kt                → Tipografía del tema.
 │
 ├─ res/
 │   ├─ drawable/              → Recursos gráficos.
 │   ├─ values/                → Strings, estilos, colores XML.
 │   └─ mipmap/                → Iconos del launcher.
 │
 └─ AndroidManifest.xml        → Configuración general del proyecto.
```

---

## 📲 Perfil de despliegue
- **Versión SDK objetivo:** 34  
- **Versión SDK mínima:** 24  
- **Dispositivo de prueba:** Emulador Pixel 8 Pro (Android 14)  
- **Resolución:** 1080 × 2400 px  
- **Densidad:** xxhdpi  

---

## 🚀 Funcionamiento de la app
La aplicación **AppContador_UT1** muestra un contador que permite:
- Incrementar el valor con el botón “+”.  
- Decrementar el valor con el botón “−”.  
- Reiniciar el valor a “0” con el botón “Reset”.  
- Mostrar un mensaje 🎉 **“¡Meta alcanzada!”** cuando llega a 10.  

El valor del contador se actualiza en tiempo real gracias al uso de `remember { mutableStateOf() }`.

**Captura de funcionamiento:**  

![alt text](image.png)
---

## 🧠 Conclusión y limitaciones
Durante el desarrollo de esta app aprendí a:
- Configurar un entorno de desarrollo Android con Compose.  
- Usar el estado en interfaces reactivas mediante `remember` y `mutableStateOf`.  
- Ejecutar y depurar una app en un emulador Android.  

**Retos/limitaciones:**  
- Configurar correctamente el emulador la primera vez fue lento.  
- El reinicio del contador debía actualizar la interfaz sin retrasos.  
- Se podría mejorar el diseño visual con colores y estilos personalizados.  

En general, fue una experiencia útil para comprender la base del desarrollo móvil con **Jetpack Compose**.

