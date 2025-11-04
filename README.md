# mace-tm
Fine-tuning and benchmarking MACE on organometallics.

## Installation
- Clone the repository `git clone https://github.com/anoushka2000/mace-tm.git`
- Install [`uv`](https://docs.astral.sh/uv/getting-started/installation/)
- Create the virtual env `uv sync`
- Activate the virtual env `source .venv/bin/activate`
### Adding Jupyter Kernel
- `uv add --dev ipykernel`
- `uv run ipython kernel install --user --env VIRTUAL_ENV $(pwd)/.venv --name=mace-tm`
