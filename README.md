# m07--e2--taller-historias-usuario-estimacion-priorizacion
### Historia 1: Gestión de Citas Médicas

**Descripción:**

Como paciente, quiero agendar, modificar y cancelar mis citas médicas en línea, para gestionar mis consultas de manera eficiente sin necesidad de acudir al hospital.

**Aplicación de INVEST y SMART:**

- **Independiente:** Puede desarrollarse sin depender de otras funcionalidades.
- **Negociable:** Puede ajustarse según las necesidades del paciente y del hospital.
- **Valiosa:** Permite a los pacientes organizar mejor sus visitas.
- **Estimable:** Se puede evaluar el esfuerzo de desarrollo.
- **Small:** Se puede dividir en tareas manejables.
- **Testable:** Se puede comprobar si los pacientes pueden gestionar sus citas correctamente.

---

### Historia 2: Consulta de Historial Médico

**Descripción:**

Como médico, quiero acceder al historial médico de mis pacientes desde la plataforma, para tomar decisiones informadas sobre sus tratamientos.

**Aplicación de INVEST y SMART:**

- **Independiente:** No depende de otras funcionalidades inmediatas.
- **Negociable:** Puede ajustarse a las necesidades de seguridad del hospital.
- **Valiosa:** Mejora la eficiencia del personal médico.
- **Estimable:** Se puede calcular su esfuerzo de implementación.
- **Small:** Puede desglosarse en subtareas.
- **Testable:** Se verifica con accesos controlados y pruebas de usabilidad.

---

### Historia 3: Notificaciones de Recordatorio

**Descripción:**

Como paciente, quiero recibir recordatorios automáticos de mis próximas citas médicas, para evitar olvidarlas y asistir puntualmente.

**Aplicación de INVEST y SMART:**

- **Independiente:** Puede desarrollarse separadamente.
- **Negociable:** Puede ajustarse en tipo de notificación (SMS, correo, app).
- **Valiosa:** Reduce las ausencias en consultas.
- **Estimable:** Puede calcularse su tiempo de desarrollo.
- **Small:** Puede dividirse en tareas específicas.
- **Testable:** Se verifica enviando notificaciones de prueba.

---

## 2. Estimación Ágil de Historias de Usuario

| Historia | Estimación (Puntos de Historia/Talla) | Justificación |
|----------|--------------------------------|--------------|
| **Gestión de Citas Médicas** | 8 puntos / M | Requiere interfaz de usuario, validaciones, conexión con la base de datos y lógica para modificaciones. |
| **Consulta de Historial Médico** | 13 puntos / L | Incluye seguridad avanzada, permisos de acceso y conexión con múltiples bases de datos. |
| **Notificaciones de Recordatorio** | 5 puntos / S | Menos compleja, involucra solo integración con sistema de notificaciones y cronogramas. |

---

## 3. Priorización de Historias de Usuario (MoSCoW)

| Historia | Prioridad | Justificación |
|----------|----------|--------------|
| **Gestión de Citas Médicas** | Must Have | Es esencial para la funcionalidad principal de la plataforma. |
| **Consulta de Historial Médico** | Should Have | Importante para la toma de decisiones médicas, pero puede funcionar sin ella en una versión inicial. |
| **Notificaciones de Recordatorio** | Could Have | Beneficiosa pero no crítica en la primera entrega. |

---

## 4. Refinamiento del Backlog

- **Gestión de Citas Médicas:** Se desglosa en subtareas (crear interfaz, desarrollar API, implementar validaciones, conectar con base de datos).
- **Consulta de Historial Médico:** Se detalla la gestión de permisos y seguridad.
- **Notificaciones de Recordatorio:** Se define el canal de notificación predeterminado.

Con este refinamiento, las historias están listas para el sprint.
