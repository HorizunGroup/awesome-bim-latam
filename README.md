<div align="center">

# Awesome BIM LATAM 🧱 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**Lista curada de herramientas, APIs, librerías y recursos para BIM — en español.**

Mantenida por [Horizun Group](https://horizunhub.com) · BIM, datos e IA para construcción desde 2018.

</div>

---

Casi todo el ecosistema BIM está documentado en inglés. Esta lista recoge lo que realmente usamos en proyectos reales en Latinoamérica, explicado en español, para que un equipo AEC hispanohablante no tenga que traducir antes de empezar.

**¿Falta algo?** Abre un [issue](../../issues) o un PR. Lee primero las [pautas de contribución](CONTRIBUTING.md).

## Contenido

- [Estándares y fundamentos](#estándares-y-fundamentos)
- [IFC y open source](#ifc-y-open-source)
- [Revit — automatización](#revit--automatización)
- [Autodesk Platform Services (APS)](#autodesk-platform-services-aps)
- [Coordinación y clash](#coordinación-y-clash)
- [Datos y visualización](#datos-y-visualización)
- [Contribuir](#contribuir)

## Estándares y fundamentos

- [buildingSMART International](https://www.buildingsmart.org/) — El organismo detrás de IFC, BCF e IDS. Punto de partida obligado.
- [Especificación IFC 4.3](https://ifc43-docs.standards.buildingsmart.org/) — Documentación oficial del esquema IFC.
- [BCF (BIM Collaboration Format)](https://github.com/buildingSMART/BCF-XML) — El estándar abierto para intercambiar incidencias de coordinación entre plataformas.
- [IDS (Information Delivery Specification)](https://github.com/buildingSMART/IDS) — Define y valida por computadora *qué* información debe traer un modelo. Clave para pre-entrega.

## IFC y open source

- [IfcOpenShell](https://ifcopenshell.org/) — La librería base del ecosistema IFC abierto (Python/C++). Si vas a tocar IFC con código, empieza aquí.
- [Bonsai (antes BlenderBIM)](https://bonsaibim.org/) — BIM nativo IFC dentro de Blender. Gratis y sorprendentemente capaz.
- [That Open Engine (antes IFC.js)](https://github.com/ThatOpen/engine_web-ifc) — Visor y motor IFC en el navegador, con JavaScript.
- [xBIM Toolkit](https://docs.xbim.net/) — Toolkit IFC para .NET.
- [Speckle](https://speckle.systems/) — Plataforma abierta de intercambio de datos entre Revit, Rhino, Blender, Grasshopper y más.

## Revit — automatización

- [Revit API Docs](https://www.revitapidocs.com/) — La referencia de la API de Revit que todo el mundo usa de verdad.
- [pyRevit](https://github.com/pyrevitlabs/pyRevit) — Scripts en Python dentro de Revit sin compilar nada. La puerta de entrada a la automatización.
- [Dynamo](https://dynamobim.org/) — Programación visual para Revit y Civil 3D.
- [The Building Coder](https://jeremytammik.github.io/tbc/a/) — El blog de Jeremy Tammik. Archivo histórico de casi cualquier problema de la Revit API.

## Autodesk Platform Services (APS)

- [APS — Documentación](https://aps.autodesk.com/developer/documentation) — Antes Forge. Traducción de modelos, visor web y datos en la nube.
- [APS Viewer](https://aps.autodesk.com/en/docs/viewer/v7/developers_guide/overview/) — Visor 3D web para Revit, Navisworks, IFC y DWG.
- [Model Derivative API](https://aps.autodesk.com/en/docs/model-derivative/v2/developers_guide/overview/) — Extrae geometría y propiedades del modelo hacia tus propios datos.

## Coordinación y clash

- [Navisworks .NET API](https://aps.autodesk.com/developer/overview/navisworks) — Automatiza clash tests, viewpoints y reportes.
- [BCF-XML](https://github.com/buildingSMART/BCF-XML) — Intercambia incidencias sin quedar atado a una plataforma.

## Datos y visualización

- [Power BI](https://learn.microsoft.com/es-es/power-bi/) — Documentación oficial, en español.
- [Lenguaje M (Power Query)](https://learn.microsoft.com/es-es/powerquery-m/) — Referencia del lenguaje con el que conectas datos del modelo.
- [PowerBIM Online](https://pbim.horizunhub.com) — *(Horizun)* Sube tu modelo de Revit y obtén sus datos y un visor 3D dentro de Power BI.
- [BIM Para Todos](https://www.youtube.com/@BIMParaTodos.HorizunAEC) — *(Horizun)* Canal en español sobre BIM, datos y Power BI aplicados a obra.

## Contribuir

Los aportes son bienvenidos. Lo único que pedimos: que el recurso sea **realmente útil en un proyecto real** y que expliques en una línea *por qué* lo es. Ver [CONTRIBUTING.md](CONTRIBUTING.md).

## Licencia

Bajo [CC0 1.0](LICENSE), Horizun Group renuncia a todos los derechos de autor sobre esta lista.
