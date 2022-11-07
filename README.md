# Català

Genera un document .csv amb els immobles de compra extrets del portal web Habitaclia.

Per executar el script es necessari la instalació de les seguents biblioteques:

pip install requests
pip install re
pip install beautifulSoup4
pip install csv
pip install pandas

La crida del script s'haura de realitzar de la següent manera:

python main.py

Posteriorment demana la població que es desitja cercar. Aquesta població s'haura d'escriure sense accents (p.e. Castellar del valles, Barcelona, Caldes de Montbui).

Finalment genera un arxiu .csv amb el conjunt de columnes:

Type: Tipus d'immoble (Casa, Pis, Xalet...)
Size: Metres quadrats de l'immoble
Baths: Nombre de banys de l'immoble
Rooms: Nombre d'habitacions de l'immoble
Price: Preu de l'immmoble

# Español

Genera un documento .csv con los inmuebles de compra extraídos del portal web Habitaclia.

Para ejecutar el script es necesario la instalación de las siguientes bibliotecas:

pip install requests
pip install re
pip install beautifulSoup4
pip install csv
pip install pandas

La llamada del script deberá realizarse de la siguiente manera:

python main.py

Posteriormente pide a la población que se desea buscar. Esta población deberá escribirse sin acentos (p.e. Castellar del Valles, Barcelona, Caldes de Montbui).

Finalmente genera un archivo .csv con el conjunto de columnas:

Type: Tipo de inmueble (Casa, Piso, Chalet...)
Size: Metros cuadrados del inmueble
Baths: Número de baños del inmueble
Rooms: Número de habitaciones del inmueble
Price: Precio del inmueble

# English

Generate a .csv document with a list of properties taken from the Habitaclia web portal.

To run the script, the installation of the following libraries is necessary:

pip install requests
pip install re
pip install beautifulSoup4
pip install csv
pip install pandas

The script call should be made as follows:

python main.py

Afterwards, it asks for the population you want to search. This town should be written without accents (e.g. Castellar del valles, Barcelona, Caldes de Montbui).

Finally generate a .csv file with a set of columns:

Type: Type of property (House, Flat, Chalet...)
Size: Square meters of the property
Baths: Number of bathrooms in the property
Rooms: Number of rooms in the property
Price: Price of the property
