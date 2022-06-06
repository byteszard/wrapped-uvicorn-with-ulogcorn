# wrapped-uvicorn-with-ulogcorn

```python
import vvicorn

vvicorn.run(app='main:app', host='0.0.0.0', port=8000, debug=True, reload=True, access_log=False)

```