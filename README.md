# sim-plugin-elmer

Elmer driver for [sim-cli](https://github.com/svd-ai-lab/sim-cli),
distributed as an out-of-tree plugin.

Elmer FEM driver for sim.

## Install

```bash
sim plugin install elmer
```

Other paths:

```bash
pip install git+https://github.com/svd-ai-lab/sim-plugin-elmer@v0.1.0
pip install https://github.com/svd-ai-lab/sim-plugin-elmer/releases/download/v0.1.0/sim_plugin_elmer-0.1.0-py3-none-any.whl
pip install -e .
```

After install:

```bash
sim plugin doctor elmer
sim plugin sync-skills
```

## Development

```bash
git clone https://github.com/svd-ai-lab/sim-plugin-elmer
cd sim-plugin-elmer
uv sync
uv run pytest
```

## License

Apache-2.0.
