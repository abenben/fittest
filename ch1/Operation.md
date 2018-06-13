### コマンド

```bash
# pytest
pytest test_one.py 
pytest test_two.py
pytest -v test_two.py
pytest -v tasks/test_four.py::test_asdict
pytest --collect-only
pytest -k "asdict or default" --collect-only
pytest -k "asdict or default"
pytest -v -k "asdict or default"
pytest -x
pytest --tb=no
pytest --maxfail=2 --yb=no
pytest --maxfail=2 --yb=no
pytest --maxfail=2 --tb=no
pytest --maxfail=1 --tb=no
pytest --lf
pytest --ff -tb=no
pytest --ff --tb=no
pytest -v --ff --tb=no
pytest -q
pytest -l tasks
pytest --tb=no tasks
pytest --tb=line tasks
pytest --tb=short tasks
pytest --durations=3 tasks
pytest --version
pytest -h
```
