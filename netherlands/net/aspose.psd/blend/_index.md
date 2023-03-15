---
title: Class Blend
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Blend klas. Definieert een overvloeipatroon. Deze klasse kan niet worden geërfd.
type: docs
weight: 110
url: /nl/net/aspose.psd/blend/
---
## Blend class

Definieert een overvloeipatroon. Deze klasse kan niet worden geërfd.

```csharp
public sealed class Blend
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Blend](blend/#constructor)() | Initialiseert een nieuw exemplaar van het`Blend` klas. Het aantal elementen in de factor- en blend-arrays is gelijk aan 1. |
| [Blend](blend/#constructor_1)(int) | Initialiseert een nieuw exemplaar van het`Blend` klasse met het opgegeven aantal factoren en posities. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Factors](../../aspose.psd/blend/factors/) { get; set; } | Hiermee wordt de reeks overvloeifactoren voor het verloop opgehaald of ingesteld. |
| [Positions](../../aspose.psd/blend/positions/) { get; set; } | Haalt de reeks overvloeiposities voor het verloop op of stelt deze in. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.psd/blend/equals/)(object) | Test of het opgegeven object een`Blend` klasse en is hiermee gelijk`Blend` klasse. |
| override [GetHashCode](../../aspose.psd/blend/gethashcode/)() | Retourneert een hash-code voor deze instantie. |

### Opmerkingen

Het typische gebruik van de overvloeiklasse is het definiëren van een overvloeipatroon voor penseel. En dus moeten de overvloei-eigenschappen zorgvuldig worden geïnitialiseerd. Null-arrays zijn niet toegestaan. Het penseel genereert de juiste uitzondering als de matrix met overvloeifactoren of posities leeg is of als hun lengte niet hetzelfde is. Als er twee of meer elementen in de matrix posities zijn, moet het eerste element 0 zijn en het laatste element 1.

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


