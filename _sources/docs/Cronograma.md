<div style="position: relative; width: 100%; padding: 10px;">
    <div style="border-radius: 10px; overflow: hidden;">
        <img src="https://i.ibb.co/TH6HzwQ/body.jpg" alt="Imagen de fondo" style="width: 100%; height: auto;">
    </div>
</div>

## 7. Cronograma

El proyecto de Voluntariado Académico (VA) de CircleUp en Tocancipá tiene como objetivo impactar a 800 personas en un período de 6 meses, proporcionando educación y capacitación a través de voluntarios locales. Este documento detalla el plan de implementación, incluyendo cronograma, presupuesto, estrategias de impacto y KPIs.

## 1. Cronograma

| ID | Tarea | Duración (semanas) | Dependencias | Recursos |
|----|-------|-------------------|--------------|----------|
| 1 | Planificación inicial | 1 | - | Owner |
| 2 | Configuración de infraestructura en la nube | 1 | 1 | Owner, SN |
| 3 | Desarrollo de MVP del sitio web | 2 | 2 | Owner, PNC |
| 4 | Integración de APIs | 1 | 3 | Owner, AV |
| 5 | Configuración de automatizaciones | 1 | 4 | Owner, HA |
| 6 | Reclutamiento de voluntarios | 2 | 3 | AO |
| 7 | Capacitación de voluntarios | 2 | 6 | Owner, Voluntarios |
| 8 | Diseño de currículum inicial | 2 | 1 | Owner |
| 9 | Creación de contenido de marketing | 2 | 3 | AO, HD |
| 10 | Lanzamiento de campaña de marketing digital | 3 | 9 | AO, PD |
| 11 | Implementación de primeros cursos | 17 | 7, 8 | Owner, Voluntarios |
| 12 | Evaluación y ajuste del programa | Continuo | 11 | Owner, AO |

Table: Cronograma

```{note}
SN: Servicios en la nube
PNC: Plataforma no-code
AV: APIs variadas
HA: Herramientas de automatización
AO: Asistente de Operaciones
HD: Herramientas de diseño
PD: Plataformas digitales
```

## 2. Hitos del Proyecto

1. Finalización de la planificación inicial (Semana 1)
2. Lanzamiento del MVP del sitio web (Semana 4)
3. Inicio de la campaña de marketing digital (Semana 6)
4. Completación del reclutamiento de voluntarios (Semana 6)
5. Finalización de la capacitación de voluntarios (Semana 8)
6. Inicio de los primeros cursos (Semana 9)
7. Alcance de 200 personas impactadas (Semana 15)
8. Alcance de 400 personas impactadas (Semana 20)
9. Finalización del proyecto con 800 personas impactadas (Semana 26)

## 3. Presupuesto Detallado

### 3.1 Costos de Infraestructura y Tecnología

| Ítem | Costo Mensual | Costo Total (6 meses) |
|------|---------------|------------------------|
| Servicios en la nube y Base de datos | $250,000 | $1,500,000 |
| Hosting web (anual) | - | $60,000 |
| Plataforma de desarrollo | $100,000 | $600,000 |
| APIs de IA Generativa | $180,000 | $1,080,000 |
| Email API | $50,000 | $300,000 |
| Herramienta de automatización | $80,000 | $480,000 |
| **Subtotal Infraestructura y Tecnología** | | **$4,020,000** |

Table: Costos de Infraestructura y Tecnología

### 3.2 Costos de Personal

| Posición | Costo Mensual | Costo Total (6 meses) |
|----------|---------------|------------------------|
| Owner (medio tiempo) | $400,000 | $2,400,000 |
| Asistente de Operaciones (medio tiempo) | $900,000 | $5,400,000 |
| **Subtotal Personal** | | **$7,800,000** |

Table: Costos de Personal

### 3.3 Costos de Marketing y Operaciones

| Ítem | Costo Mensual | Costo Total (6 meses) |
|------|---------------|------------------------|
| Material POP | $100,000 | $600,000 |
| Campañas digitales | $350,000 | $2,100,000 |
| Herramienta de diseño | $30,500 | $183,000 |
| Alquiler de espacios | $60,000 | $360,000 |
| **Subtotal Marketing y Operaciones** | | **$3,243,000** |

Table: Costos de Marketing y Operaciones

### 3.4 Resumen del Presupuesto

| Categoría | Costo Total |
|-----------|-------------|
| Infraestructura y Tecnología | $4,020,000 |
| Personal | $7,800,000 |
| Marketing y Operaciones | $3,243,000 |
| **TOTAL** | **$15,063,000** |

