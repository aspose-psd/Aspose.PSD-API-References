---
title: "Klasse Metered"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "Aspose.PSD.Metered-Klasse. Stellt Methoden zum Festlegen des gemessenen Schlüssels bereit."
type: docs
weight: 5610
url: /de/net/aspose.psd/metered/
---
{{< psd/tize >}}
## Metered class

Stellt Methoden zum Setzen des gemessenen Schlüssels bereit.

```csharp
public class Metered
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Metered](metered/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Equals](../../aspose.psd/metered/equals/)(object) | Bestimmt, ob das angegebene Objekt dieser Instanz gleich ist. |
| [GetProductName](../../aspose.psd/metered/getproductname/)() | Gibt den Namen des Produkts zurück. |
| [SetMeteredKey](../../aspose.psd/metered/setmeteredkey/)(string, string) | Setzt den öffentlichen und privaten gemessenen Schlüssel. Wenn Sie eine gemessene Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Wenn jedoch das Hochladen von Verbrauchsdaten ständig fehlschlägt und 24 Stunden überschreitet, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf. |
| static [GetConsumptionCredit](../../aspose.psd/metered/getconsumptioncredit/)() | Gibt das Verbrauchsguthaben zurück |
| static [GetConsumptionQuantity](../../aspose.psd/metered/getconsumptionquantity/)() | Gibt die Dateigröße des Verbrauchs zurück |
| static [IsMeteredLicensed](../../aspose.psd/metered/ismeteredlicensed/)() | Prüfen, ob Metered lizenziert ist |

## Beispiele

In diesem Beispiel wird versucht, den öffentlichen und privaten Metered-Schlüssel zu setzen

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

### Siehe auch

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


