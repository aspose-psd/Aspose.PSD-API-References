---
title: "Clase Cache"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Cache. Contiene la configuración de caché."
type: docs
weight: 240
url: /es/net/aspose.psd/cache/
---
{{< psd/tize >}}
## Cache class

Contiene la configuración de caché.

```csharp
public static class Cache
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| static [AllocatedDiskBytesCount](../../aspose.psd/cache/allocateddiskbytescount/) { get; } | Obtiene el recuento de bytes asignados en disco. |
| static [AllocatedMemoryBytesCount](../../aspose.psd/cache/allocatedmemorybytescount/) { get; } | Obtiene el recuento de bytes asignados en memoria. |
| static [CacheFolder](../../aspose.psd/cache/cachefolder/) { get; set; } | Obtiene o establece la carpeta de caché. |
| static [CacheType](../../aspose.psd/cache/cachetype/) { get; set; } | Obtiene o establece el esquema de caché utilizado. |
| static [ExactReallocateOnly](../../aspose.psd/cache/exactreallocateonly/) { get; set; } | Obtiene o establece un valor que indica si la reasignación debe ser exacta o no. Si la reasignación no es exacta, el rendimiento debería ser mayor. |
| static [MaxDiskSpaceForCache](../../aspose.psd/cache/maxdiskspaceforcache/) { get; set; } | Obtiene o establece el espacio máximo disponible en disco para la caché. El valor especificado es el recuento de megabytes. |
| static [MaxMemoryForCache](../../aspose.psd/cache/maxmemoryforcache/) { get; set; } | Obtiene o establece la memoria máxima disponible para la caché en memoria. El valor especificado es el recuento de megabytes. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| static [SetDefaults](../../aspose.psd/cache/setdefaults/)() | Establece la configuración de `Cache` a los valores predeterminados. |

## Ejemplos

Este ejemplo demuestra el uso de Aspose.PSD.Cache

```csharp
[C#]

// Por defecto, la carpeta de caché se establece en el directorio temporal local del usuario.
// También puedes especificar otra carpeta de caché distinta a la predeterminada como se muestra a continuación:
// Cache.CacheFolder = @"D:\\MyTemp";

string path = "C:\\temp\\image.psd";

// El modo automático es flexible y eficiente
Cache.CacheType = CacheType.Auto;

// El valor predeterminado es 0, lo que significa que no hay límite superior
Cache.MaxDiskSpaceForCache = 1073741824; // 1 gigabyte
Cache.MaxMemoryForCache = 1073741824; // 1 gigabyte

// No se recomienda cambiar la siguiente propiedad ya que puede afectar significativamente el rendimiento
Cache.ExactReallocateOnly = false;

// En cualquier momento puedes comprobar cuántos bytes están actualmente asignados para memoria o disco 
// caché examinando las siguientes propiedades
long l1 = Cache.AllocatedDiskBytesCount;
long l2 = Cache.AllocatedMemoryBytesCount;

// Realiza algún procesamiento de imágenes como se muestra a continuación
using (RasterImage image = (RasterImage)Image.Load(path))
{
    Color[] pixels = new Color[image.Width * image.Height];
    for (int i = 0; i < pixels.Length; i++)
    {
        pixels[i] = Color.White;
    }

    image.SavePixels(image.Bounds, pixels);

    // Después de ejecutar el código anterior, se asignarán 40000 bytes en memoria.
    long diskBytes = Cache.AllocatedDiskBytesCount;
    long memoryBytes = Cache.AllocatedMemoryBytesCount;
}

// Las propiedades de asignación pueden usarse para comprobar si todos los objetos de Aspose.PSD fueron eliminados correctamente.
// En caso de que hayas olvidado llamar a dispose en algún objeto, los valores de caché serán diferentes de 0.
l1 = Cache.AllocatedDiskBytesCount;
l2 = Cache.AllocatedMemoryBytesCount;
```

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


