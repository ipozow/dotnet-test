# Recursos generados

Este directorio queda vacío en el control de versiones porque los iconos y pantallas de inicio de Windows se generan automáticamente a partir de los archivos vectoriales ubicados en `Resources/`.

Para producir nuevamente los `.png` utilizados por el manifiesto de Windows ejecuta:

```bash
dotnet build -f net10.0-windows10.0.19041
```

El comando compila el proyecto y, durante el proceso, el pipeline de .NET MAUI crea los recursos en la carpeta de `obj` y los copia a la salida de publicación.
