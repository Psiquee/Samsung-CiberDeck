# 🔐 SSH Samsung → Debian

## Objetivo

Utilizar el Samsung GT-B5510L como terminal portátil para administrar remotamente un servidor Debian mediante SSH.

---

## Instalación OpenSSH

### Actualizar sistema

```bash
sudo apt update
sudo apt upgrade
```

### Instalar servidor SSH

```bash
sudo apt install openssh-server
```

### Verificar estado

```bash
sudo systemctl status ssh
```

### Habilitar inicio automático

```bash
sudo systemctl enable ssh
```

### Iniciar servicio

```bash
sudo systemctl start ssh
```

---

## Obtener IP

```bash
hostname -I
```

---

## Configuración ConnectBot

Servidor:

```
usuario@IP
```

Ejemplo:

```
psique@192.168.0.16
```

Puerto:

```
22
```

---

## Resultado

✅ Conexión SSH exitosa

✅ Administración remota desde Android

✅ Terminal Linux funcional

---

## Evidencia


screenshots/ssh/

