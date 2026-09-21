# Sistemas Operativos en Red — 2º SMR

Apuntes, ejemplos y ejercicios de la asignatura **Sistemas Operativos en Red** de 2º SMR.

---

## Contenidos

### 1er Trimestre

| Bloque | Temas | Contenido |
|--------|-------|-----------|
| [Bloque 1 — Fundamentos e instalación de sistemas operativos en red](bloque1/README.md) | 1, 2 | Qué es un SO en red, arquitectura cliente/servidor, requisitos, particiones, gestores de arranque, tipos de instalación, imágenes, virtualización |
| Bloque 2 — Instalación y explotación básica de servidores | 3, 4 | Instalación de Windows Server y de Ubuntu Server, configuración inicial, red, cortafuegos, actualizaciones, instalación desatendida y remota |
| Bloque 3 — Usuarios y servicios en Windows Server | 5, 6 | Usuarios y grupos, Active Directory, perfiles, administración remota, servicios DNS y DHCP |
| Bloque 4 — Dominios en Windows Server | 7, 8 | Dominios y controladores de dominio, unidades organizativas, discos y cuotas, roles FSMO, herramientas de administración, delegación |

### 2º Trimestre

| Bloque | Temas | Contenido |
|--------|-------|-----------|
| Bloque 5 — Administración de Linux Server | 9, 10 | Usuarios, grupos y permisos en Linux, servicio de directorio LDAP, servicios DNS, DHCP y FTP |
| Bloque 6 — Monitorización de eventos y rendimiento | 11, 12 | Arranque y apagado, herramientas de rendimiento, logs y alertas, programación de tareas en Windows Server y en Linux |
| Bloque 7 — Recursos compartidos, copias de seguridad e integración | 13, 14, 15 | Carpetas, permisos, cuotas e impresoras compartidas, copias de seguridad, redes con sistemas mixtos (PuTTY, VNC, NFS) |

---

## ¿Qué vamos a ver este curso?

La asignatura sigue un hilo conductor: cómo se monta, se administra y se mantiene una red de equipos que comparten recursos, primero con Windows Server y después con Linux, hasta hacer que convivan.

```
Bloque 1  ──►  Fundamentos e instalación  → qué es un SO en red y cómo se prepara una instalación
Bloque 2  ──►  Primeros servidores        → instalar y dejar en marcha Windows Server y Ubuntu Server
Bloque 3  ──►  Usuarios y servicios       → quién usa la red (usuarios, grupos, Active Directory) y qué
                                            servicios la hacen funcionar (DNS, DHCP)
Bloque 4  ──►  Dominios                   → organizar y administrar toda la red desde un punto central
Bloque 5  ──►  Linux Server               → el mismo trabajo (usuarios, permisos, servicios) en Linux
Bloque 6  ──►  Monitorización             → vigilar que todo funciona: rendimiento, logs y tareas automáticas
Bloque 7  ──►  Compartir e integrar       → recursos compartidos, copias de seguridad y redes con
                                            Windows y Linux a la vez
```

Cada bloque se apoya en el anterior: primero se aprende a **instalar** un servidor, después a **administrar** a quienes lo usan, a **vigilarlo** para que no se caiga y, por último, a **compartir sus recursos y protegerlos** con copias de seguridad en un entorno donde conviven distintos sistemas.

---

## Estructura de cada tema

- **apuntes.md** — Resumen teórico/práctico de cada tema.
- **casospracticos.md** — Ejemplos y casos prácticos con su resolución y explicados en clase.
- **ejercicios.md** — Ejercicios para practicar de forma autónoma y corregir en clase.

---

## Herramientas

- **Máquinas virtuales** — para instalar y probar servidores sin tocar equipos reales
- **Windows Server** — Active Directory, DNS, DHCP, recursos compartidos, copias de seguridad
- **Ubuntu Server** — administración desde la terminal: usuarios, permisos, LDAP, DNS, DHCP y FTP
- **PowerShell y terminal de Linux** — administración y comprobación de sistemas
- **PuTTY, VNC y NFS** — conexión y compartición de recursos entre equipos con distintos sistemas operativos
