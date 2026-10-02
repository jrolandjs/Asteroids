uv init --no-package --python 3.13 Asteroids # Create new Project
cd Asteroids
uv venv # Create new virtual environment
source .venv/bin/activate # activate the virtual environment
uv add pygame==2.6.1
uv run -m pygame # Check pygame installation
s
