---
title: "PixelDataFormat.Rgba64Bpp"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Propiedad PixelDataFormat. Obtiene el PixelDataFormat definido para 64 bits por píxel con 16 bits para cada uno de los canales alfa, rojo, verde y azul"
type: docs
weight: 110
url: /es/net/aspose.psd/pixeldataformat/rgba64bpp/
---
{{< psd/tize >}}
## PixelDataFormat.Rgba64Bpp property

Obtiene el [`PixelDataFormat`](../) definido para 64 bits por píxel con 16 bits para cada uno de los canales alfa, rojo, verde y azul.

```csharp
public static PixelDataFormat Rgba64Bpp { get; }
```

### Property Value

El [`PixelDataFormat`](../) definido para 64 bits por píxel con 16 bits para cada uno de los canales alfa, rojo, verde y azul.

## Ejemplos

El siguiente código demuestra el soporte de la clase RawColor en lugar de la estructura Color obsoleta.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### Ver también

* class [PixelDataFormat](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


