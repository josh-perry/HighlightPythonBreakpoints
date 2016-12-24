# HighlightPythonBreakpoints
A Sublime text plugin to highlight Python breakpoints.

Highlights things like:
```python
import pdb; pdb.set_trace()
```

and

```python
pdb.set_trace()
```

but not
```python
import pdb
```

...on it's own.