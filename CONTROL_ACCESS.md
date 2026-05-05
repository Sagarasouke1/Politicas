# 🔐 CONTROL DE ACCESOS A SERVIDORES

## 1. OBJETIVO

Garantizar que todos los accesos a servidores se realicen bajo un esquema controlado, auditado y autorizado.

---

## 2. ALCANCE

- Servidor SCP (Linux)
- Servidor ANALÍTICA (Windows)

---

## 3. MODELO DE ACCESO

### Principios:

- Mínimo privilegio
- Acceso individual
- Acceso temporal
- Auditoría obligatoria

---

## 4. REGLAS GENERALES

- Todo acceso debe ser solicitado
- Todo acceso debe ser aprobado
- Todo acceso debe ser registrado
- Todo acceso debe expirar

---

## 5. RESTRICCIONES

- No acceso root (Linux)
- No acceso administrador (Windows)
- No accesos compartidos
- No accesos fuera de proceso

---

## 6. ACCESO POR ROL

### Administrador
- Acceso completo

### Jefe TIC
- Sin acceso a SCP
- Lectura en ANALÍTICA

### Coordinadora
- Acceso supervisado en ANALÍTICA

### Soporte
- Sin acceso

---

## 7. CONTROL DE SESIONES

- Acceso solo por VPN
- Registro de IP
- Registro de usuario
- Registro de horario

---

## 8. CADUCIDAD

- Accesos temporales: 24 horas
- Accesos permanentes: solo administradores

---

## 9. RESPONSABILIDAD

El administrador es responsable de:

- Validar accesos
- Registrar accesos
- Revocar accesos

---

## 10. INCUMPLIMIENTO

Cualquier acceso fuera de este esquema será considerado:

- Acceso no autorizado
- Violación de seguridad
