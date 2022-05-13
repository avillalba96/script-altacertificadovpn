# **script-altacertificadovpn**

Script para descargar .ovpn de PfSense a equipos linux

## **Instalación** 🔧

* Para instalar openvpn en equipo linux

```bash
git clone https://github.com/avillalba96/script-altacertificadovpn.git && cd "$(basename "$_" .git)" && ./altaopenvpn
```

## **Configurar User PfSense**

* Si quieren tener un usuario limitado, estos son los permisos necesarios:

```bash
User - Config: Deny Config Write
WebCfg - System: CA Manager
WebCfg - System: Certificate Manager
WebCfg - Dashboard (all)
```

## **TAREAS**

* verificar que funcione con "apt-get" y que existe el "/etc/openvpn/client/"
