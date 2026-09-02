
# Despliegue de Servidor Web Local con Vagrant y Linux

Proyecto práctico de infraestructura básica enfocado en el aprovisionamiento de un entorno virtualizado aislado para hospedar un sitio web estático.

## 🛠️ Tecnologías y Herramientas Utilizadas
* **Virtualización:** Vagrant, VirtualBox
* **Sistema Operativo:** Linux (CentOS / Rocky Linux)
* **Servidor Web:** Apache HTTP Server (`httpd`)
* **Redes:** Configuración de redes privadas y reenvío de puertos (Port Forwarding)
* **Utilidades de red:** `wget`, `unzip`

---

## 📂 Estructura del Repositorio
```text
.
├── Vagrantfile        # Configuración de recursos (CPU, RAM) y esquemas de red
└── README.md          # Documentación del proyecto


```
---

## 🚀 Cómo replicar este entorno

1. Clona este repositorio en tu máquina local:
```bash
git clone [https://github.com/tu-usuario/tu-repositorio.git](https://github.com/tu-usuario/tu-repositorio.git)
cd tu-repositorio

```


2. Levanta la máquina virtual con Vagrant:
```bash
vagrant up

```


3. Conéctate a la máquina virtual mediante SSH:
```bash
vagrant ssh

```


4. Verifica que el servicio web de Apache esté activo y habilitado para iniciar con el sistema:
```bash
sudo systemctl status httpd

```


5. Abre tu navegador web e ingresa a la IP privada o al puerto configurado en tu `Vagrantfile` para visualizar la plantilla web desplegada en `/var/www/html`.

