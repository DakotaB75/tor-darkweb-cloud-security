<p align="center">
  <img src="./Tor.png" width="100%" alt="Tor Dark Web Cloud Security">
</p>

<h1 align="center">Tor, Dark Web & Cloud Security | Capacitación</h1>

**Instructora:** Dakota Bazan  
**Área:** Cybersecurity · Threat Intelligence · OSINT · Blue Team · Cloud Security  
**Nivel:** Intermedio / Avanzado  
**Carga horaria:** 32 horas   
**Especialización Cloud:** Microsoft Azure  
**Orientación:** Investigación y ciberseguridad defensiva

---

## Sobre la capacitación

Este repositorio reúne la documentación técnica, los contenidos formativos, los recursos de aprendizaje y las actividades prácticas correspondientes a la capacitación **Tor, Dark Web & Cloud Security**.

La formación aborda el análisis de infraestructuras de anonimato, los fundamentos técnicos de la red Tor, las metodologías de investigación OSINT y los procesos de Threat Intelligence aplicados a la identificación, evaluación y contextualización de amenazas digitales.

El programa integra estos conocimientos con estrategias de defensa corporativa, seguridad de identidades, monitoreo de eventos y protección de infraestructuras Cloud, incorporando tecnologías del ecosistema Microsoft Azure.

El enfoque académico combina fundamentos de redes y criptografía, investigación de fuentes públicas, análisis de indicadores de compromiso (IoCs), seguridad perimetral y metodologías Blue Team.

El objetivo es que los participantes desarrollen competencias para interpretar escenarios de amenazas, realizar investigaciones digitales responsables y diseñar estrategias de prevención, detección y mitigación de riesgos en entornos tecnológicos.

## Instructora

**Dakota Bazan — Cloud Security**

