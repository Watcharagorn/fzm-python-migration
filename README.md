# FZM-PYTHON-MIGRATION

FZM-PYTHON-MIGRATION is a database schema migration tool.
Forked from [Yoyo-migrations](https://pypi.org/project/yoyo-migrations/#history)

## Installation from [![pypirepo](https://img.shields.io/badge/pypi-blue.svg)](https://pypi.org/project/fzm-python-migrations/)
```python
pip install fzm-python-migrations
```

## Command line usage
### ● run migration
```comman
yoyo apply {migration_folder}
```
### ● add new migration
```
yoyo new {migration_folder} -m {migration_name}
```

### ● List available migrations
```
yoyo list {migration_folder}
```

## Additional Feature from the source

### Agurments
| args name | required | default | description |
| ----- | ---- | ---- | ---- |
| ( new ) migration_table_prefix | ✔ | None | prefix สำหรับตาราง _yoyo_migration และตารางอื่นๆที่เป็นของระบบ |
| sources | ✔ | None | Directoty to read migrations file |


> [Yoyo migrations documentation](https://ollycope.com/software/yoyo)
