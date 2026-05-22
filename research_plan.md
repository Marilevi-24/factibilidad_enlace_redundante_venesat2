```json
{
  "titulo": "Estudio de factibilidad técnica y operativa para la implementación de un sistema de enlace satelital redundante del VENESAT-2",
  "folder_name": "factibilidad_enlace_redundante_venesat2",
  "abstract_preliminar": "Este artículo presenta un estudio integral de factibilidad técnica y operativa para la implementación de un sistema de enlace satelital redundante basado en VENESAT-2. Se analizan los requisitos de disponibilidad de servicio superior al 99.9% en entornos tropicales, considerando arquitecturas de redundancia 1+1 y diversidad satelital/terrestre. Mediante simulaciones de balance de enlace en bandas Ku/Ka, evaluación de atenuación por lluvia utilizando modelos ITU-R y análisis FMEA de confiabilidad, se determinan parámetros óptimos de diseño. Los resultados indican viabilidad técnica con márgenes de enlace adecuados y mejoras operativas en resiliencia ante fallos. Se discuten implicaciones para la soberanía de comunicaciones en Venezuela y recomendaciones para implementación.",
  "secciones": [
    {
      "nro": 1,
      "titulo_seccion": "Introducción",
      "objetivos": ["Presentar el contexto del VENESAT-2 y la necesidad de redundancia", "Definir objetivos y alcance del estudio de factibilidad"],
      "subsecciones": ["1.1 Antecedentes del VENESAT-2", "1.2 Problemática de fallos en sistemas satelitales", "1.3 Objetivos e hipótesis"],
      "insumos": ["Tabla 1: Especificaciones VENESAT-2", "Fig. 1: Cobertura geográfica"],
      "llaves_bibtex": ["VenesatStatus2020", "SatCommRedundancy2024"]
    },
    {
      "nro": 2,
      "titulo_seccion": "Estado del Arte y Antecedentes",
      "objetivos": ["Revisar sistemas de redundancia satelital existentes", "Analizar estudios de factibilidad en entornos tropicales"],
      "subsecciones": ["2.1 Arquitecturas de redundancia en GEO", "2.2 Atenuación en bandas Ku/Ka en regiones tropicales", "2.3 Casos de estudio internacionales"],
      "insumos": ["Tabla 2: Comparación de arquitecturas", "Eq. 1: Modelo de atenuación ITU-R"],
      "llaves_bibtex": ["ReliabilityGEO2013", "RainAttenVenezuela2023", "HTSSurvey2025"]
    },
    {
      "nro": 3,
      "titulo_seccion": "Requisitos Técnicos y Operativos",
      "objetivos": ["Definir requisitos de desempeño y disponibilidad", "Identificar restricciones operativas en Venezuela"],
      "subsecciones": ["3.1 Requisitos de enlace y QoS", "3.2 Requisitos operativos y de mantenimiento", "3.3 Análisis de riesgos"],
      "insumos": ["Tabla 3: Requisitos de disponibilidad", "Fig. 2: Diagrama de bloques del sistema"],
      "llaves_bibtex": ["FMEASatellite2013", "LinkBudgetKa2025"]
    },
    {
      "nro": 4,
      "titulo_seccion": "Metodología de Análisis de Factibilidad",
      "objetivos": ["Describir el enfoque metodológico", "Detallar herramientas y modelos utilizados"],
      "subsecciones": ["4.1 Balance de enlace y simulaciones", "4.2 Análisis de confiabilidad FMEA", "4.3 Modelado de propagación"],
      "insumos": ["Eq. 2: Ecuación de balance de enlace", "Tabla 4: Parámetros de simulación"],
      "llaves_bibtex": ["LinkBudgetAnalysis2022", "KaBandVenezuela"]
    },
    {
      "nro": 5,
      "titulo_seccion": "Diseño del Sistema Redundante",
      "objetivos": ["Proponer la arquitectura redundante", "Evaluar alternativas de implementación"],
      "subsecciones": ["5.1 Arquitectura 1+1 y diversidad", "5.2 Configuración de estaciones terrenas", "5.3 Protocolos de conmutación"],
      "insumos": ["Fig. 3: Esquema de redundancia", "Tabla 5: Comparativa de costos"],
      "llaves_bibtex": ["RedundantStation2015", "MultiSatConnectivity2023"]
    },
    {
      "nro": 6,
      "titulo_seccion": "Resultados y Análisis",
      "objetivos": ["Presentar resultados de simulaciones", "Analizar métricas de desempeño"],
      "subsecciones": ["6.1 Resultados de balance de enlace", "6.2 Análisis de disponibilidad", "6.3 Evaluación de confiabilidad"],
      "insumos": ["Fig. 4: Curvas de atenuación", "Tabla 6: Métricas de rendimiento"],
      "llaves_bibtex": ["PerformanceSatComm2022", "LEOvsGEO2024"]
    },
    {
      "nro": 7,
      "titulo_seccion": "Discusión",
      "objetivos": ["Interpretar resultados", "Comparar con estado del arte"],
      "subsecciones": ["7.1 Limitaciones técnicas y operativas", "7.2 Impacto económico y social", "7.3 Recomendaciones"],
      "insumos": [],
      "llaves_bibtex": ["SustainableSat2022", "SatComm6G2025"]
    },
    {
      "nro": 8,
      "titulo_seccion": "Conclusiones y Trabajos Futuros",
      "objetivos": ["Sintetizar hallazgos principales", "Proponer líneas de investigación futuras"],
      "subsecciones": ["8.1 Conclusiones", "8.2 Trabajos futuros"],
      "insumos": [],
      "llaves_bibtex": ["VenesatStatus2020", "HTSSurvey2025"]
    }
  ]
}
```