- LinkedIn: [Dakota Bazan](https://www.linkedin.com/in/dakota-bazan/)
- Área de especialización: Threat Intelligence, OSINT, Blue Team y Cloud Security.
- Especialidad técnica: Investigación de amenazas y defensa de infraestructuras Cloud.
- Ecosistema tecnológico: Tor, Microsoft Azure y tecnologías de seguridad empresarial.

Este repositorio documenta la estructura académica de la capacitación, sus contenidos técnicos y los recursos utilizados para organizar y desarrollar el proceso formativo.

## Objetivos de aprendizaje

Al finalizar la capacitación, los participantes podrán:

- Comprender la arquitectura de la red Tor y los fundamentos de los protocolos de anonimato.
- Interpretar el funcionamiento de circuitos, relays y servicios Onion v3.
- Reconocer los fundamentos criptográficos aplicados a las comunicaciones anónimas.
- Aplicar metodologías OSINT para la investigación de amenazas digitales.
- Comprender el ciclo de vida de Threat Intelligence y sus distintos niveles de análisis.
- Identificar y contextualizar Indicadores de Compromiso (IoCs).
- Analizar información pública relacionada con ransomware, filtraciones y exposición de datos.
- Evaluar riesgos de seguridad asociados a infraestructuras de anonimato.
- Aplicar controles de seguridad de identidad mediante Microsoft Entra ID.
- Analizar registros de seguridad utilizando Kusto Query Language (KQL).
- Comprender mecanismos de protección perimetral mediante Azure Web Application Firewall.
- Diseñar entornos controlados de investigación y aplicar principios de OPSEC.
- Documentar hallazgos técnicos y elaborar recomendaciones de mitigación.

---

# Programa de contenidos

## Módulo 1. Arquitectura de red, Tor y criptografía aplicada

**Carga horaria: 8 horas**

**Contenidos:**

- Fundamentos de privacidad, anonimato y confidencialidad.
- Arquitectura distribuida de la red Tor.
- Funcionamiento de nodos Entry, Middle Relay y Exit.
- Establecimiento y funcionamiento de circuitos Tor.
- Fundamentos de Onion Routing y cifrado por capas.
- Criptografía simétrica y asimétrica aplicada a comunicaciones.
- Fundamentos de curvas elípticas y Ed25519.
- Arquitectura de servicios Onion v3.
- Direccionamiento y autenticación de servicios Onion.
- Pluggable Transports: fundamentos de obfs4 y meek.
- Resistencia a mecanismos de censura y análisis de sus implicancias.
- Consideraciones de seguridad y limitaciones de los protocolos de anonimato.

**Actividad práctica:**

Análisis técnico de la arquitectura de Tor, identificación de sus componentes y documentación del funcionamiento de circuitos y servicios Onion mediante recursos oficiales y entornos controlados.

## Módulo 2. Threat Intelligence, OSINT e investigación Dark Web

**Carga horaria: 8 horas**

**Contenidos:**

- Fundamentos y ciclo de vida de Threat Intelligence.
- Inteligencia estratégica, operacional, táctica y técnica.
- Identificación y clasificación de actores de amenazas.
- Fundamentos de Open Source Intelligence (OSINT).
- Metodologías de recopilación, validación y correlación de información.
- Evaluación de confiabilidad de fuentes digitales.
- Surface Web, Deep Web y Dark Web: características y diferencias.
- Arquitectura de acceso a servicios Onion.
- Investigación responsable de fuentes públicas relacionadas con amenazas.
- Análisis de reportes de ransomware y actividades de extorsión digital.
- Identificación de indicadores de compromiso (IoCs).
- Investigación de filtraciones y exposición de información corporativa.
- Documentación de evidencias e informes de inteligencia.
- Consideraciones legales, éticas y de seguridad durante las investigaciones.

**Actividad práctica:**

Desarrollo de un informe de Threat Intelligence a partir de fuentes públicas, con identificación de indicadores de compromiso, evaluación de confiabilidad y documentación de un escenario simulado de exposición de información.

## Módulo 3. Cloud Security, Microsoft Azure y defensa perimetral

**Carga horaria: 8 horas**

**Contenidos:**

- Fundamentos de seguridad en infraestructuras Cloud.
- Arquitectura de identidad en Microsoft Entra ID.
- Principios de Zero Trust.
- Conditional Access y políticas de acceso.
- Evaluación de riesgos de autenticación e identidad.
- Fundamentos de SIEM y XDR.
- Introducción a Microsoft Sentinel.
- Ingesta y análisis de registros de seguridad.
- Fundamentos de Kusto Query Language (KQL).
- Consultas, filtros, proyecciones y agregaciones.
- Análisis temporal y correlación de eventos.
- Identificación de patrones de actividad anómala.
- Arquitectura de seguridad perimetral en Azure.
- Azure Application Gateway y Web Application Firewall (WAF).
- Reglas administradas y personalizadas.
- Registro, análisis y mitigación de solicitudes maliciosas.

**Actividad práctica:**

Análisis de registros de seguridad mediante KQL y diseño de una estrategia defensiva para un escenario simulado de actividad sospechosa en una infraestructura Microsoft Azure.

## Módulo 4. OPSEC, laboratorios aislados y seguridad operativa

**Carga horaria: 8 horas**

**Contenidos:**

- Fundamentos de Operational Security (OPSEC).
- Gestión de exposición digital durante investigaciones.
- Protección de información sensible y metadatos.
- Riesgos asociados a DNS y exposición de direcciones IP.
- Diseño de entornos controlados de investigación.
- Aislamiento y segmentación de redes.
- Máquinas virtuales temporales en entornos Cloud.
- Gestión de identidades, permisos y privilegios.
- Fundamentos de Infraestructura como Código (IaC).
- Introducción a Azure Bicep y Terraform.
- Configuración declarativa de infraestructura.
- Reproducibilidad y control de cambios.
- Fundamentos de respuesta ante incidentes (Incident Response).
- Identificación, clasificación y documentación de incidentes.
- Preservación de evidencias digitales.
- Estrategias de contención y mitigación.
- Elaboración de informes y recomendaciones defensivas.

**Actividad práctica:**

Diseño documental de un laboratorio de investigación aislado, elaboración de un checklist de OPSEC y desarrollo de un procedimiento de respuesta ante un escenario simulado de exposición de información.

---

## Distribución de la carga horaria

| Módulo | Área temática | Horas |
|---|---|---:|
| 01 | Arquitectura de red, Tor y criptografía | 8 |
| 02 | Threat Intelligence, OSINT y Dark Web | 8 |
| 03 | Cloud Security y defensa perimetral | 8 |
| 04 | OPSEC y laboratorios aislados | 8 |
| **Total** | **Capacitación completa** | **32 horas** |

---

## Recursos técnicos y prácticas

El repositorio está organizado para documentar progresivamente los contenidos de la capacitación y sus correspondientes recursos técnicos.

```text
tor-darkweb-cloud-security/
├── README.md
├── modulos/
│   ├── 01-arquitectura-tor-criptografia/
│   ├── 02-threat-intelligence-osint/
│   ├── 03-cloud-security-azure/
│   └── 04-opsec-laboratorios/
├── laboratorios/
│   ├── arquitectura-de-red/
│   ├── investigacion-osint/
│   ├── threat-intelligence/
│   ├── azure-security/
│   └── opsec/
├── evidencias/
│   └── tor-metrics/
├── recursos/
│   ├── documentacion-oficial.md
│   ├── referencias-tecnicas.md
│   └── glosario.md
└── SECURITY.md
```

Los directorios se irán completando con documentación, referencias, ejercicios, capturas analíticas y materiales técnicos a medida que se desarrollen y validen.

## Referencias oficiales

### Tor Project
- [Tor Project — Documentación oficial](https://www.torproject.org/)
- [Tor Metrics — Estadísticas de la red Tor](https://metrics.torproject.org/)
- [Tor Project — Onion Services](https://community.torproject.org/onion-services/)
- [Tor Project — Manual](https://manpages.debian.org/tor)

### Microsoft Security & Cloud
- [Microsoft Learn — Microsoft Entra ID](https://learn.microsoft.com/es-es/entra/)
- [Microsoft Learn — Microsoft Sentinel](https://learn.microsoft.com/es-es/azure/sentinel/)
- [Microsoft Learn — Kusto Query Language](https://learn.microsoft.com/es-es/kusto/query/)
- [Microsoft Learn — Azure Web Application Firewall](https://learn.microsoft.com/es-es/azure/web-application-firewall/)
- [Microsoft Learn — Azure Security](https://learn.microsoft.com/es-es/azure/security/)

### Threat Intelligence & OSINT
- [MITRE ATT&CK](https://attack.mitre.org/)
- [CISA — Cybersecurity Advisories](https://www.cisa.gov/news-events/cybersecurity-advisories)
- [NIST — Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [FIRST — Common Vulnerability Scoring System](https://www.first.org/cvss/)

---

## Buenas prácticas

Los materiales y actividades de este repositorio deben respetar criterios de calidad técnica, investigación responsable y seguridad:

- Utilizar documentación oficial y fuentes verificables como referencia.
- Diferenciar hechos observados, indicadores, hipótesis y conclusiones.
- Documentar la procedencia y confiabilidad de las fuentes consultadas.
- Desarrollar actividades prácticas exclusivamente en entornos controlados y autorizados.
- No publicar credenciales, claves, tokens ni información sensible.
- No realizar accesos no autorizados ni pruebas sobre infraestructuras de terceros.
- Evitar la distribución de malware, herramientas de explotación o material destinado a facilitar actividades ilícitas.
- Aplicar el principio de mínimo privilegio.
- Preservar la integridad y confidencialidad de las evidencias.
- Respetar las condiciones de uso y licenciamiento de los recursos de terceros.

## Descargo de responsabilidad

Este repositorio tiene fines exclusivamente educativos, académicos y de investigación en ciberseguridad.

Los contenidos relacionados con Tor, Dark Web, OSINT y Threat Intelligence se abordan desde una perspectiva de análisis técnico, comprensión de infraestructuras, investigación responsable y defensa de sistemas.

Las actividades prácticas deben realizarse únicamente sobre recursos propios, entornos de laboratorio o infraestructuras para las cuales se disponga de autorización expresa.

La documentación no constituye asesoramiento para realizar accesos no autorizados, vulnerar sistemas, obtener información privada ni participar en actividades ilícitas.

Los nombres, marcas, herramientas y recursos de terceros mencionados pertenecen a sus respectivos titulares.

---

**Instructora:** Dakota Bazan  
**Capacitación:** Tor, Dark Web & Cloud Security  
**Área técnica:** Cybersecurity · Threat Intelligence · OSINT · Blue Team · Cloud Security  
**Carga horaria:** 32 horas  
**Estructura académica:** 4 módulos de 8 horas
