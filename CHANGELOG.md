# Changelog

All notable changes to this project are documented here.
Format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

## [0.1.0] - 2026-11-19
### Added
- `Required Files/export_working_long_code.py`: ANSA Python script that imports a STEP file, maps shell faces, remeshes volumes with a quality criterion, and exports an ANSYS CDB deck per mesh size.
- `Required Files/CAM_SHAFT.STEP`: the two-lobe camshaft input geometry.
- `Mesh/`: exported CDB decks at 3.0, 5.0 and 7.0 mm.
- `Log File/ansa_mesh_log.txt`: run log from the 1 July 2025 batch.
- `Report/` and `images/quality_checks/`: LaTeX report, PDF, and quality-plot exports.
- Project docs: CONTRIBUTING, MIT license, issue templates, and a CI check that byte-compiles the script.
