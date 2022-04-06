# **script-altacertificadovpn**

Script para descargar .ovpn de PfSense a equipos linux

## **Instalación** 🔧

* Para instalar openvpn el el equipo linux

```bash
git clone https://github.com/avillalba96/script-altacertificadovpn.git
cd script-altacertificadovpn
./altaopenvpn
```

## **Configurar User PfSense**

* Si quieren tener un usuario limitado, estos son los permisos necesarios:

```bash
User - Config: Deny Config Write
WebCfg - System: CA Manager
WebCfg - System: Certificate Manager
```
