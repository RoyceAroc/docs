# src.uagents.utils

#### get_logger [↗](https://github.com/fetchai/uAgents/blob/main/python/src/uagents/utils.py#L10)

```python
def get_logger(logger_name: str, level: Union[int, str] = logging.INFO)
```

Get a logger with the given name using uvicorn's default formatter.

#### log [↗](https://github.com/fetchai/uAgents/blob/main/python/src/uagents/utils.py#L23)

```python
def log(logger: Optional[logging.Logger], level: int, message: str)
```

Log a message with the given logger and level.

**Arguments**:

- `logger` _Optional[logging.Logger]_ - The logger to use.
- `level` _int_ - The logging level.
- `message` _str_ - The message to log.
