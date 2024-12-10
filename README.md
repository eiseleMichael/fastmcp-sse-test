# Replicate FastMCP SSE Issue

1. Install dependencies using `uv sync` 
2. Run `python demo.py`
3. Run `fastmcp dev demo.py`
4. In Inspector set Transport Type to SSE
6. Then set URL to http://localhost:8000/sse
7. Error occurs `TypeError: 'NoneType' object is not callable`