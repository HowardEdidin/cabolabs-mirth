# 0011_http_xml_java

Ejemplo de ejecuci�n de c�digo Java desde Mirth.

El canal recibe un mensaje XML por HTTP, y en funci�n de un par�metro "action" ejecuta una determinada acci�n sobre los datos recibidos, y esa acci�n est� implementada en c�digo Java como una librer�a externa a Mirth Connnect.

Ejemplo de mensaje XML:

```
<mensaje>
    <nombre>Pablo</nombre>
</mensaje>
```

URL: http://localhost:6674/java/
