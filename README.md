# Geospatial Intelligence AI Agent (Demo)

Demo repo for geospatial object detection and change detection workflows with GeoPandas and Rasterio.
Quickstart:
```bash
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python src/geospatial/agent_demo.py
uvicorn src.api.app:app --reload --port 8400
```
