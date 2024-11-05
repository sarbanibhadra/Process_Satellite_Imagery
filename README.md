# Process_Satellite_Imagery

## Commands to run before running any script 
python3 -m venv agb-venv
source agb-env/bin/activate
pip install earthengine-api
earthengine authenticate
pip install geemap
pip install -r requirements.txt
pip3 install wheel
pip3 install ipykernel geemap ipyleaflet==0.16
python3 -m ipykernel install --user --name=venv-geemap