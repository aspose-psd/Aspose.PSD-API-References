---
title: "ImageAttributes.SetWrapMode"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método ImageAttributes. Establece el modo de ajuste que se usa para decidir cómo mosaicar una textura a lo largo de una forma o en los bordes de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando."
type: docs
weight: 210
url: /es/net/aspose.psd/imageattributes/setwrapmode/
---
{{< psd/tize >}}
## SetWrapMode(WrapMode) {#setwrapmode}

Establece el modo de ajuste que se utiliza para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

```csharp
public void SetWrapMode(WrapMode mode)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | WrapMode | Un elemento de [`WrapMode`](../../wrapmode/) que especifica cómo se utilizan copias repetidas de una imagen para mosaicar un área. |

### Ver también

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

Establece el modo de ajuste y el color utilizados para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | WrapMode | Un elemento de [`WrapMode`](../../wrapmode/) que especifica cómo se utilizan copias repetidas de una imagen para mosaicar un área. |
| color | Color | Un objeto [`ImageAttributes`](../) que especifica el color de los píxeles fuera de una imagen renderizada. Este color es visible si el parámetro mode está configurado en Clamp y el rectángulo de origen pasado a DrawImage es más grande que la propia imagen. |

### Ver también

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

Establece el modo de ajuste y el color utilizados para decidir cómo mosaicar una textura a lo largo de una forma, o en los límites de la forma. Una textura se mosaica a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mode | WrapMode | Un elemento de [`WrapMode`](../../wrapmode/) que especifica cómo se utilizan copias repetidas de una imagen para mosaicar un área. |
| color | Color | Un objeto de color que especifica el color de los píxeles fuera de una imagen renderizada. Este color es visible si el parámetro mode está configurado en Clamp y el rectángulo de origen pasado a DrawImage es más grande que la propia imagen. |
| clamp | Boolean | Este parámetro no tiene efecto. Establézcalo en false. |

### Ver también

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


