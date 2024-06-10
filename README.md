flowchart TD
    A[Inicio] --> B[Recepcion de Solicitud]
    B --> C[Reunion con el Cliente]
    C --> D[Analisis de Necesidades del Cliente]
    D --> E[Desarrollo del Concepto Inicial]
    E --> F{Aprobacion del Concepto}
    F -- No --> G[Revision del Concepto]
    G --> E
    F -- Si --> H[Diseno del Flyer]
    H --> I[Primera Version del Flyer]
    I --> J[Retroalimentacion del Cliente]
    J --> K[Ajustes y Ediciones]
    K --> I
    I --> L{Aprobacion del Cliente}
    L -- No --> K
    L -- Si --> M[Version Final del Flyer]
    M --> N[Entrega al Cliente]
    N --> O[Fin]
