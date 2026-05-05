# 🔐 Control de Accesos a Infraestructura TI  
## SCP (Linux) & ANALÍTICA (Windows)

Este repositorio define los lineamientos obligatorios para el acceso a servidores, asegurando que ningún acceso pueda realizarse fuera del flujo autorizado.

---

# 📄 PROCEDIMIENTO (NO EVASIBLE)

## 🔁 Flujo obligatorio

1. Solicitud formal
   - Link: https://forms.gle/79NtAivtMB2Z13Rm9
3. Justificación documentada  
4. Aprobación previa  
5. Asignación de acceso  
6. Registro en logs  
7. Revocación automática  

---

## ❗ Regla de validación

Si alguno de los pasos no se cumple, el acceso se considera **NO AUTORIZADO**.

---

## ⏳ Vigencia

- Temporal: 24 horas  
- Permanente: solo administradores  

---

## 🚫 Prohibiciones

- Accesos sin solicitud  
- Accesos sin aprobación  
- Accesos sin registro  
- Accesos por solicitud verbal  

---

# 📊 MATRIZ DE ACCESOS (DEFENSIVA)

| Rol | SCP (Linux) | ANALÍTICA (Windows) | Nivel |
|-----|------------|--------------------|------|
| Admin Sistemas | Completo | Completo | Total |
| Jefe TIC | ❌ | Lectura | Limitado |
| Coordinadora | ❌ | Supervisado | Parcial |
| Soporte | ❌ | ❌ | Restringido |

---

## 🔐 Regla clave

No se otorgan accesos por jerarquía, solo por función.

---

# 📄 ESTÁNDAR TÉCNICO (OBLIGATORIO)

## 🐧 Linux (SCP)

- SSH con llave  
- Root deshabilitado  
- sudo restringido  
- Logs activos  

---

## 🪟 Windows (ANALÍTICA)

- RDP controlado  
- Usuarios estándar  
- Auditoría activa  

---

## 🌐 VPN

- Acceso obligatorio  
- Registro de sesión  

---

## 📊 Logs

- SSH  
- RDP  
- VPN  

---

## 🚫 Prohibiciones técnicas

- Acceso sin VPN  
- Credenciales compartidas  
- Privilegios sin autorización  

---

# 🔥 CONCLUSIÓN

Este esquema garantiza control, auditoría y cumplimiento de seguridad TI.
