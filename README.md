# 🧪 Windows Server Lab – Darkzone

Laboratorio práctico de **administración de sistemas Windows Server**, enfocado en la implementación de un **dominio Active Directory** en un entorno virtualizado con **QEMU/KVM**.

El proyecto documenta paso a paso la instalación, configuración y puesta en marcha de un dominio Windows funcional, siguiendo buenas prácticas de sysadmin y documentación técnica.

---

## 🧠 Objetivo del proyecto

* Aprender administración de **Windows Server 2022**
* Implementar un dominio **Active Directory**
* Configurar servicios básicos de infraestructura:

  * DNS
  * Gestión de usuarios y equipos
* Comprender la interacción entre servidor y cliente en un entorno de dominio
* Documentar el proceso de forma clara y reproducible
* Construir material para **portafolio profesional**

---

## 🧱 Arquitectura del laboratorio

* Dominio: `darkzone.cl`
* Entorno virtualizado con QEMU/KVM
* Un controlador de dominio
* Un equipo cliente unido al dominio

📁 El diagrama de arquitectura se encuentra en la carpeta `diagrama/`.

---

## 🖥️ Componentes

### 🔹 Servidor (DC01)

* Sistema Operativo: Windows Server 2022
* Roles:

  * Active Directory Domain Services (AD DS)
  * DNS Server
* IP: 192.168.100.10 (estática)

### 🔹 Cliente (PC01)

* Sistema Operativo: Windows 10 Pro
* IP: Asignada por DHCP
* Unido al dominio `darkzone.cl`

---

## 📂 Estructura del repositorio

```
Laboratorios/
└── 01-ActiveDirectory/
    └── windows-server-lab-darkzone/
        ├── docs/
        ├── diagrama/
        ├── capturas/
        └── README.md
```

---

## 📝 Documentación

La documentación del laboratorio se encuentra en la carpeta `docs/` y está organizada por etapas, de forma progresiva y reproducible.

Actualmente incluye:

1. **Instalación de Windows Server en QEMU/KVM**
2. **Configuración de red e IP estática** (en progreso)
3. **Creación del dominio Active Directory** (en progreso)

Cada documento incluye explicación técnica, comandos utilizados y capturas del proceso.

---

## 📸 Evidencias

* Inicio de sesión en dominio
* Creación de usuarios en Active Directory
* Cliente unido al dominio
* Resolución DNS funcionando correctamente

📁 Las capturas se encuentran en la carpeta `capturas/`.

---

## ⚙️ Tecnologías utilizadas

* QEMU / KVM
* Windows Server 2022
* Windows 10 Pro
* Active Directory Domain Services (AD DS)
* DNS
* Git & GitHub
* draw.io (diagramas)

---

## 🧠 Aprendizajes

* Comprensión del funcionamiento de Active Directory en entornos empresariales
* Importancia del servicio DNS dentro del dominio
* Gestión centralizada de usuarios y equipos
* Integración de cliente Windows a un dominio
* Resolución de problemas de conectividad en entornos virtualizados
* Organización y documentación de laboratorios técnicos

---

## 🔐 Próximas mejoras (Seguridad)

* Implementación de políticas GPO avanzadas
* Hardening de Windows Server basado en CIS Benchmarks
* Auditoría de eventos en Active Directory
* Gestión de privilegios y control de accesos
* Simulación de escenarios de ataque y defensa

---

## 🚀 Estado del proyecto

🟡 **En desarrollo**

El laboratorio se construye de forma incremental, agregando configuraciones reales y documentación a medida que se avanza en el aprendizaje de administración de sistemas y ciberseguridad.

🔄 Continuación

Este laboratorio forma parte de un entorno más amplio de infraestructura.

➡️ Proyecto relacionado: darkzone-infrastructure-lab

Donde se abordan:

Redes empresariales

Seguridad

Servicios adicionales

Arquitectura de sistemas

👤 Autor

Proyecto personal con fines educativos, orientado al desarrollo de habilidades en:

Administración de sistemas

Infraestructura Windows

Active Directory

Ciberseguridad

Documentación técnica profesional
