# Procom_Datamining_of_Ansible_code

To run Voyager in 2024, follow these steps:

0) install pipx and poetry (python >= 3.8 required)

Inside the Voyager folder:
1) change file pyproject.toml (new version posted on discord by Maxime)
2) change class _ConfigOption in util/cli.py (new version posted on discord by Maxime)
3) run following commands in a Linux terminal:
rm poetry.lock
poetry lock
poetry install --no-root

4) main is ready to run ! for arguments, see https://github.com/ROpdebee/Voyager/blob/master/README.md

  poetry run -- python main.py
