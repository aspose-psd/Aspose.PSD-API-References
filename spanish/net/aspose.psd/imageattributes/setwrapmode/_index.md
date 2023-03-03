---
title: ImageAttributes.SetWrapMode
second_title: Referencia de API de Aspose.PSD para .NET
description: ImageAttributes método. Establece el modo de ajuste que se usa para decidir cómo colocar una textura en mosaico a lo largo de una forma o en los límites de la forma. Una textura se coloca en mosaico a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.
type: docs
weight: 210
url: /es/net/aspose.psd/imageattributes/setwrapmode/
---
## SetWrapMode(WrapMode) {#setwrapmode}

Establece el modo de ajuste que se usa para decidir cómo colocar una textura en mosaico a lo largo de una forma o en los límites de la forma. Una textura se coloca en mosaico a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

```csharp
public void SetWrapMode(WrapMode mode)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| mode | WrapMode | un elemento de[`WrapMode`](../../wrapmode/) que especifica cómo se utilizan las copias repetidas de una imagen para colocar en mosaico un área. |

### Ver también

* enum [WrapMode](../../wrapmode/)
* class [ImageAttributes](../)
* espacio de nombres [Aspose.PSD](../../imageattributes/)
* asamblea [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color) {#setwrapmode_1}

Establece el modo de ajuste y el color que se usa para decidir cómo colocar una textura en mosaico a lo largo de una forma o en los límites de la forma. Una textura se coloca en mosaico a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

```csharp
public void SetWrapMode(WrapMode mode, Color color)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| mode | WrapMode | un elemento de[`WrapMode`](../../wrapmode/) que especifica cómo se utilizan las copias repetidas de una imagen para colocar en mosaico un área. |
| color | Color | Un[`ImageAttributes`](../) objeto que especifica el color de los píxeles fuera de una imagen renderizada. Este color es visible si el parámetro de modo se establece enClamp y el rectángulo de origen pasado a DrawImage es más grande que la propia imagen. |

### Ver también

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* espacio de nombres [Aspose.PSD](../../imageattributes/)
* asamblea [Aspose.PSD](../../../)

---

## SetWrapMode(WrapMode, Color, bool) {#setwrapmode_2}

Establece el modo de ajuste y el color que se usa para decidir cómo colocar una textura en mosaico a lo largo de una forma o en los límites de la forma. Una textura se coloca en mosaico a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando.

```csharp
public void SetWrapMode(WrapMode mode, Color color, bool clamp)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| mode | WrapMode | un elemento de[`WrapMode`](../../wrapmode/) que especifica cómo se utilizan las copias repetidas de una imagen para colocar en mosaico un área. |
| color | Color | Un objeto de color que especifica el color de los píxeles fuera de una imagen renderizada. Este color es visible si el parámetro de modo se establece enClamp y el rectángulo de origen pasado a DrawImage es más grande que la propia imagen. |
| clamp | Boolean | Este parámetro no tiene efecto. Establézcalo en falso. |

### Ver también

* enum [WrapMode](../../wrapmode/)
* struct [Color](../../color/)
* class [ImageAttributes](../)
* espacio de nombres [Aspose.PSD](../../imageattributes/)
* asamblea [Aspose.PSD](../../../)


