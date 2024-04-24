
No muestra los permisos del archivo.

```bash
ls -al helloword.sh
```

Dar permisos de ejecución
```bash
chmod +x helloworld.sh
```

Para ejecutar el archivo
```bash
./helloworld.sh
```

## Guardar salida

Guardar en un archivo txt, esto sobreescribe todo lo que haya existido en el archivo.
```bash
cat > hola.txt
```

Guardar en un archivo txt sin sobreescribir lo que ya esta.
```bash
cat >> hola.txt
```

## Lectura

Para guardar datos en una variable

```bash
#! /bin/bash
echo "Ingresa tu edad: "
read age
echo "Esta es tu edad: $age años"
```