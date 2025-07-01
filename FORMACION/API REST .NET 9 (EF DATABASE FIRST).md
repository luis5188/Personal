
**Instalación de paquetes Nuget:

☑️ Microsoft.EntityFrameworkCore 
☑️ Microsoft.EntityFrameworkCore.SqlServer 
☑️ Microsoft.EntityFrameworkCore.Tools 
☑️ Swashbuckle.AspNetCore 
☑️ Swashbuckle.AspNetCore.Swagger

**Ejecutar en la consola de administrador de paquetes:

Scaffold-DbContext "Server=ESDESLMLAP;Database=GestionActividades;User Id=sa;Password=jupiter1*;TrustServerCertificate=True;" Microsoft.EntityFrameworkCore.SqlServer -OutputDir Models -Force

**Eliminar de context el metodo:

OnConfiguring


