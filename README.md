Enter venv:

```
python3 -m venv ~/cairo_venv
source ~/cairo_venv/bin/activate
```

Compile Cairo program:

```
cairo-compile test.cairo --output test_compiled.json
```

Run Cairo program:

```
cairo-run \
  --program=test_compiled.json --print_output \
  --print_info --relocate_prints
```
