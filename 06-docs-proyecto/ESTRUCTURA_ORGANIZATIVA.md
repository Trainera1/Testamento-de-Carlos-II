# Estructura Organizativa Recomendada para el Repositorio

## Árbol de Directorios Propuesto

```
Testamento-de-Carlos-II/
│
├── README.md
│
├── documentos-primarios/
│   ├── tratados-particion/
│   │   ├── 1700_Traite_Lorraine_Bar_Milanais_D17000004.pdf
│   │   ├── 1701-06-18_Traite_alliance_testament_D17010006.pdf
│   │   └── 1701_Traite_alliance_testament_D17010006_v2.pdf
│   │
│   ├── documentos-matrimoniales/
│   │   ├── 1679_Contrato_matrimonio_Carlos_II_MLuisa_D16790010.pdf
│   │   └── 1679_Convenio_matrimonial_Carlos_II_MLuisa_D16790009.pdf
│   │
│   ├── relaciones-internacionales/
│   │   ├── 1673_Declaracion_Inglaterra_Charleroi_TRA16730009_s1.pdf
│   │   └── 1701_Memoire_Hollande_dispositions_hostiles_9782013188234.pdf
│   │
│   └── serie-tra/
│       ├── 1668_TRA16680006_001.pdf
│       ├── 1668_TRA16680006_003.pdf
│       ├── 1668_TRA16680006_005.pdf
│       └── 1689_TRA16890002_s1.pdf
│
├── analisis/
│   ├── modulo-01_introduccion.md
│   ├── modulo-02_contexto-historico.md
│   ├── modulo-03_tratados-particion.md
│   ├── modulo-04_testamento-carlos-ii.md
│   ├── modulo-05_reacciones-europeas.md
│   ├── modulo-06_transicion-dinastica.md
│   ├── modulo-07_[tema-por-definir].md
│   ├── modulo-08_[tema-por-definir].md
│   ├── modulo-09_[tema-por-definir].md
│   └── modulo-10_[tema-por-definir].md
│
├── metodologia/
│   ├── analisis-forense.md
│   ├── prosopografia.md
│   └── fuentes-archivisticas.md
│
├── bibliografia/
│   ├── fuentes-primarias.md
│   └── bibliografia-secundaria.md
│
└── anexos/
    ├── cronologia.md
    ├── dramatis-personae.md
    └── genealogias.md
```

## Explicación de la Estructura

### 1. documentos-primarios/
Contiene todos los documentos históricos originales organizados temáticamente:

- **tratados-particion/**: Los tratados europeos sobre la división del reino de España
- **documentos-matrimoniales/**: Contratos y convenios matrimoniales de Carlos II
- **relaciones-internacionales/**: Memorias y declaraciones de potencias europeas
- **serie-tra/**: Documentos archivísticos de la serie TRA sin clasificar temáticamente

### 2. analisis/
Módulos de análisis académico numerados secuencialmente:
- Módulos 1-6 ya definidos conceptualmente
- Módulos 7-10 pendientes de definir contenido específico

### 3. metodologia/
Documentación sobre los métodos de investigación empleados:
- Análisis forense de documentos
- Estudios prosopográficos
- Gestión de fuentes archivísticas

### 4. bibliografia/
Referencias organizadas:
- Fuentes primarias (con códigos archivísticos)
- Bibliografía secundaria académica

### 5. anexos/
Material de apoyo:
- Cronología detallada de eventos 1668-1714
- Listado de personajes clave (dramatis personae)
- Árboles genealógicos Habsburgo-Borbón

## Nomenclatura de Archivos

Para mantener consistencia y facilitar la búsqueda:

### Formato propuesto:
`YYYY_Descripcion_breve_CodigoArchivistico.extension`

### Ejemplos:
- `1701-06-18_Traite_alliance_testament_D17010006.pdf`
- `1679_Contrato_matrimonio_Carlos_II_MLuisa_D16790010.pdf`
- `1668_TRA16680006_001.pdf`

### Ventajas:
- Orden cronológico automático
- Descripción clara del contenido
- Trazabilidad archivística preservada
- Compatibilidad multiplataforma (sin espacios problemáticos)

## Pasos para Implementar

### En la interfaz web de GitHub:

1. **Crear carpetas:**
   - GitHub crea carpetas automáticamente al subir archivos con rutas
   - Ejemplo: subir `documentos-primarios/tratados-particion/archivo.pdf`

2. **Reorganizar archivos existentes:**
   - Opción A: Descargar, renombrar localmente, resubir con nueva estructura
   - Opción B: Usar interfaz web para mover archivos uno por uno

3. **Crear archivos markdown:**
   - Usar botón "Add file" > "Create new file"
   - Escribir ruta completa: `analisis/modulo-07.md`

### Usando Git local (si tienes Git instalado):

```bash
# Clonar repositorio
git clone https://github.com/Trainera1/Testamento-de-Carlos-II.git
cd Testamento-de-Carlos-II

# Crear estructura de carpetas
mkdir -p documentos-primarios/{tratados-particion,documentos-matrimoniales,relaciones-internacionales,serie-tra}
mkdir -p analisis metodologia bibliografia anexos

# Mover archivos a nuevas ubicaciones
# (hacer manualmente según correspondencia)

# Commit y push
git add .
git commit -m "Reorganización: estructura temática y cronológica"
git push origin main
```

## Notas Importantes

1. **Preservación de códigos archivísticos**: Siempre mantener los códigos D y TRA en los nombres de archivo
2. **Backup**: Antes de reorganizar, descargar copia local de todos los archivos
3. **README actualizado**: El README.md debe reflejar la nueva estructura
4. **Commits descriptivos**: Usar mensajes de commit claros para trazabilidad

## Próximos Pasos

1. Definir contenido específico de módulos 7-10
2. Renombrar archivos según nomenclatura propuesta
3. Crear estructura de carpetas
4. Mover archivos a ubicaciones correspondientes
5. Actualizar README con nueva estructura
6. Crear archivos markdown para módulos de análisis
