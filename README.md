# diputades_nets

Primero correr ideal_points.Rmd para generar la lista de todos los legisladores con su punto ideal calculado para cada periodo.
Luego, create_distance_matrix.Rmd, para calcular las distancias entre legisladores, medida en valor absoluto de la diferencia de punto ideal.
Finalmente, correr networks.Rmd, el cual creara una carpeta por periodo y en ella pondra varias versiones del mismo grafo pero con diferente layout, para lograr una proyeccion que sea mas aceptable. Ademas, creara los subgrafos de cada periodo, correspondientes a cada comunidad y emitira las listas de nombres y bloque de cada uno de ellos en formato csv.
