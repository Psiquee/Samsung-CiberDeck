


# 🧹 Limpieza Android

## Objetivo

Reducir consumo de recursos eliminando aplicaciones innecesarias para transformar el dispositivo en un CyberDeck.

---

## Aplicaciones eliminadas

### Google

* Play Store
* Gmail
* Google Search
* Google Feedback
* Unified Inbox
* SignIn

### Samsung

* Samsung Apps
* Samsung Apps UNA

---

## Método utilizado

Ingreso por ADB:

```bash
adb shell
su
```

Renombrado seguro:

```bash
mv App.apk App.apk.bak
```

Ejemplo:

```bash
mv Phonesky.apk Phonesky.apk.bak
```

---

## Ventajas

* Menor consumo RAM
* Menor consumo almacenamiento
* Menos procesos en segundo plano
* Sistema más estable

---

## Resultado

✅ Sistema más ligero

✅ SSH operativo

✅ ConnectBot operativo

---

## Evidencia

```text
screenshots/cleanup/
```
