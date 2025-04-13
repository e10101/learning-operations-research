<!-- markdownlint-disable MD033 -->
<div style="width: 100%; margin: 0 auto;">
    <img src="./assets/banner.svg" alt="Learning Operations Research" style="width: 100%; height: auto; display: block;">
</div>

## 📓 Notebooks and Videos

| 📝 Notebook | 📺 Video (🇨🇳) |
|------------|------------|
| [Traveling Salesman Problem - Nearest Neighbor](./network/TSP-Nearest-Neighbor.ipynb) | [![Bilibili](./assets/badges/bilibili.svg)](https://www.bilibili.com/video/BV14jRUYZEpn) |
| [Traveling Salesman Problem - 2-Opt](./network/TSP-2-Opt.ipynb) | [![Bilibili](./assets/badges/bilibili.svg)](https://www.bilibili.com/video/BV15KdVYkEec/) |
| [Minimum Spanning Tree - Prim](./network/TSP-MST-Prim.ipynb) | [![Bilibili](./assets/badges/bilibili.svg)](https://www.bilibili.com/video/BV1MKdDYMEYg/) |
| [Minimum Spanning Tree - Kruskal](./network/TSP-MST-Kruskal.ipynb) | [![Bilibili](./assets/badges/bilibili.svg)](https://www.bilibili.com/video/BV1QpdhY9EW5/) [![Bilibili](./assets/badges/bilibili.svg)](https://www.bilibili.com/video/BV1B3dhYwEJ1/)  |
| [Minimum-Cost Network Flow Problems](./network/MCNFP.ipynb) | [![Bilibili](./assets/badges/bilibili.svg)](https://www.bilibili.com/video/BV1xDdzYqEU2/) [![Bilibili](./assets/badges/bilibili.svg)](https://www.bilibili.com/video/BV17Td6YdEv9/)  |


## 🐳 Running Notebooks with Docker

This project uses Docker to provide a consistent environment for running Jupyter notebooks. The setup includes:
- Jupyter Lab with scientific Python packages pre-installed
- Gurobi optimization environment with Jupyter Lab

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Quick Start

1. Start the services:

   ```bash
   docker-compose up
   ```

2. Access the services in your browser:

   - Jupyter Lab: `http://localhost:8888` (token: `jupyter`)
   - Gurobi Lab: `http://localhost:8889` (token: `gurobi`)

3. You'll find the notebooks in the mounted directories:
   - Jupyter: `/home/jovyan/work`
   - Gurobi: `/home/gurobi`

### Features

- Jupyter Lab interface for both services
- Scientific Python stack pre-installed
- Gurobi optimization environment
- Automatic volume mounting (changes are saved to your local files)
- Persistent workspace

### Stopping the Server

To stop the server, press `Ctrl+C` in the terminal or run:

```bash
docker-compose down
```

## Star History

<a href="https://www.star-history.com/#e10101/learning-operations-research&Date">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=e10101/learning-operations-research&type=Date&theme=dark" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=e10101/learning-operations-research&type=Date" />
   <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=e10101/learning-operations-research&type=Date" />
 </picture>
</a>