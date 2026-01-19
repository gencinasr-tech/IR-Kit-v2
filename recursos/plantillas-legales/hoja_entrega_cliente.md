### **HOJA DE ENTREGA Y CIERRE DE SERVICIO DE RESPUESTA A INCIDENTES**

**Número de Caso/Incidente:** `[IR-XXXX]`
**Fecha de Entrega:** `[Fecha]`
**Referencia del Acuerdo de Servicio:** `[Firmado el Fecha]`

**ENTREGADO POR (Prestador del Servicio):**
`[Tu Nombre o Razón Social]`
Firma: _________________________

**RECIBIDO POR (Cliente):**
`[Nombre del Cliente o Empresa]`
Nombre y Cargo: `[Nombre y Cargo del firmante]`
Firma: _________________________

---

#### **1. RESUMEN DEL SERVICIO Y ESTADO FINAL**

*   **Descripción del Incidente Atendido:** `[Breve descripción, ej: "Análisis y remediación de infección por malware tipo ransomware en el equipo principal del CEO."]`
*   **Fecha de Intervención:** `[Fecha]`
*   **Estado Final del Sistema:** `[LIMPIO y OPERATIVO / DATOS RECUPERADOS / REQUIERE ACCIONES ADICIONALES (especificar)]`
*   **Horas de Servicio Facturables:** `[XX] horas`

---

#### **2. LISTA DE ENTREGABLES**

El Prestador del Servicio hace entrega al Cliente de los siguientes elementos, relacionados exclusivamente con el caso referenciado:

| #  | Tipo de Entrega | Descripción del Contenido | Formato/Soporte | Observaciones |
|:---|:----------------|:--------------------------|:----------------|:--------------|
| 1  | **Evidencia Digital Forense** | Todos los artefactos, volcados de memoria y datos de análisis recopilados durante la investigación. | Soporte físico: `[Ej: Disco SSD externo de 1TB, marca/modelo]`<br>Carpeta raíz: `EVIDENCIA_IR-XXXX` | El soporte está cifrado con BitLocker. La contraseña se ha proporcionado por separado. |
| 2  | **Informe Técnico Final** | Documento que detalla los hallazgos, metodología, IOCs, cronología y recomendaciones. | Archivo digital: `Informe_Final_IR-XXXX.pdf`<br>Copia impresa: `[Sí/No]` | Se adjunta a este acta y se encuentra también en la raíz del soporte físico. |
| 3  | **Registro de Cadena de Custodia** | Documento que rastrea la manipulación de toda la evidencia desde su recolección hasta esta entrega. | Archivo digital: `Registro_Custodia_IR-XXXX.pdf` | Firmado por el técnico. Es un anexo legal al informe. |
| 4  | **Datos Recuperados** (si aplica) | Copia de los archivos de usuario críticos recuperados durante el proceso. | Carpeta dentro del soporte físico: `_RECUPERADOS/` | Se recomienda verificar la integridad e importar estos datos al sistema limpio. |

---

#### **3. DECLARACIONES Y ACUERDOS DE CIERRE**

Al firmar este documento, ambas partes declaran y acuerdan:

1.  **Entrega Completa:** El Cliente reconoce haber recibido todos los elementos listados en la Sección 2 en las condiciones descritas.
2.  **Fin de la Custodia:** El Prestador del Servicio transfiere formalmente la custodia y responsabilidad sobre la evidencia digital y los entregables al Cliente a partir de esta fecha.
3.  **Confidencialidad:** Ambas partes reafirman su compromiso de mantener la confidencialidad de toda la información intercambiada, tal como se establece en el Acuerdo de Servicio inicial.
4.  **Destrucción de Copias:** El Prestador del Servicio se compromete a eliminar de forma segura cualquier copia de los datos del Cliente que permanezca en sus sistemas, dentro del plazo acordado (`[ej: 30 días]`), salvo obligación legal de retención.
5.  **Soporte Post-Incidente:** Los servicios de respuesta a incidentes se consideran completos. Cualquier soporte técnico futuro, implementación de recomendaciones o nuevo análisis requerirá un nuevo acuerdo de servicio.

---

#### **4. PRÓXIMOS PASOS RECOMENDADOS PARA EL CLIENTE**

Se recuerda al Cliente la importancia crítica de ejecutar las siguientes acciones, tal como se detallan en el Informe Final:

-   [ ] **Cambiar todas las contraseñas** (cuentas de Windows, email corporativo, servicios en la nube) **desde un dispositivo limpio**.
-   [ ] **Invalidar tokens de sesión y claves API** que pudieran estar comprometidas.
-   [ ] **Auditar otros sistemas** en la red para detectar posibles movimientos laterales.
-   [ ] **Considerar la implementación** de las recomendaciones de seguridad a medio y largo plazo expuestas en el informe.

---

**Este documento, junto con el Informe Final y el Registro de Custodia, constituye la clausura formal del servicio de respuesta a incidentes `[IR-XXXX]`.**

**Firmado en `[Ciudad]`, a `[día]` de `[mes]` de `[año]`.**
