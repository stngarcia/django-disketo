Actualizar pip:
python -m pip install --upgrade pip

actualizar conda
conda update conda --yes

cargar linters y formateadores.
pip install -r base-requirements.txt




Preparación del ambiente para disketo:
a. crear el ambiente virtual.
conda create --name disketo python=3.7 --yes

b. activar el ambiente virtual.
conda activate disketo

c. Cargar las librerías necesarias, se debe estar dentro del ambiente virtual.
pip install -r requirements.txt




Otras acciones:
desactivar el ambiente virtual.
conda deactivate

eliminar el ambiente virtual, primero debe desactivar el ambiente virtual antes de eliminarlo.
conda remove --yes --name disketo --all
