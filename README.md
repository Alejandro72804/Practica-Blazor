# 🎯 Practica-Blazor

## Descripción

Este es un proyecto de **práctica** desarrollado con **Blazor**, un framework moderno de Microsoft para construir aplicaciones web interactivas usando C# en lugar de JavaScript. 

El objetivo principal de este proyecto es explorar y practicar los conceptos fundamentales de Blazor, incluyendo componentes reutilizables, vinculación de datos, manejo de eventos y más.

---

## 📋 Requisitos Previos

Antes de comenzar, asegúrate de tener instalado:

- [.NET 8.0 SDK](https://dotnet.microsoft.com/download) o superior
- [Visual Studio 2022](https://visualstudio.microsoft.com/es/) o [Visual Studio Code](https://code.visualstudio.com/)
- Git

---

## 🚀 Instalación y Configuración

### 1. Clonar el repositorio

```bash
git clone https://github.com/Alejandro72804/Practica-Blazor.git
cd Practica-Blazor
```

### 2. Restaurar dependencias

```bash
dotnet restore
```

### 3. Ejecutar el proyecto

```bash
dotnet run
```

La aplicación estará disponible en `https://localhost:5001` (o el puerto configurado).

---

## 📁 Estructura del Proyecto

```
Practica-Blazor/
├── Components/          # Componentes reutilizables
├── Pages/              # Páginas de la aplicación
├── Layouts/            # Layouts/plantillas
├── wwwroot/            # Archivos estáticos (CSS, imágenes, JS)
├── Program.cs          # Configuración de la aplicación
├── appsettings.json    # Configuración
└── README.md           # Este archivo
```

---

## 🔧 Tecnologías Utilizadas

- **Blazor WebAssembly** o **Blazor Server** - Framework principal
- **C#** - Lenguaje de programación
- **.NET** - Plataforma de desarrollo
- **HTML/CSS** - Maquetación y estilos
- **Bootstrap** o **CSS personalizado** - Framework de diseño

---

## 📚 Conceptos Practicados

Este proyecto cubre los siguientes conceptos de Blazor:

- ✅ Componentes Blazor
- ✅ Vinculación de datos (Data Binding)
- ✅ Manejo de eventos
- ✅ Validación de formularios
- ✅ Enrutamiento
- �� Ciclo de vida de componentes
- ✅ Inyección de dependencias
- ✅ Interoperabilidad con JavaScript (si aplica)

---

## 💡 Ejemplo de Uso

### Componente Simple

```csharp
@page "/contador"
<h3>Contador</h3>
<p>Valor actual: @contador</p>
<button class="btn btn-primary" @onclick="IncrementarContador">
    Incrementar
</button>

@code {
    private int contador = 0;

    private void IncrementarContador()
    {
        contador++;
    }
}
```

---

## 🤝 Contribuciones

Este es un proyecto personal de práctica. Si deseas realizar cambios o mejoras:

1. Realiza un fork del repositorio
2. Crea una rama con tu feature (`git checkout -b feature/MiFeature`)
3. Commit tus cambios (`git commit -m 'Añado MiFeature'`)
4. Push a la rama (`git push origin feature/MiFeature`)
5. Abre un Pull Request

---

## 📖 Recursos Útiles

- [Documentación oficial de Blazor](https://learn.microsoft.com/es-es/aspnet/core/blazor)
- [Blazor WebAssembly](https://learn.microsoft.com/es-es/aspnet/core/blazor/hosting-models)
- [Componentes Blazor](https://learn.microsoft.com/es-es/aspnet/core/blazor/components)
- [Tutorial oficial de Microsoft](https://learn.microsoft.com/es-es/training/paths/build-web-apps-with-blazor/)

---

## 📝 Licencia

Este proyecto está disponible bajo la licencia [MIT](LICENSE) (opcional - agrega una licencia si lo deseas).

---

## 👤 Autor

**Alejandro72804**

- GitHub: [@Alejandro72804](https://github.com/Alejandro72804)
- Repositorio: [Practica-Blazor](https://github.com/Alejandro72804/Practica-Blazor)

---

## ⭐ Notas

- Este es un proyecto con fines educativos
- Se actualiza conforme se avanza en el aprendizaje de Blazor
- Los comentarios y retroalimentación son bienvenidos

---

**¡Hecho con ❤️ para practicar Blazor!**