Table: Resumen del Presupuesto

### 3.5 Descripción, Alternativas y Definiciones Prácticas

| Ítem | Descripción y Alternativas | Definición Práctica |
|------|----------------------------|---------------------|
| Servicios en la nube y Base de datos | Opción principal: Azure Cloud Services (hosting y procesamiento) con Azure SQL Database (almacenamiento estructurado). Firestore como base de datos principal para datos en tiempo real. Alternativas: (1) Google Cloud Platform con Cloud SQL, (2) Amazon Web Services con RDS, (3) DigitalOcean con Managed Databases. | Infraestructura tecnológica remota para almacenar y procesar datos, accesible con conexión a internet. |
| Hosting web | Opción principal: Bluehost (hosting compartido). Alternativas: (1) SiteGround, (2) HostGator, (3) A2 Hosting. | Servicio para alojar un sitio web en servidores accesibles en internet. |
| Plataforma de desarrollo | Opción principal: Streamlit (desarrollo rápido de apps web con Python). Alternativas: (1) Dash by Plotly, (2) Flask + React, (3) FastAPI. | Herramienta que facilita la creación y mantenimiento de aplicaciones web. |
| APIs de IA Generativa | Opciones: (1) OpenAI API, (2) Anthropic Claude, (3) Google Gemini. | Interfaces para acceder a modelos de inteligencia artificial que generan contenido (texto, imágenes, código). |
| Email API | Opción principal: SendGrid (envío masivo de correos). Alternativas: (1) Mailgun, (2) Amazon SES, (3) Mailchimp. | Servicio para enviar correos electrónicos de forma programática y en grandes volúmenes. |
| Herramienta de automatización | Opción principal: Make (automatizaciones complejas). Alternativas: (1) Zapier, (2) n8n, (3) Automate.io. | Plataforma para crear flujos de trabajo automatizados entre apps y servicios. |
| Material POP | Opción principal: Materiales promocionales físicos (folletos, carteles, camisetas). Alternativas: (1) Marketing digital exclusivo, (2) Asociaciones con imprentas locales, (3) Materiales ecológicos. | Elementos físicos de publicidad para promocionar en el punto de contacto con el público. |
| Campañas digitales | Opción principal: Publicidad en redes sociales y Google Ads. Alternativas: (1) Marketing de contenidos y SEO, (2) Colaboraciones con influencers, (3) Email marketing. | Estrategias de marketing en canales digitales para alcanzar al público objetivo. |
| Herramienta de diseño | Opción principal: Canva Pro (diseño de materiales gráficos). Alternativas: (1) Adobe Creative Cloud, (2) Figma, (3) GIMP y Inkscape. | Software para crear contenido visual para marketing y comunicación. |
| Alquiler de espacios | Estrategias: (1) Alianzas con entidades públicas, (2) Espacios al aire libre o comunitarios, (3) Rotar entre instalaciones de empresas locales. | Contratación temporal de lugares físicos para eventos, talleres o cursos presenciales. |

Table: Definiciones Prácticas

## 4. Flujo de Caja Proyectado

| Mes | Ingresos | Gastos | Flujo Neto | Saldo Acumulado |
|-----|----------|--------|------------|------------------|
| 1 | 15.063.000 | 1.500.000 | 13.563.000 | 13.563.000 |
| 2 | $0 | 2.000.000 | -2.000.000 | 11.563.000 |
| 3 | $0 | 2.500.000 | -2.500.000 | 9.063.000 |
| 4 | $0 | 3.000.000 | -3.000.000 | 6.063.000 |
| 5 | $0 | 3.000.000 | -3.000.000 | 3.063.000 |
| 6 | $0 | 3.063.000 | -3.063.000 | $0 |

Table: Flujo de Caja

## 5. Estrategia de Impacto

Para alcanzar e impactar a 800 personas en 6 meses:

1. **Eventos Presenciales**: Organizar talleres y seminarios mensuales en espacios comunitarios los sábados.
2. **Campaña Digital**: Utilizar redes sociales y marketing por correo electrónico para llegar a la audiencia objetivo.
3. **Alianzas Estratégicas**: Colaborar con organizaciones locales para ampliar el alcance.
4. **Programa de Referidos**: Incentivar a los participantes a invitar a otros miembros de la comunidad.
5. **Contenido Educativo Online**: Crear y distribuir recursos educativos a través del sitio web del proyecto.

## 6. Indicadores Clave de Desempeño (KPIs)