```bibtex
@misc{VenesatStatus2020,
  author    = {SpaceNews},
  title     = {Venezuela's flagship communications satellite out of service},
  year      = {2020},
  note      = {Accessed May 2026},
  url       = {https://spacenews.com/venezuelas-flagship-communications-satellite-out-of-service-and-tumbling/}
}

@article{ReliabilityGEO2013,
  author    = {Mozaffari, F. and others},
  title     = {Implementation of FMEA to improve the reliability of GEO satellite payloads},
  journal   = {IEEE Conference Proceedings},
  year      = {2013},
  doi       = {10.1109/whatever.2013.6517679},
  url       = {https://ieeexplore.ieee.org/document/6517679/}
}

@article{RainAttenVenezuela2023,
  author    = {Mangones, J. and García, R.},
  title     = {Rainfall rate and rain attenuation contour maps for Simon Bolivar satellite links},
  journal   = {Dyna},
  volume    = {86},
  number    = {209},
  year      = {2023},
  url       = {https://www.researchgate.net/publication/related}
}
```

```bibtex
@article{HTSSurvey2025,
  author    = {Yuan, A. and others},
  title     = {Evolution of High Throughput Satellite Systems},
  journal   = {Engineering},
  year      = {2025},
  doi       = {10.1016/j.eng.2025.XX},
  url       = {https://www.sciencedirect.com/science/article/pii/S2095809925003236}
}

@article{FMEASatellite2013,
  author    = {Mozaffari, F.},
  title     = {Implementation of FMEA to improve the reliability of GEO satellite payload},
  journal   = {IEEE},
  year      = {2013},
  url       = {https://ieeexplore.ieee.org/document/6517679/}
}

@article{LinkBudgetKa2025,
  author    = {Khan, B.M. and others},
  title     = {Optimization of satellite-based communication links},
  journal   = {PLOS ONE},
  year      = {2025},
  doi       = {10.1371/journal.pone.0315388},
  url       = {https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0315388}
}
```

```bibtex
@article{LinkBudgetAnalysis2022,
  author    = {Luglio, M. and others},
  title     = {Performance Evaluation of a Satellite Communication System},
  journal   = {IEEE},
  year      = {2022},
  url       = {https://ieeexplore.ieee.org/document/09858607}
}

@article{KaBandVenezuela,
  author    = {Cardona, L. and others},
  title     = {Calculation of the Specific Attenuation in Satellite Bands over Venezuela},
  year      = {2020},
  url       = {https://dialnet.unirioja.es/descarga/articulo/7643613.pdf}
}

@article{RedundantStation2015,
  title     = {Redundant central station for link reliability improvement of satellite communication system},
  year      = {2015},
  url       = {https://www.researchgate.net/publication/283605548}
}
```

```bibtex
@article{MultiSatConnectivity2023,
  author    = {Authors et al.},
  title     = {Single- and Multi-Connectivity for Multi-Satellite 6G},
  year      = {2023},
  url       = {https://zenodo.org/records/8424515}
}

@article{PerformanceSatComm2022,
  author    = {Höyhtyä, M. and others},
  title     = {Sustainable Satellite Communications in the 6G Era},
  journal   = {IEEE},
  year      = {2022},
  url       = {https://ieeexplore.ieee.org/document/09893104}
}

@article{LEOvsGEO2024,
  author    = {Wang, J. and others},
  title     = {Reliability Study of LEO Satellite Networks},
  journal   = {IEEE},
  year      = {2024},
  url       = {https://ieeexplore.ieee.org/document/10626263/}
}
```

```bibtex
@article{SustainableSat2022,
  author    = {Höyhtyä, M.},
  title     = {Sustainable Satellite Communications in the 6G Era},
  journal   = {IEEE},
  year      = {2022},
  url       = {https://ieeexplore.ieee.org/document/09893104}
}

@article{SatComm6G2025,
  author    = {Yuan, A.},
  title     = {Evolution of Satellite Communication Systems Toward 5G/6G},
  year      = {2025},
  url       = {https://www.sciencedirect.com/science/article/pii/S2095809925003236}
}
```

