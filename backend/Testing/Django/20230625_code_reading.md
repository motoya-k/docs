# Code reading

## Python manage のコマンドについて

`python manage.py` で呼ばれる場所

```python
def call_command(command_name, *args, **options):
```

各コマンドの実装はこちらにある

```
django/core/management/commands
```
