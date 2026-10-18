Simple template to manage my Data Science / Machine Learning projects using uv.

**Included packages:**
- numpy >= 2.5.4
- pandas >= 3.0.6
- matplotlib >= 3.11.2

**Dev dependencies:**
- pytest >=9.1.1
- jupyter>=1.1.1
- ipykernel>=7.4.0



### Install UV on Linux / Mac
> pip install uv / brew install uv

### Create project
> uv init --no-package name_of_project

### Add packages
> uv add name_of_package

### Add packages only for devs (not shipped with project)
> uv add --dev pytest

### Reproduce environment / install dependencies
> uv sync

### Run your project
> uv run name_of_project

