# Guía para agentes

Este repositorio contiene un proyecto multiplataforma basado en **.NET 10 Release Candidate 1** y **.NET MAUI**. El lenguaje principal es **C# 13** junto con vistas declarativas en **XAML**. Cuando agregues código nuevo:

- Prefiere sintaxis moderna de C# (pattern matching, `using` implícitos, records, etc.) siempre que mantenga la legibilidad.
- Mantén los textos visibles para las personas usuarias en español.
- Asegúrate de que las ventanas principales funcionen en Windows, macOS (Mac Catalyst) e iOS.
- Si dispones del SDK instalado en tu entorno, ejecuta `dotnet build` antes de finalizar tus cambios. Si no es posible, documenta la limitación en el resumen.
- Evita introducir dependencias externas sin describir el motivo en la descripción del cambio.

La estructura del proyecto se organiza a través de un único `HelloMaui.csproj` que apunta a los recursos compartidos y a las plataformas específicas.
