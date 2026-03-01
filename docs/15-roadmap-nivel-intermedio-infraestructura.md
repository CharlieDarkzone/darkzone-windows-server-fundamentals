# 15 - Roadmap Nivel Intermedio hacia Infraestructura (Active Directory)

## 🎯 Objetivo

Definir las competencias necesarias para avanzar desde administración básica de Active Directory hacia un perfil de Infraestructura con responsabilidad real sobre el dominio corporativo.

Este documento establece el siguiente nivel de madurez técnica.

---

# 🧠 Nivel Actual (Base ya lograda)

Actualmente se domina:

- Instalación de Windows Server
- Creación de Dominio
- Diseño de OU
- Creación y vinculación de GPO
- Filtrado de seguridad por grupos
- Precedencia y Enforced
- Modelo de excepciones
- Validación con gpresult
- Troubleshooting de aplicación de políticas

Esto corresponde a un nivel Intermedio Inicial en AD.

---

# 🚀 Nivel Intermedio – Objetivos Técnicos

## 1️⃣ Delegación de Control en AD

Aprender a:

- Delegar administración por OU
- Permitir que ciertos usuarios creen cuentas sin ser Domain Admin
- Aplicar principio de mínimo privilegio

Ruta técnica:

Active Directory Users and Computers
→ Delegation of Control


---

## 2️⃣ Modelo de Privilegios (Tiering Model)

Comprender:

- Tier 0 (Domain Controllers, Admins)
- Tier 1 (Servidores)
- Tier 2 (Workstations)

Objetivo:
Evitar movimiento lateral en caso de compromiso.

---

## 3️⃣ Hardening del Domain Controller

Aprender a:

- Revisar cuentas privilegiadas
- Restringir logon a DC
- Deshabilitar protocolos inseguros
- Aplicar recomendaciones CIS

---

## 4️⃣ Gestión Avanzada de GPO

- WMI Filters
- Loopback Processing
- Starter GPO
- Central Store
- Backup y Restore de GPO

---

## 5️⃣ Auditoría y Logs

- Advanced Audit Policy
- Event Viewer
- Seguimiento de cambios en AD
- Auditoría de membresías críticas

---

## 6️⃣ Integración con Linux

Integrar:

- Ubuntu Server al dominio
- Autenticación vía Kerberos
- SSSD
- Samba como miembro de dominio

Esto eleva el perfil a entorno híbrido.

---

# 🏗️ Competencias Clave a Desarrollar

- Pensamiento estructural
- Diseño escalable
- Gestión de privilegios
- Gobernanza de acceso
- Documentación técnica formal

---

# 🧭 Meta Profesional

Transicionar desde:

"Administrador que configura"

hacia:

"Administrador que diseña, controla y gobierna la infraestructura"

---

