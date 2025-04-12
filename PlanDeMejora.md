**Título:**  
Implementación del Método Kaizen para Organizar Apuntes Académicos en Obsidian: Un Enfoque de 14 Días  

**Autor:**  
Jesus Rodolfo Gil Farias
[12 de abril de 2025]  

---

### **Resumen**  
Este documento propone un plan de 14 días para transformar un sistema de apuntes digitales desorganizados (basados en archivos markdown dispersos) en una estructura jerárquica y eficiente en Obsidian. Aplicando los principios Kaizen de mejoras graduales, se abordarán etapas como la eliminación de notas redundantes, la creación de una taxonomía académica y la implementación de metadatos automatizados. Palabras clave: Kaizen, Obsidian, organización académica, gestión del conocimiento, productividad.  

---

### **Introducción**  
La falta de estructura en los apuntes digitales genera ineficiencias en la recuperación y conexión de información (Bush, 1945). Este plan aplica el método Kaizen para resolver este problema, migrando progresivamente archivos markdown desorganizados a un *vault* de Obsidian con categorías claras, etiquetas y flujos de trabajo estandarizados. El enfoque prioriza cambios pequeños y medibles para evitar la sobrecarga cognitiva.  

---

### **Objetivo Específico**  
**Meta:**  
*Crear un sistema de apuntes académicos en Obsidian con una estructura intuitiva (organizada por materia, semestre, profesor y tema), logrando una reducción del 70% en el tiempo de búsqueda de información y eliminando el 100% de las notas duplicadas o vacías en 14 días.*  

**Criterios de éxito medibles:**  
1. Eliminar todas las notas vacías o duplicadas (identificadas en el Día 1).  
2. Estructurar el 100% de las notas en carpetas y subcarpetas temáticas.  
3. Implementar un sistema de etiquetas y enlaces que conecte el 80% de las notas relacionadas.  

---

### **Plan de Ejecución en 14 Días**  
*(Basado en principios Kaizen: eliminación de desperdicios, estandarización y mejora continua)*  

---

#### **Fase 1: Días 1-3 (Limpieza y Fundamento)**  
- **Día 1: Creación del Vault y Estructura basada en semestres**  
  - **Acción:** Crear un *vault* nuevo en Obsidian titulado "UCAB".  
  - Establecer carpetas principales por semestre:**  
    - 1. Mover materias a sus semestres correspondientes 
  - **Documentación:**  [Día 1 - 29/03/2025](dias/Dia1_2025-03-29.md)

- **Día 2: Estructura Básica de Carpetas**  
  - **Acción:** Crear carpetas principales en el vault:  
  - Crear plantillas estandarizadas para profesores y materias.
  - Integrar el _vault_ de Obsidian con Git para control de versiones.
  - Configurar Git LFS (_Large File Storage_) para gestionar archivos binarios (PDFs, imágenes).
  - **Documentación**: [Día 2 - 30/03/2025](dias/Dia2_2025-03-30.md)



- **Día 3: Crear un **sistema integrado de calendario y seguimiento de tareas** en Obsidian que permita:

	1. Visualizar plazos académicos clave (exámenes, entregas).
	2. Planificar sesiones de estudio diarias/semanales.
	3. Vincular tareas directamente con apuntes y recursos.
	- **Documentación**: [Día 3 - 31/03/2025](dias/Dia3_2025-03-31.md)

---

#### **Fase 2: Días 4-7 (Organización Jerárquica)**  
- **Día 4: Documento De Enlace**
  - **Acción:** crear una plantilla que sirva como documento de e
  - **Documentación**: [Día 4 - 01/04/2025](dias/Dia4_2025-04-01.md)

- **Día 5: Planificación de Clases**  
  - **Acción:** Crear una planificación interna para las clases. Ejemplo:  
    ```  
      ### Temas
      #### Dudas
	 ``` 
- **Documentación:** [Día 5 - 02/04/2025](dias/Dia5_2025-04-02.md)

- **Día 6: indexar los datos con la plantilla de la meteria**  
  - **Acción:**instanciar la plantilla en cada materia.:  
    ```markdown  
    # materia
    - **temas:** [[Matemáticas Avanzadas]]  
    -  
    ```  
  - **Documentación:** [Día 6 - 03/04/2025](dias/Dia6_2025-04-03.md)

