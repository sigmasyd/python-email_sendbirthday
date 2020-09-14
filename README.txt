Emails Automáticos de Felicitaciones con Python | Al Andrade
from: https://www.youtube.com/watch?v=Xv-3tukj9KM&ab_channel=AlAndrade

#####
creamos la base de datos "birthdays"
-----------------------------------
$ sqlite3 birthdays.db

SQL para crear la tabla "clientes" in SQLite
-----------------------------------
create table clientes(name text,last_name text,email text,birthday date);

comandos para importar los datos desde el archivo data.csv dentro de la tabla "clientes"
-----------------------------------
.import data.csv clientes

secret: nmssaydlrnnipdqt