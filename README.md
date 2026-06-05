# Neale Petrillo

Computer scientist and software engineer based in upstate New York. I build software for everything from embedded control systems, distributed infrastructure, and data pipelines with a particular focus on Python and the surrounding ecosystem.

---

## Education

MS Computer Science — Georgia Institute of Technology, 2020  
BA Computer Science — Wells College, 2011

---

## Open Source

### Python Libraries

**[logring](https://github.com/nealepetrillo/logring)**  
A ring buffer-based Python logging handler designed for use in interactive tools. Keeps a fixed-size window of recent log records in memory, making it easy to surface contextual log history without writing to disk or flooding a terminal.

**[pytest-gcppubsub](https://github.com/nealepetrillo/pytest-gcppubsub)**
A wrapper for the GCP pub/sub emulator to integrate it with Pytest.

**[pytest-firestore](https://github.com/nealepetrillo/pytest-firestore)**
A wrapper for the GCP firestore emulator to integrate it with Pytest

**[pytest-gcpsecretmanager](https://github.com/nealepetrillo/pytest-gcpsecretmanager)**
A Pytest plugin to mock calls to GCP's secret manager; allows for the injection and retrieval of secrets for testing


### C++ Libraries

**[SimplyEmail](https://github.com/nealepetrillo/SimplyEmail)**  
A minimal C++ email library built on libcurl. Provides a straightforward interface for sending email over SMTP without pulling in a heavyweight dependency. Builds with CMake and targets C++11, tested on Ubuntu 18.04+ and RHEL 7.7+.

### Claude Code Skills

**[claude-skills-echart](https://github.com/nealepetrillo/claude-skills-echart)**
A Claude Code skill for generating production-ready Apache ECharts. Supports 20+ chart types across standalone HTML, vanilla JS, React, and Vue output formats. Applies evidence-based design defaults: colorblind-safe Paul Tol palettes, zero-baseline enforcement for bar charts, and ECharts v6 features including dynamic theme switching and chord charts.

**[claude-skills-fastapi](https://github.com/nealepetrillo/claude-skills-fastapi)**
A Claude Code skill built from the complete FastAPI documentation. Covers the full stack — routing, dependency injection, Pydantic validation, middleware, OAuth2/JWT authentication, WebSockets, background tasks, and SQLModel database integration — plus a detailed testing reference using TestClient and pytest fixtures.

**[claude-skills-pytest](https://github.com/nealepetrillo/claude-skills-pytest)**
A Claude Code skill for pytest, sourced from the official docs and key plugin ecosystems. Covers core pytest patterns (fixtures, parametrize, markers, monkeypatching, configuration) alongside deep reference material for a dozen plugins including pytest-mock, pytest-asyncio, pytest-xdist, pytest-playwright, and pytest-postgresql.

**[claude-skills-poetry](https://github.com/nealepetrillo/claude-skills-poetry)**
A Claude Code skill for managing Python projects with Poetry 2.x. Covers pyproject.toml generation per PEP 621, dependency groups, virtual environment handling, lock file management, and package publishing to PyPI or private repositories.

