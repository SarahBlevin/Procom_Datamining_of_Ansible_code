# Procom_Datamining_of_Ansible_code.

To run Voyager in 2024, follow these steps:

0) install pipx and poetry (python >= 3.8 required)

Inside the Voyager folder:
1) change file pyproject.toml (see resources/toml_changes.txt)
2) change class _ConfigOption in util/cli.py (see resources/util_changes.txt)
3) run following commands in a Linux terminal:

```rm poetry.lock```

```poetry lock```

```poetry install``` // issue: modules in voyager not found

5) main is ready to run ! for arguments, see https://github.com/ROpdebee/Voyager/blob/master/README.md

```poetry shell```

```poetry run -- python main.py```

  ## Tests

  ```poetry run pytest --assert=plain``` Most of tests work but error importing voyager modules
