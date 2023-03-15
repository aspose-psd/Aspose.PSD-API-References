---
title: GraphicsPath.Flatten
second_title: Referencia de API de Aspose.PSD para .NET
description: GraphicsPath método. Convierte cada curva de esta ruta en una secuencia de segmentos de línea conectados.
type: docs
weight: 90
url: /es/net/aspose.psd/graphicspath/flatten/
---
## Flatten() {#flatten}

Convierte cada curva de esta ruta en una secuencia de segmentos de línea conectados.

```csharp
public void Flatten()
```

### Ver también

* class [GraphicsPath](../)
* espacio de nombres [Aspose.PSD](../../graphicspath/)
* asamblea [Aspose.PSD](../../../)

---

## Flatten(Matrix) {#flatten_1}

Aplica la transformación especificada y luego convierte cada curva en este[`GraphicsPath`](../) en una secuencia de segmentos de línea conectados.

```csharp
public void Flatten(Matrix matrix)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| matrix | Matrix | A[`Matrix`](../../matrix/) por el cual transformar esto[`GraphicsPath`](../) antes de aplanar. |

### Ver también

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* espacio de nombres [Aspose.PSD](../../graphicspath/)
* asamblea [Aspose.PSD](../../../)

---

## Flatten(Matrix, float) {#flatten_2}

Convierte cada curva en este[`GraphicsPath`](../) en una secuencia de segmentos de línea conectados.

```csharp
public void Flatten(Matrix matrix, float flatness)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| matrix | Matrix | A[`Matrix`](../../matrix/) por el cual transformar esto[`GraphicsPath`](../) antes de aplanar. |
| flatness | Single | Especifica el error máximo permitido entre la curva y su aproximación aplanada. Un valor de 0,25 es el predeterminado. Reducir el valor de planitud aumentará el número de segmentos de línea en la aproximación. |

### Ver también

* class [Matrix](../../matrix/)
* class [GraphicsPath](../)
* espacio de nombres [Aspose.PSD](../../graphicspath/)
* asamblea [Aspose.PSD](../../../)


