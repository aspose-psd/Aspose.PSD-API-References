---
title: Class Metered
second_title: Referencia de API de Aspose.PSD para .NET
description: Aspose.PSD.Metered clase. Proporciona métodos para configurar la clave medida.
type: docs
weight: 5120
url: /es/net/aspose.psd/metered/
---
## Metered class

Proporciona métodos para configurar la clave medida.

Proporciona métodos medidos para la integración

```csharp
public class Metered
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Metered](metered/)() | Constructor predeterminado |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | Determina si el especificadoObject , es igual a esta instancia. |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | Establece claves públicas y privadas medidas |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | Obtiene crédito de consumo |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | Obtiene el tamaño del archivo de consumo |

### Ejemplos

En este ejemplo, se intentará establecer una clave pública y privada medidas

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Ver también

* espacio de nombres [Aspose.PSD](../../aspose.psd/)
* asamblea [Aspose.PSD](../../)