- **Día 7: Temas Clave y Enlaces**  
  - **Acción:** Crear pizarras y llevar la clase a un método mas visual vincularlas a materias y clases.  
  - **Documentación:** [Día 7 - 04/04/2025](dias/Dia7_2025-04-04.md)

---

#### **Fase 3: Días 8-10 (Sistema de Temas y Automatización)**

- ### **Día 8: Plantilla de Seguimiento de Temas**
    
    - **Objetivo:** Crear sistema centralizado para monitorear avances por materia.
        
    - **Acciones:**
        
        1. Crear plantilla `/Plantillas/Seguimiento Temas.md`
            
        2. Aplicar a 3 materias prioritarias
            
        3. Documentar en [Día 8 - 05/04/2025](dias/Dia8_2025-04-05.md)
            
    - **Resultado:** Vista unificada de progreso académico.
        
- ### **Día 9: Prompt para Extracción de Temas**
    
    - **Objetivo:** Agilizar identificación de contenidos clave.
        
    - **Acciones:**
        
        1. Desarrollar prompt estándar para análisis de materias
            
        2. Probar en 2 asignaturas
            
        3. Documentar en [Día 9 - 06/04/2025](dias/Dia9_2025-05-06.md)
            
    - **Resultado:** Método rápido para mapeo curricular.
        
- ### **Día 10: Implementación Masiva y Biblioteca de Prompts**
    
    - **Objetivo:** Escalar sistema a todas las materias.
        
    - **Acciones:**
        
        1. Ejecutar prompt en 5 materias
            
        2. Crear `/Sistema/Prompts.md`
            
        3. Documentar en [Día 10 - 07/04/2025](dias/Dia10_2025-04-07.md)
            
        

---

#### **Fase 4: Días 11-13 (Optimización del Flujo de Estudio)**

- ### **Día 11: Sistema de Alertas Académicas**
    
    - **Objetivo:** Automatizar recordatorios clave
        
    - **Acciones:**
        
        1. Configurar recordatorios recurrentes para:
            
            - 📅 Revisiones semanales (viernes 4pm)
                
            - 📚 Sesiones de repaso (diarias 7pm)
                
            - 🧠 Autoevaluaciones (domingos 10am)
                
        2. Vincular cada alerta a su nota correspondiente
            
        3. Documentar en [Día 11 - 08/04/2025](dias/Dia11_2025-04-08.md)
            
- ### **Día 12: Tablero de Proyectos y Tareas**
    
    - **Objetivo:** Crear tablero Kanbas para seguimiento 
        
    - **Acciones:**
            
        4. Documentar en [Día 12 - 09/04/2025](dias/Dia12_2025-04-09.md)
            
- ### **Día 13: Documentación del Sistema**
    
    - **Objetivo:** Crear `Manual del Usuario` 
        Documentar en [Día 13 - 10/04/2025](dias/Dia13_2025-04-10.md)

---

#### **Día 14: Retrospectiva Kaizen y Sostenibilidad**  
- **Acción 1:** Comparar métricas iniciales y finales (ej.: tiempo de búsqueda de notas).  
- **Acción 2:** Crear una nota "Manual de Mantenimiento" con reglas para futuras actualizaciones.  
- **Acción 3:** Programar revisiones semanales de 15 minutos para evitar desorganización.  
- **Documentación:** [Día 14 - 11/04/2025](dias/Dia14_2025-04-11.md)

---

### **Documentación del Proceso**  
- **Bitácora Kaizen en Obsidian:**  
  ```markdown  
  ## Día 1 - 20/Oct/2023  
  - **Acción:** Eliminadas 12 notas vacías y 8 duplicados.  
  - **Resultado:** Vault reducido en un 15%.  
  - **Reflexión:** Las notas duplicadas surgieron por falta de naming conventions.  
  ```  


---

### **Conclusión**  
Este plan transformará caos en orden mediante mejoras mínimas pero consistentes, alineadas con la filosofía Kaizen. La estructura resultante no solo optimizará la gestión de apuntes, sino que sentará las bases para un sistema escalable y adaptable a futuros semestres.  

---

### **Referencias**  
Imai, M. (1986). *Kaizen: The Key to Japan’s Competitive Success*. McGraw-Hill.  
Obsidian. (2021). *Core Plugins Documentation*. https://help.obsidian.md  

--- 

**Nota:** Ajuste los nombres de carpetas y plugins según sus necesidades académicas. Para citas adicionales, agregue referencias APA relevantes.