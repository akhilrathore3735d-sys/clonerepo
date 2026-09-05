<p align="center">
  <img width="500" src="https://user-images.githubusercontent.com/10407788/204477834-2533241a-5927-4f56-959e-4e8494027bc0.png"/>
  <p align="center">Simple and Fast Geospatial OGC Features and Tiles API for PostGIS.</p>
</p>

<p align="center">
  <a href="https://github.com/developmentseed/tipg/actions?query=workflow%3ACI" target="_blank">
      <img src="https://github.com/developmentseed/tipg/workflows/CI/badge.svg" alt="Test">
  </a>
  <a href="https://codecov.io/gh/developmentseed/tipg" target="_blank">
      <img src="https://codecov.io/gh/developmentseed/tipg/branch/main/graph/badge.svg" alt="Coverage">
  </a>
  <a href="https://pypi.org/project/tipg" target="_blank">
      <img src="https://img.shields.io/pypi/v/tipg?color=%2334D058&label=pypi%20package" alt="Package version">
  </a>
  <a href="https://github.com/developmentseed/tipg/blob/main/LICENSE" target="_blank">
      <img src="https://img.shields.io/github/license/developmentseed/tipg.svg" alt="License">
  </a>
</p>

---

**Documentation**: <a href="https://developmentseed.org/tipg/" target="_blank">Documentation</a>

**Source Code**: <a href="https://github.com/developmentseed/tipg" target="_blank">Source Code</a>

---

This is a **Python** package that helps create lightweight OGC **Features** and **Tiles** API with a PostGIS Database backend. The API has been designed for [OGC Features](https://ogcapi.ogc.org/features) and [OGC Tiles](https://ogcapi.ogc.org/tiles/) specifications.

> **Note**
> This project is the result of the merge between [tifeatures](https://github.com/developmentseed/tifeatures) and [timvt](https://github.com/developmentseed/timvt).

## Install

```bash
python -m pip install pip -U
python -m pip install tipg

# or from source
git clone https://github.com/developmentseed/tipg.git
cd tipg
python -m pip install -e .
