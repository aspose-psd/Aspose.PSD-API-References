---
title: "Region.Equals"
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Método Region. Prueba si la Region especificada es idéntica a esta Region en la superficie de dibujo especificada"
type: docs
weight: 40
url: /es/net/aspose.psd/region/equals/
---
{{< psd/tize >}}
## Equals(Region, Graphics) {#equals}

Prueba si la [`Region`](../) especificada es idéntica a esta [`Region`](../) en la superficie de dibujo especificada.

```csharp
public bool Equals(Region region, Graphics g)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| region | Region | La [`Region`](../) a probar. |
| g | Graphics | Un [`Graphics`](../../graphics/) que representa una superficie de dibujo. |

### Valor devuelto

True si el interior de la región es idéntico al interior de esta región cuando se aplica la transformación asociada con el parámetro *g*; de lo contrario, false.

### Excepciones

| excepción | condición |
| --- | --- |
| ArgumentNullException | *g *or* region* es nulo. |

### Ver también

* class [Graphics](../../graphics/)
* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## Equals(object) {#equals_1}

Comprueba si los objetos son iguales.

```csharp
public override bool Equals(object obj)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| obj | Object | El otro objeto. |

### Valor devuelto

El resultado de la comparación de igualdad.

### Ver también

* class [Region](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


