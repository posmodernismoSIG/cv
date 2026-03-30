# Joan Sebastián Díaz Gómez

**GIS Backend Engineer · Bogotá, Colombia**

[![GIS](https://img.shields.io/badge/GIS-ArcGIS%20Enterprise-00e5a0?style=flat-square&logoColor=white)](https://www.esri.com/)
[![Python](https://img.shields.io/badge/Python-Django%20%7C%20FastAPI%20%7C%20Flask-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Cloud](https://img.shields.io/badge/Cloud-AWS%20EKS%20%7C%20Kubernetes-FF9900?style=flat-square&logo=amazonaws&logoColor=white)](https://aws.amazon.com/)
[![Location](https://img.shields.io/badge/Location-Bogot%C3%A1%2C%20Colombia-00d4e8?style=flat-square)](https://maps.google.com/?q=Bogota,Colombia)

---

## Cover Letter

Dear Hiring Team,

I build the backend systems that make geospatial intelligence usable — and I do it in production, at scale, for clients that include government agencies and Colombia's military forces.

I am a backend engineer and development team lead at **Procalculo**, an ESRI Partner company in Bogotá that provides geographic information services derived from satellite imagery and remote sensing. My work centers on designing **Python API layers** (Django REST Framework, FastAPI, Flask) that act as middleware between client applications and **ArcGIS Enterprise** — handling everything from token-based authentication and feature service publishing to batch spatial data ingestion via `applyEdits` and async geoprocessing job management.

---

## Production Systems

### 🌿 [ABACO](https://abaco.procalculo.com/) — Deforestation Analysis Platform
> *Satellite-based change detection · Military & environmental agencies*

A deforestation monitoring system processing multi-temporal **Sentinel satellite imagery** to detect, classify, and track forest loss at scale. It runs NDVI change detection via **ArcPy geoprocessing services**, pushes detected polygons to ArcGIS Enterprise hosted feature layers, and surfaces results through a Django REST API. Deployed on **AWS EKS**.

### 🛰️ [Prisma API](https://prisma.procalculo.com/docu/) — Satellite Imagery API
> *Unified multi-source imagery access · Planet · Capella SAR*

A unified imagery API that abstracts **Planet optical** and **Capella SAR** data behind a single Django REST surface, using **ArcGIS image services** for tile caching and on-the-fly raster rendering. Designed for e-commerce-style imagery purchasing workflows with CRM integration.

### 🗺️ [Mapas.co](https://mapas.procalculo.com/) — Geospatial Web Platform
> *Government & enterprise clients · Angular · ArcGIS Enterprise*

A geospatial web platform wrapping ArcGIS Enterprise feature and map services in a clean **Python middleware layer**, consumed by Angular and React frontends. Enables clients to query, filter, and visualize authoritative spatial datasets without direct ESRI dependency.

---

## ArcGIS Enterprise Expertise

My hands-on integration experience covers the full stack:

| Area | Details |
|---|---|
| **Server Integration** | Portal for ArcGIS · token auth (built-in / IWA) · service publishing |
| **SDK & Automation** | `arcgis` Python SDK · `arcpy` · Spatially Enabled DataFrames |
| **Data Stores** | Relational · Raster Store · Cloud Store (AWS S3) |
| **REST API** | `applyEdits` · `generateToken` · GP service async job polling |
| **Server Libraries** | Conda env management · `arcgispro-py3` cloning · server registration |
| **Raster Processing** | GDAL · Rasterio · NDVI change detection · RasterToPolygon |

---

## Core Stack

```
Backend    →  Django DRF · FastAPI · Flask · Pydantic · Celery
GIS        →  ArcGIS Enterprise 11.x · ArcPy · arcgis SDK · GDAL · Rasterio
Spatial DB →  PostGIS / PostgreSQL · SQL Server · GeoPandas · Shapely
Frontend   →  Angular · React · Next.js · ArcGIS Maps SDK (JS)
Cloud      →  AWS EKS · Kubernetes · Docker · EC2 · S3 · Lambda
Security   →  SonarQube · Snyk · AWS Security Hub · GitFlow CI/CD
```

---

## Beyond the Backend

I lead end-to-end delivery across the full engineering lifecycle:

- 🏗️ **Infrastructure** — AWS EKS / Kubernetes migration strategy, VPC configuration, SSL management, service startup sequencing for ArcGIS Enterprise on Windows Server
- 🔒 **Security** — Secrets management, SonarQube / Snyk integration, CI/CD security hardening, AWS Security Hub OKRs
- 👥 **Team Leadership** — Mentoring frontend, backend, and full-stack developers on Git workflows, OOP, design patterns, and GIS best practices
- 📐 **Architecture** — Hexagonal architecture, SOLID principles, REST API design, OpenAPI documentation

---

I bring a combination of deep GIS domain expertise, production-grade backend engineering, and team leadership that is rare in this space. I work well in complex, ambiguous technical environments — the kind where the geospatial stack, the cloud infrastructure, and the product requirements are all evolving at the same time.

If that sounds like what you're working on, I'd like to talk.

---

*Joan Sebastián*
*GIS Backend Engineer · Bogotá, Colombia*
*4.7110°N · 74.0721°W*