# Modulo UML

[[UML] Capacitación INVAP][Presentacion]

**Planteamos la utilización de PlantUML por las siguientes razones**:

- Se pueden versionan los distintos diagramas
- Existen herramientas que lo interpretan y no requiere la instalación de un software. Ver [aquí](#editor-online)
- La utilización de `include` facilita la actualización de los diagramas
- Gitlab permite embeber diagramas de plantuml en los archivos `.md`. Ver [aquí](https://git.partners.invap.com.ar/pyo/capacitacion/sw-embebido/sandbox/curso/test-uml-gitlab-capabilities)

## Herramientas

### Editor online

**Nota:**
Es útil para pequeños ensayos de notación. 

- [Plantuml Editor](https://plantuml-editor.kkeisuke.com/)
- [Plant Text](https://www.planttext.com/)

### IDE

**Nota:**
Verifiqué el funcionamiento en Mac OS y Linux

| Herramienta                           | Version |
|---------------------------------------|---------|
| [VSCode][external_vscode]             | v1.58.0 |
| [Plantuml plugin][external_pplantuml] | v2.15.1 |

### PlantUML

#### Documentación

[Documentación de Plantuml][external_plantuml_docs]

##### Referencia por diagrama

| Diagrama          | Documento                                 |
|-------------------|-------------------------------------------|
| Clases y paquetes | https://plantuml.com/es/class-diagram     |
| Secuencia         | https://plantuml.com/es/sequence-diagram  |
| Componentes       | https://plantuml.com/es/component-diagram |
| Estados           | https://plantuml.com/state-diagram        |
| Despliegue        | https://plantuml.com/deployment-diagram   |
|                   |                                           |


##### Elementos específicos

| Elemento    | Documento                                              |
|-------------|--------------------------------------------------------|
| _Include_   | https://plantuml.com/es/preprocessing#393335a6fd28a804 |
| _Variables_ | https://plantuml.com/es/preprocessing#788fa5fb2276ed17 |

## Ejemplo de diagramas

| Diagrama     | Carpeta                             |
|--------------|-------------------------------------|
| Clases       | [diagramas](diagramas/clases)       |
| Secuencia    | [diagramas](diagramas/secuencias)   |
| Paquetes     | [diagramas](diagramas/paquetes)     |
| Componentes  | [diagramas](diagramas/componentes)  |
| Casos de uso | [diagramas](diagramas/casos_de_uso) |
| Actividad    | [diagramas](diagramas/actividad)    |
| Estados      | [diagramas](diagramas/estados)      |
| Despliegue   | [diagramas](diagramas/despliegue)   |


[Presentacion]: https://docs.google.com/presentation/d/1nkawKzySthLmkAl0huwdfCMsF1NFS2WVCglG1G4kzjg/edit?usp=sharing]

[external_vscode]: https://code.visualstudio.com/Download
[external_pplantuml]: https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml
[external_plantuml_docs]: https://plantuml.com/es/
