# 📊 AUDITORÍA DE ACCESOS A SERVIDORES

## 1. OBJETIVO

Verificar que todos los accesos a los servidores cumplan con la política de seguridad establecida.

---

## 2. ALCANCE

- SCP (Linux)
- ANALÍTICA (Windows)
- VPN

---

## 3. ELEMENTOS A AUDITAR

### Accesos

- Usuarios que ingresaron
- Fecha y hora
- IP de origen

---

### Actividad

- Comandos ejecutados (Linux)
- Sesiones RDP (Windows)

---

### Validación

- Existencia de solicitud
- Existencia de aprobación
- Vigencia del acceso

---

## 4. FRECUENCIA

- Auditoría semanal
- Auditoría mensual

---

## 5. HERRAMIENTAS

### Linux

- /var/log/auth.log
- auditd

---

### Windows

- Event Viewer
- Logs de seguridad

---

### VPN

- Logs de conexión

---

## 6. CRITERIOS DE ALERTA

Se considerará alerta cuando:

- Acceso sin registro
- Acceso fuera de horario
- Acceso sin solicitud
- Acceso con privilegios indebidos

---

## 7. ACCIONES

En caso de detección:

1. Bloqueo de usuario
2. Registro del incidente
3. Notificación
4. Revisión del acceso

---

## 8. EVIDENCIA

Toda auditoría debe generar:

- Reporte
- Logs
- Validación de accesos

---

## 9. RESPONSABLE

Administrador de sistemas

---

## 10. CONCLUSIÓN

Todo acceso debe ser:

- Justificado
- Autorizado
- Registrado
- Auditable
