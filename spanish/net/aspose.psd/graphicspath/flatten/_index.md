---
title: "GraphicsPath.Flatten"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método GraphicsPath. Convierte cada curva en esta ruta en una secuencia de segmentos de línea conectados"
type: docs
weight: 90
url: /es/net/aspose.psd/graphicspath/flatten/
---
{{< psd/tize >}}
## Flatten() {#flatten}

Convierte cada curva en esta ruta en una secuencia de segmentos de línea conectados.

```csharp
public void Flatten()
```

### Ver también

* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

Aplica la transformación especificada y luego convierte cada curva en este [`GraphicsPath`](../) en una secuencia de segmentos de línea conectados.

```csharp
public void Flatten(Matrix matrix)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | Matrix | Una [`Matrix`](../../matrix/) mediante la cual transformar este [`GraphicsPath`](../) antes de aplanar. |

### Ver también

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Convierte cada curva en este [`GraphicsPath`](../) en una secuencia de segmentos de línea conectados.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| matrix | Matrix | Una [`Matrix`](../../matrix/) mediante la cual transformar este [`GraphicsPath`](../) antes de aplanar. |
| planitud | Single | Especifica el error máximo permitido entre la curva y su aproximación aplanada. Un valor de 0.25 es el predeterminado. Reducir el valor de planitud aumentará el número de segmentos de línea en la aproximación. |

### Ver también

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


