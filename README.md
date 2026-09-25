# Ciclo de Vida de un Sistema de Información

Aquí tienes el organizador gráfico basado en la teoría de los sistemas de información:

```mermaid
graph TD
    Root[<b>Ciclo de Vida de un Sistema de Información</b>]
    
    Root --> Phases[<b>Fases del Ciclo de Vida</b>]
    Root --> Scope[<b>Delimitación del Ámbito</b>]
    Root --> Feasibility[<b>Estudio de Viabilidad</b>]
    Root --> Risk[<b>Análisis de Riesgos</b>]
    Root --> Models[<b>Modelos de Ciclo de Vida</b>]
    
    Phases --> Planning[<b>1. Planificación</b><br/>Tareas previas para el éxito del proyecto]
    Phases --> Analysis[<b>2. Análisis</b><br/>Descubrir requerimientos y necesidades reales]
    Phases --> Design[<b>3. Diseño</b><br/>Estudio de alternativas y diseño arquitectónico<br/><i>(Iterativo)</i>]
    Phases --> Implementation[<b>4. Implementación</b><br/>Selección de herramientas, entorno y lenguaje]
    Phases --> Testing[<b>5. Pruebas</b><br/>Detección y corrección de errores]
    Phases --> Deployment[<b>6. Instalación/Despliegue</b><br/>Configuración de hardware, software y redes]
    Phases --> Maintenance[<b>7. Uso y Mantenimiento</b><br/>Consumo del 40-80% de los recursos<br/><i>(Etapa más importante)</i>]
    
    Scope --> ScopeDesc[<b>Delimitación</b><br/>Fijar límites y exclusiones del proyecto]
    
    Feasibility --> FeasDesc[<b>Viabilidad</b><br/>Evaluar recursos limitados vs. viabilidad del proyecto]
    
    Risk --> RiskDesc[<b>Riesgos</b><br/>Evaluación y control de contratiempos]
    
    Models --> Cascade[<b>Ciclo de Vida Clásico (Cascada)</b><br/>Secuencial<br/>Verificación y validación en cada etapa<br/>Proceso de 'hacer las cosas bien desde el principio']
