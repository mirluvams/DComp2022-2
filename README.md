# Visualization of worldwide flights using Distributed Computing 
# Affiliation
Final Project for the Distributed Computing 2022-2 class, taught by Dr. Victor de la Luz at the _Universidad Nacional Autónoma de México_ (National Autonomous University of México | UNAM), in its _Escuela Nacional de Estudios Superiores Unidad Morelia_ Campus (National School of Superior-Level Studies, _Morelia_ Campus | ENES Morelia), as part of its _Licenciatura en Tecnologías para la Información en Ciencias_ career plan (Bs. in Information Technologies applied to Science | L.T.I.C.).

> DEVELOPED BY:
>
> Alexis Hassiel Nuviedo Arriaga ([@nuviedo](https://github.com/nuviedo))
> 
> Miriam Guadalupe Valdez | mirluvams@gmail.com ([@mirluvams](https://github.com/mirluvams)) |
> 
> Luis David Huante | luisdhuante@gmail.com ([@LuisDHuante](https://github.com/LuisDHuante)) |


# Introduction
The following project intends to provide a functional endpoint in which a potential user can visualize a map containing worldwide flight routes in real time. 

The need for such a project stems mainly out of curiosity, as the patterns of flight of a population can aid in the understanding of the global situation as a whole, such as, for example, visualizing armed conflicts or trade associations.

As a final project, this aims to be a practical demostration of how a series of computers in parallel can be used to obtain an easily scalable product that could potentially be commercialized and expanded upon once completed, without relying on a single, high performance computer to perform the entire process.

# Objectives
The expected output of this project is a set of four servers, each of which provide an essential part of the project. Their denomination is as follows:

> Data Retrieval Server

In charge of obtaining real-time data from the OpenSky Network API, through the use of Python. Will relay said information in a timely manner to the Storage Server.

> Storage Server

In charge of storing historical data, to be sorted and retrieved as needed by the Processing Server.

> Processing Server

In charge of generating map images on demand, based on the request by the Web Server API

> Web Server

In charge of displaying map images to the end user through a modern web interface


# Toolset
The project is to be developed by making use of modern Python 3 libraries, including but not limited to:
* [The OpenSky Network API](https://opensky-network.org/) for data collection of near-real time flight information. 
* [Folium](https://github.com/python-visualization/folium), a wrapper to the [Leaflet.js](https://leafletjs.com/) JavaScript mapping library.
* [NumPy](https://numpy.org/)
* [Pandas](https://pandas.pydata.org/)

Additionally, it plans to make use of the following web technologies, on top of the usual development stack:
* [Apache HTTPD](https://httpd.apache.org/)
* [MariaDB](https://mariadb.org/)
* [PHP](https://www.php.net/)
* [Bootstrap](https://getbootstrap.com/)

# Methodology
...



# Usage Instructions & Requirements
...



# Results
...



# Conclusions
...


