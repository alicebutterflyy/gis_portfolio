# 3-dimensional glacier flow simulation (Matlab, Python, QGIS)

Over the course of my internship, I worked along a project led by the Bureau de Recherches Géologiques et Minières (BRGM), a French geological survey institution. The aim of this project is to deepen the knowledge of the geological and sedimentary history of the Pyrenees (Monod _et al._, 2018). I worked specifically on the history of the last deglaciation (starting from about 20 000 BC). 

Following the photo-interpretation of DEMS over my specific sector, I managed to get vector shapes of many glacial moraines, as show the map below.

The aim of my internship was then to translate a Matlab program (Harper & Humphrey, 2003) into a Python application, which would help me simulate ice flow and correlate the different deposits together. The program which I worked on allows the user to modify climatic parameters (temperature and rain) and then obtain the 3D characteristics of the glacier resulting of those climatic conditions. After translating the program in Python, I also made it available as a ArcGIS toolbox available at [this address](https://github.com/alicelamure/GlacierSimulation). I added some extra parameters, using the rasterio library, such as automatic georeferencing, generation of surface **and** thickness rasters, etc. Below are two examples of the maps produced using this program.



Those maps were then used to highlight the existence of halts during the glaciers' retreat. The thickness rasters also allowed for the reconstruction of the Equilibrium Line Altitude (ELA) of each retreating glacier using an ArcGIS toolbox developed by Pellitero _et al._ (2015).

## Data
BRGM, Institut National Géographique, Taillefer (1966)

## Cited literature
- Harper, J.T., et Humphrey, N.F.,« High altitude Himalayan climate inferred from glacial ice flux », Geophysical research letters, 30-14, 2003.
- Monod, B., Gandolfi, J.M., Saplairoles, M., « Amélioration de la connaissance géologique des formations fluvioglaciaires dans les Pyrénées », Programme POTAPYR, BRGM, 2018.
- Pellitero, R., Rea B.R., Spagnolo, M., Bakke, J., Hughes, P., Ivy-Ochs, S., Lukas, S., Ribolini, A., « A GIS tool for automatic calculation of glacier equilibrium-line altitudes », Computers & Geosciences, 82, 2015.
