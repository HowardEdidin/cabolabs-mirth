# 0002 Variable Mappings

Recibe mensajes HL7 v2.x por MLLP, extrae datos de pacientes y los mapea a variables.

Se agreg� un destination filter para no dejar pasar los mensajes que tienen un valor de sexo inv�lido.

Destination 2 es un Database Writer que est� deshabilitado, para usarlo necesita instalar MySQL, crear la base de datos "mirth_tests" y la tabla "pacientes" seg�n: https://github.com/ppazos/cabolabs-mirth/blob/master/mirth/mysql_database_tables.sql