---
title: "Clase Metered."
second_title: "Referencia de API de Aspose.PSD para .NET"
description: "Clase Aspose.PSD.Metered. Proporciona métodos para establecer la clave medida"
type: docs
weight: 5610
url: /es/net/aspose.psd/metered/
---
{{< psd/tize >}}
## Metered class

Proporciona métodos para establecer la clave medida.

```csharp
public class Metered
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Metered](metered/)() | El constructor predeterminado. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | Determina si el Object especificado es igual a esta instancia. |
| [GetProductName](../../aspose.psd/metered/getproductname/)() | Obtiene el nombre del producto. |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | Establece la clave pública y privada medida. Si compras una licencia medida, al iniciar la aplicación, se debe llamar a esta API; normalmente, eso es suficiente. Sin embargo, si siempre falla la carga de los datos de consumo y supera las 24 horas, la licencia se establecerá en estado de evaluación; para evitar ese caso, deberías comprobar regularmente el estado de la licencia y, si está en estado de evaluación, llamar a esta API nuevamente. |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | Obtiene el crédito de consumo |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | Obtiene el tamaño del archivo de consumo |
| static [IsMeteredLicensed](../../aspose.psd/metered/ismeteredlicensed/)() | Verifica si la licencia medida está licenciada |

## Ejemplos

En este ejemplo, se intentará establecer la clave pública y privada medida

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Ver también

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


