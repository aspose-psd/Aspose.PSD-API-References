---
title: "Cache.ExactReallocateOnly"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Cache propiedad. Obtiene o establece un valor que indica si la reasignación debe ser exacta o no. Si la reasignación no es exacta, el rendimiento debería ser mayor"
type: docs
weight: 50
url: /es/net/aspose.psd/cache/exactreallocateonly/
---
{{< psd/tize >}}
## Cache.ExactReallocateOnly property

Obtiene o establece un valor que indica si la reasignación debe ser exacta o no. Si la reasignación no es exacta, el rendimiento debería ser mayor.

```csharp
public static bool ExactReallocateOnly { get; set; }
```

### Property Value

`true` si la reasignación es exacta; de lo contrario, `false`.

## Observaciones

La reasignación exacta realizará la reasignación de memoria adicional solo hasta el límite superior especificado. Al establecer el límite superior para la memoria en tiempo de ejecución durante la reasignación, los datos en caché se copiarán al disco si es posible. Al establecer el límite superior para la memoria en disco durante la reasignación, se lanzará la excepción correspondiente. El rendimiento debería ser mayor si esta opción está desactivada, ya que no se realizará copia adicional si es posible; sin embargo, esto también puede llevar a superar los límites superiores especificados para la memoria o el disco.

### Ver también

* class [Cache](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


