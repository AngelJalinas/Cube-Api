# API de Exploración Multidimensional

Esta API nos permite la exploración de datos multidimensionales conectandonos a una base de datos en SQL Server, Analysis Services (SSAS). A través de distintos endpoints, como usuarios podemos realizar consultas y explorar los datos estructurados en un modelo multidimensional. La exploraciión del cubo se puede ejecutar tanto en Visual Studio como en SQL Server Management Studio.

## Tecnologías y Extensiones Utilizadas

- **Microsoft.AnalysisServices.AdomdClient**: Utilizado para conectar con SSAS y trabajar con el `CellSet`, permitiendo la exploración de datos multidimensionales.
- **System.Collections.Generic**: Utilizado para el manejo de colecciones como `List` y `Dictionary` en la API.
- **Microsoft.AspNetCore.Builder**: Usado para configurar el `WebApplication`.
- **Microsoft.Extensions.DependencyInjection**: Proporciona el servicio de exploración de API.
- **Microsoft.Extensions.Hosting**: Utilizado para gestionar el ambiente de desarrollo o producción.

## Funcionalidades

- Conexión con SQL Server Analysis Services (SSAS) para realizar consultas en un modelo multidimensional.
- Endpoints que permiten a los usuarios interactuar con datos de una base de datos multidimensional para exploración y análisis.
- Integración con Visual Studio y SQL Server Management Studio para facilitar el análisis y la administración de datos.


**Instalar las Dependencias**:
   dotnet add package Microsoft.AnalysisServices.AdomdClient
   dotnet add package Microsoft.AspNetCore

   
