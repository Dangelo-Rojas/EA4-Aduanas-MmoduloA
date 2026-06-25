# EA4-Aduanas-MmoduloA
# Sistema Integrado de Modernización de Pasos Fronterizos - Módulo A
**Asignatura:** Ingeniería de Software (RQY1102)  
**Evaluación:** EA4 - Encargo Grupal  
**Institución:** DuocUC  
**Caso de Estudio:** Servicio Nacional de Aduanas (SNA) - Paso Fronterizo Los Libertadores  

##  Integrantes
* Dangelo Rojas 
* Francisco Yáñez

---

##  1. Foco del Prototipo: Módulo A
Este repositorio contiene el prototipo funcional, interactivo y navegable enfocado en el **Módulo A: Pre-declaración digital del viajero**, abordando el proceso crítico de declaración jurada obligatoria antes del arribo de los pasajeros al complejo fronterizo terrestre.

### Objetivos del Módulo:
* **Reducción de tiempos de atención:** Mitigar el cuello de botella en ventanilla permitiendo la autoatención previa.
* **Rigor Legal:** Integrar las normativas vigentes del Servicio Nacional de Aduanas (SNA), Servicio Agrícola y Ganadero (SAG) y la Policía de Investigaciones (PDI).
* **Conectividad Offline:** Provisión de un comprobante con Código QR con metadatos de validación para su uso sin internet en la alta cordillera.

---

##  2. Tecnologías Utilizadas e IA Co-Pilot
* **Google AI Studio (Gemini 1.5):** Utilizado como asistente de ingeniería de software para el co-diseño de reglas de negocio complejas, validación de flujos condicionales y generación estructurada del código frontend.
* **Stack Tecnológico:** HTML5, CSS3 Nativo (Diseño institucional SNA) y JavaScript Vanilla (Lógica SPA - Single Page Application).
* **Control de Versiones:** Git & GitHub.

---

##  3. Matriz de Mejora y Trazabilidad (Bitácora de Desarrollo)
Siguiendo los criterios de calidad e iteración solicitados en la pauta de evaluación, el prototipo evolucionó a través de los siguientes hitos (verificables en el historial de commits):

| Hito / Versión | Descripción del Cambio / Mejora | Feedback / Justificación Técnica |
| :--- | :--- | :--- |
| **v1.0.0** | Estructura base y login simulado. | Creación del flujo inicial de pantallas y esqueleto en Google AI Studio. |
| **v1.1.0** | Control de acceso diferenciado (ClaveÚnica vs Pasaporte). | Permite gestionar flujos alternativos para chilenos residentes y turistas extranjeros. |
| **v1.2.0** | Segmentación intermedia: Personas vs Carga Comercial. | Escalabilidad del sistema para atender tanto a particulares como a choferes de camiones. |
| **v1.3.0** | Formulación con Rigor Legal Exhaustivo (SNA/SAG/PDI). | Inclusión de banners de advertencia penal por perjurio, tablas de mercancía >US$500 y campos de minoría de edad con folios notariales. |
| **v1.4.0** | Lógica de salida post-QR y redirección institucional. | Permite la atención en bucle ("Realizar otro trámite") o salida segura a una página neutra informativa. |

---

## 🚀 4. Cómo Ejecutar el Prototipo
1. Descarga el archivo `index.html` de este repositorio.
2. Haz doble clic sobre el archivo para abrirlo en cualquier navegador web moderno (Chrome, Edge, Firefox, Safari).
3. No requiere instalaciones de servidores locales ni dependencias externas (Cumple con los atributos de portabilidad y eficiencia de desempeño de la norma ISO 25010).
