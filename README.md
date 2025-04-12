# 📚 Learning Operations Research

## 📓 Notebooks and Videos

| 📝 Notebook | 📺 Video |
|------------|----------|
| [Traveling Salesman Problem - Nearest Neighbor](./tsp/TSP-Nearest-Neighbor.ipynb) | [![Bilibili](./assets/badges/bilibili.svg)](https://www.bilibili.com/video/BV14jRUYZEpn) |
| [Traveling Salesman Problem - 2-Opt](./tsp/TSP-2-Opt.ipynb) | [![Bilibili](./assets/badges/bilibili.svg)](https://www.bilibili.com/video/BV15KdVYkEec/) |
| [Minimum Spanning Tree - Prim](./tsp/TSP-MST-Prim.ipynb) | [![Bilibili](./assets/badges/bilibili.svg)](https://www.bilibili.com/video/BV1MKdDYMEYg/) |


## 🐳 Running Notebooks with Docker

This project uses Docker to provide a consistent environment for running Jupyter notebooks. The setup includes Jupyter Lab with scientific Python packages pre-installed.

### Prerequisites

- [Docker](https://docs.docker.com/get-docker/)
- [Docker Compose](https://docs.docker.com/compose/install/)

### Quick Start

1. Start the Jupyter Lab server:

   ```bash
   docker-compose up
   ```

2. Open your browser and navigate to:

   ```
   http://localhost:8888
   ```

3. You'll find the notebooks in the `work` directory.

### Features

- Jupyter Lab interface
- Scientific Python stack pre-installed
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