1. Número de personas impactadas (Objetivo: 800 en 6 meses)
2. Porcentaje de alcance del objetivo de impacto (Target: 85% de 800 personas, es decir, 680 personas)
3. Tasa de retención de voluntarios (Objetivo: 80%)
4. Satisfacción de los participantes (Objetivo: 4.5/5 en encuestas)
5. Número de alianzas estratégicas formadas (Objetivo: 5 en 6 meses)
6. Tiempo promedio para la definición de fechas de cursos por voluntarios (Objetivo: < 2 semanas)
7. Tasa de ocupación de espacios públicos gestionados (Objetivo: 70%)

## 7. Costo de Adquisición de Voluntarios y Participantes

### 7.1 Costo de Adquisición de Voluntarios (CAV)

- Presupuesto total de marketing: 3,243,000 COP
- Estimación del 30% del presupuesto para reclutamiento de voluntarios: 972,900 COP
- Objetivo de reclutamiento: 50 voluntarios

```{math}
CAV = 972,900 \text{ COP} / 50 \text{ voluntarios} = 19,458 \text{ COP por voluntario}
```

### 7.2 Costo de Adquisición de Participantes (CAP)

- Presupuesto total de marketing: 3,243,000 COP
- Estimación del 70% del presupuesto para atracción de participantes: 2,270,100 COP
- Objetivo de participantes: 800 personas

```{math}
CAP = 2,270,100 \text{ COP} / 800 \text{ participantes} = 2,838 \text{ COP por participante}
```

### 7.3 Publicaciones en Redes Sociales del Municipio

```{admonition} Valor Estimado de Publicaciones
:class: tip
Aunque las publicaciones en redes sociales del municipio de Tocancipá no tienen un costo directo para CircleUp, se puede estimar un valor mínimo basado en el alcance y el costo equivalente de publicidad pagada:

- Estimación de 10 publicaciones durante el proyecto
- Alcance promedio por publicación: 5,000 personas
- Costo equivalente por 1,000 alcances: 10,000 COP

Valor estimado de las publicaciones del municipio:
10 publicaciones * (5,000 / 1,000) * 10,000 COP = 500,000 COP

Este valor, aunque no representa un gasto directo para CircleUp, puede considerarse como un ahorro en costos de marketing.
```

## 8. Limitantes Potenciales

1. **Gestión de espacios públicos**: La disponibilidad y los procesos de autorización para el uso de espacios públicos pueden retrasar la implementación de cursos presenciales.

2. **Definición de fechas por parte de los voluntarios**: A pesar de la co-creación de contenido con CircleUp, los voluntarios pueden necesitar tiempo adicional para ajustar sus agendas y definir las fechas de los cursos.

3. **Reclutamiento de voluntarios**: Conseguir el número adecuado de voluntarios comprometidos en el tiempo previsto puede ser un desafío.

4. **Adopción tecnológica**: Algunos participantes pueden enfrentar dificultades con las herramientas digitales utilizadas en el programa.

5. **Retención de participantes**: Mantener el interés y la asistencia constante de los participantes a lo largo del programa puede ser desafiante.

6. **Coordinación con entidades locales**: La colaboración efectiva con las autoridades municipales y otras organizaciones locales puede requerir más tiempo del previsto.

## 9. Conclusiones y Recomendaciones

```{admonition} Conclusión
:class: note
El proyecto de Voluntariado Académico de CircleUp en Tocancipá tiene el potencial de generar un impacto significativo en la comunidad. Con un presupuesto total de 15,063,000 COP y un objetivo de impactar a 800 personas, el proyecto presenta una oportunidad costo-efectiva de proporcionar educación y capacitación.
```

### Recomendaciones

1. **Relaciones locales**: Priorizar la construcción de relaciones sólidas con las autoridades locales y organizaciones comunitarias para facilitar el acceso a espacios y recursos.

2. **Seguimiento robusto**: Implementar un sistema de seguimiento robusto para monitorear el progreso hacia los KPIs y realizar ajustes oportunos.

3. **Plan de contingencia**: Desarrollar un plan de contingencia para abordar las limitantes potenciales identificadas.

4. **Programa de incentivos**: Considerar la implementación de un programa de incentivos para voluntarios y participantes para mejorar la retención y el compromiso.

5. **Diversificación de financiamiento**: Evaluar la posibilidad de diversificar las fuentes de financiamiento para garantizar la sostenibilidad del programa más allá de los 6 meses iniciales.

```{tip}
Estas recomendaciones deben revisarse y ajustarse periódicamente según el progreso y los desafíos encontrados durante la implementación del proyecto.
```