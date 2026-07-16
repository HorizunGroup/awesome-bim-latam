<div align="center">

# Awesome BIM LATAM 🧱 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**A curated list of BIM tools, APIs, libraries and resources — every entry proven on a real construction project.**

Maintained by [Horizun Group](https://horizunhub.com) · BIM, data & AI for construction since 2018.

</div>

---

Most awesome-lists are indexes: everything that exists, sorted. This one is a filter. Every entry here has been used by an AEC team on an actual jobsite in Latin America — a region where BIM budgets are tight, deadlines are tighter, and a tool either survives contact with a real project or it doesn't.

So the bar isn't "this exists". The bar is **"we shipped with it"**.

**Missing something?** Open an [issue](../../issues) or a PR — and tell us which project you used it on. See the [contributing guidelines](CONTRIBUTING.md).

## Contents

- [Standards & foundations](#standards--foundations)
- [IFC & open source](#ifc--open-source)
- [Revit automation](#revit-automation)
- [Autodesk Platform Services (APS)](#autodesk-platform-services-aps)
- [Coordination & clash detection](#coordination--clash-detection)
- [Data & visualization](#data--visualization)
- [Contributing](#contributing)

## Standards & foundations

- [buildingSMART International](https://www.buildingsmart.org/) — The body behind IFC, BCF and IDS. The non-negotiable starting point.
- [IFC 4.3 specification](https://ifc43-docs.standards.buildingsmart.org/) — Official documentation of the IFC schema.
- [BCF (BIM Collaboration Format)](https://github.com/buildingSMART/BCF-XML) — The open standard for moving coordination issues between platforms without lock-in.
- [IDS (Information Delivery Specification)](https://github.com/buildingSMART/IDS) — Machine-checkable rules for *what* information a model must carry. The thing that makes handover reviews objective instead of an argument.

## IFC & open source

- [IfcOpenShell](https://ifcopenshell.org/) — The foundation of the open IFC ecosystem (Python/C++). If you're touching IFC with code, start here.
- [Bonsai (formerly BlenderBIM)](https://bonsaibim.org/) — Native IFC authoring inside Blender. Free, and far more capable than you'd expect.
- [That Open Engine (formerly IFC.js)](https://github.com/ThatOpen/engine_web-ifc) — IFC viewer and engine in the browser, in JavaScript.
- [xBIM Toolkit](https://docs.xbim.net/) — IFC toolkit for .NET.
- [Speckle](https://speckle.systems/) — Open data exchange across Revit, Rhino, Blender, Grasshopper and more.

## Revit automation

- [Revit API Docs](https://www.revitapidocs.com/) — The Revit API reference everyone actually uses.
- [pyRevit](https://github.com/pyrevitlabs/pyRevit) — Python scripting inside Revit with nothing to compile. The realistic entry point to automation.
- [Dynamo](https://dynamobim.org/) — Visual programming for Revit and Civil 3D.
- [The Building Coder](https://jeremytammik.github.io/tbc/a/) — Jeremy Tammik's blog. The historical archive for nearly any Revit API problem you'll hit.

## Autodesk Platform Services (APS)

- [APS documentation](https://aps.autodesk.com/developer/documentation) — Formerly Forge. Model translation, web viewer and cloud data.
- [APS Viewer](https://aps.autodesk.com/en/docs/viewer/v7/developers_guide/overview/) — Web 3D viewer for Revit, Navisworks, IFC and DWG.
- [Model Derivative API](https://aps.autodesk.com/en/docs/model-derivative/v2/developers_guide/overview/) — Pull geometry and properties out of the model and into your own data stack.

## Coordination & clash detection

- [Navisworks .NET API](https://aps.autodesk.com/developer/overview/navisworks) — Automate clash tests, viewpoints and reports.
- [BCF-XML](https://github.com/buildingSMART/BCF-XML) — Exchange issues without being tied to one vendor.

## Data & visualization

- [Power BI](https://learn.microsoft.com/en-us/power-bi/) — Official documentation.
- [M language (Power Query)](https://learn.microsoft.com/en-us/powerquery-m/) — Reference for the language you'll connect model data with.
- [PowerBIM Online](https://pbim.horizunhub.com) — *(Horizun)* Upload a Revit model and get its data plus a 3D viewer inside Power BI.
- [BIM Para Todos](https://www.youtube.com/@BIMParaTodos.HorizunAEC) — *(Horizun)* YouTube channel on BIM, data and Power BI applied to real jobsites. *In Spanish.*

## Contributing

Contributions are welcome. One rule: the resource must have **earned its place on a real project**, and you should say in one line *why*. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

Under [CC0 1.0](LICENSE), Horizun Group waives all copyright over this list.