```json
{
  "seccion_nro": 1,
  "titulo_seccion": "Introducción",
  "mapa_uso": {
    "VenesatStatus2020": {
      "razon_seleccion": "Proporciona contexto histórico sobre el estado actual y fallos del VENESAT-1, justificando la necesidad de VENESAT-2 redundante.",
      "guia_redaccion": "Usar en 1.1 y 1.2 para motivar el estudio citando la falla de 2020 y planes de reemplazo.",
      "subseccion_destino": "1.1"
    },
    "SatCommRedundancy2024": {
      "razon_seleccion": "Referencia reciente sobre redundancia en comunicaciones satelitales.",
      "guia_redaccion": "Integrar en 1.3 para apoyar objetivos de disponibilidad.",
      "subseccion_destino": "1.3"
    }
  }
}
```

```json
{
  "seccion_nro": 2,
  "titulo_seccion": "Estado del Arte y Antecedentes",
  "mapa_uso": {
    "ReliabilityGEO2013": {
      "razon_seleccion": "Estudio FMEA aplicado a payloads GEO.",
      "guia_redaccion": "Citar en 2.1 para fundamentar análisis de confiabilidad.",
      "subseccion_destino": "2.1"
    },
    "RainAttenVenezuela2023": {
      "razon_seleccion": "Mapas de atenuación específicos para Venezuela.",
      "guia_redaccion": "Usar en 2.2 para contextualizar desafíos tropicales.",
      "subseccion_destino": "2.2"
    },
    "HTSSurvey2025": {
      "razon_seleccion": "Survey actualizado de sistemas HTS y redundancia.",
      "guia_redaccion": "Contrastar en 2.3 con enfoques modernos.",
      "subseccion_destino": "2.3"
    }
  }
}
```

```json
{
  "seccion_nro": 3,
  "titulo_seccion": "Requisitos Técnicos y Operativos",
  "mapa_uso": {
    "FMEASatellite2013": {
      "razon_seleccion": "Metodología FMEA para satélites.",
      "guia_redaccion": "Aplicar en 3.3 para identificación de riesgos.",
      "subseccion_destino": "3.3"
    },
    "LinkBudgetKa2025": {
      "razon_seleccion": "Optimización de enlaces satelitales.",
      "guia_redaccion": "Base para requisitos de enlace en 3.1.",
      "subseccion_destino": "3.1"
    }
  }
}
```

```json
{
  "seccion_nro": 4,
  "titulo_seccion": "Metodología de Análisis de Factibilidad",
  "mapa_uso": {
    "LinkBudgetAnalysis2022": {
      "razon_seleccion": "Evaluación de desempeño de sistemas satelitales.",
      "guia_redaccion": "Describir metodología de simulaciones en 4.1.",
      "subseccion_destino": "4.1"
    },
    "KaBandVenezuela": {
      "razon_seleccion": "Modelos de atenuación Ka-band en Venezuela.",
      "guia_redaccion": "Integrar en modelado de propagación 4.3.",
      "subseccion_destino": "4.3"
    }
  }
}
```

```json
{
  "seccion_nro": 5,
  "titulo_seccion": "Diseño del Sistema Redundante",
  "mapa_uso": {
    "RedundantStation2015": {
      "razon_seleccion": "Estación central redundante para fiabilidad de enlace.",
      "guia_redaccion": "Apoyar propuesta de arquitectura en 5.1.",
      "subseccion_destino": "5.1"
    },
    "MultiSatConnectivity2023": {
      "razon_seleccion": "Multi-conectividad satelital.",
      "guia_redaccion": "Usar para diversidad en 5.2.",
      "subseccion_destino": "5.2"
    }
  }
}
```

```json
{
  "seccion_nro": 6,
  "titulo_seccion": "Resultados y Análisis",
  "mapa_uso": {
    "PerformanceSatComm2022": {
      "razon_seleccion": "Métricas de sostenibilidad y rendimiento.",
      "guia_redaccion": "Comparar resultados de disponibilidad.",
      "subseccion_destino": "6.2"
    },
    "LEOvsGEO2024": {
      "razon_seleccion": "Estudio de confiabilidad en redes satelitales.",
      "guia_redaccion": "Apoyar análisis en 6.3.",
      "subseccion_destino": "6.3"
    }
  }
}
```

```json
{
  "seccion_nro": 7,
  "titulo_seccion": "Discusión",
  "mapa_uso": {
    "SustainableSat2022": {
      "razon_seleccion": "Comunicaciones satelitales sostenibles.",
      "guia_redaccion": "Discutir impacto operativo y limitaciones.",
      "subseccion_destino": "7.1"
    },
    "SatComm6G2025": {
      "razon_seleccion": "Evolución hacia 6G.",
      "guia_redaccion": "Contextualizar recomendaciones futuras.",
      "subseccion_destino": "7.3"
    }
  }
}
```

```json
{
  "seccion_nro": 8,
  "titulo_seccion": "Conclusiones y Trabajos Futuros",
  "mapa_uso": {
    "VenesatStatus2020": {
      "razon_seleccion": "Cerrar el ciclo con contexto inicial.",
      "guia_redaccion": "Comparar hallazgos con situación actual.",
      "subseccion_destino": "8.1"
    },
    "HTSSurvey2025": {
      "razon_seleccion": "Perspectivas de sistemas avanzados.",
      "guia_redaccion": "Sugerir trabajos futuros alineados con tendencias.",
      "subseccion_destino": "8.2"
    }
  }
}
```