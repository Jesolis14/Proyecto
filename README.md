# Proyecto
Primero tenemos que instalar las dependencias usando el siguiente código
!pip install mysql-connector-python matplotlib pandas.
Si deseas agregar una dependencia en específico, le tienes que poner un igual y la dependencia específica que deseas.

Segundo tienes que conectar tu libreta con mysql, usando la funcion **connect_to_db()**, le tendras que dar la información que tienes en mysql.

Tercero, con **fetch_data(query)** lo usas para ejecutar una consulta y devolver los resultados en un DataFrame.
