---
title: Class Region
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Region klas. Beschrijft het interieur van een grafische vorm die bestaat uit rechthoeken en paden. Deze klasse kan niet worden geërfd.
type: docs
weight: 5360
url: /nl/net/aspose.psd/region/
---
## Region class

Beschrijft het interieur van een grafische vorm die bestaat uit rechthoeken en paden. Deze klasse kan niet worden geërfd.

```csharp
public sealed class Region
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Region](region/#constructor)() | Initialiseert een nieuw`Region` . |
| [Region](region/#constructor_1)(GraphicsPath) | Initialiseert een nieuw`Region` met de aangegeven[`GraphicsPath`](../graphicspath/) . |
| [Region](region/#constructor_2)(Rectangle) | Initialiseert een nieuw`Region` van het gespecificeerde[`Rectangle`](../rectangle/)structuur. |
| [Region](region/#constructor_3)(RectangleF) | Initialiseert een nieuw`Region` van het gespecificeerde[`RectangleF`](../rectanglef/)structuur. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| [Complement](../../aspose.psd/region/complement/#complement)(GraphicsPath) | Werkt dit bij`Region` om het gedeelte van het gespecificeerde te bevatten[`GraphicsPath`](../graphicspath/) dat valt hier niet onder`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_1)(Rectangle) | Werkt dit bij`Region` om het gedeelte van het gespecificeerde te bevatten[`Rectangle`](../rectangle/) structuur die hier niet mee snijdt`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_2)(RectangleF) | Werkt dit bij`Region` om het gedeelte van het gespecificeerde te bevatten[`RectangleF`](../rectanglef/) structuur die hier niet mee snijdt`Region` . |
| [Complement](../../aspose.psd/region/complement/#complement_3)(Region) | Werkt dit bij`Region` om het gedeelte van het gespecificeerde te bevatten`Region` dat valt hier niet onder`Region` . |
| [DeepClone](../../aspose.psd/region/deepclone/)() | Maakt hiervan een exacte diepe kopie`Region` . |
| [Equals](../../aspose.psd/region/equals/#equals)(Region, Graphics) | Test of de opgegeven`Region` is identiek hieraan`Region` op het opgegeven tekenoppervlak. |
| [Exclude](../../aspose.psd/region/exclude/#exclude)(GraphicsPath) | Werkt dit bij`Region` om alleen het gedeelte van het interieur te bevatten dat het gespecificeerde niet snijdt[`GraphicsPath`](../graphicspath/) . |
| [Exclude](../../aspose.psd/region/exclude/#exclude_1)(Rectangle) | Werkt dit bij`Region` om alleen het gedeelte van het interieur te bevatten dat het gespecificeerde niet snijdt[`Rectangle`](../rectangle/)structuur. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_2)(RectangleF) | Werkt dit bij`Region` om alleen het gedeelte van het interieur te bevatten dat het gespecificeerde niet snijdt[`RectangleF`](../rectanglef/)structuur. |
| [Exclude](../../aspose.psd/region/exclude/#exclude_3)(Region) | Werkt dit bij`Region` om alleen het gedeelte van het interieur te bevatten dat het gespecificeerde niet snijdt`Region` . |
| [Intersect](../../aspose.psd/region/intersect/#intersect)(GraphicsPath) | Werkt dit bij`Region` naar de kruising van zichzelf met het gespecificeerde[`GraphicsPath`](../graphicspath/) . |
| [Intersect](../../aspose.psd/region/intersect/#intersect_1)(Rectangle) | Werkt dit bij`Region` naar de kruising van zichzelf met het gespecificeerde[`Rectangle`](../rectangle/)structuur. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_2)(RectangleF) | Werkt dit bij`Region` naar de kruising van zichzelf met het gespecificeerde[`RectangleF`](../rectanglef/)structuur. |
| [Intersect](../../aspose.psd/region/intersect/#intersect_3)(Region) | Werkt dit bij`Region` naar de kruising van zichzelf met het gespecificeerde`Region` . |
| [IsEmpty](../../aspose.psd/region/isempty/)(Graphics) | Test of dit`Region` heeft een leeg interieur op het opgegeven tekenoppervlak. |
| [IsInfinite](../../aspose.psd/region/isinfinite/)(Graphics) | Test of dit`Region` heeft een oneindig interieur op het opgegeven tekenoppervlak. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible)(Point) | Test of de opgegeven[`Point`](../point/) structuur zit hierin`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_2)(PointF) | Test of de opgegeven[`PointF`](../pointf/) structuur zit hierin`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_4)(Rectangle) | Test of een deel van het opgegeven[`Rectangle`](../rectangle/) structuur zit hierin`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_6)(RectangleF) | Test of een deel van het opgegeven[`RectangleF`](../rectanglef/) structuur zit hierin`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_11)(float, float) | Test of het gespecificeerde punt hierin is opgenomen`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_1)(Point, Graphics) | Test of de opgegeven[`Point`](../point/) structuur zit hierin`Region` wanneer getekend met behulp van de opgegeven[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_3)(PointF, Graphics) | Test of de opgegeven[`PointF`](../pointf/) structuur zit hierin`Region` wanneer getekend met behulp van de opgegeven[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_5)(Rectangle, Graphics) | Test of een deel van het opgegeven[`Rectangle`](../rectangle/) structuur zit hierin`Region` wanneer getekend met behulp van de opgegeven[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_7)(RectangleF, Graphics) | Test of een deel van het opgegeven[`RectangleF`](../rectanglef/) structuur zit hierin`Region` wanneer getekend met behulp van de opgegeven[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_12)(float, float, Graphics) | Test of het gespecificeerde punt hierin is opgenomen`Region` wanneer getekend met behulp van de opgegeven[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_8)(int, int, Graphics) | Test of het gespecificeerde punt hierin is opgenomen`Region` object wanneer getekend met behulp van de opgegeven[`Graphics`](../graphics/) object. |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_13)(float, float, float, float) | Test of een deel van de opgegeven rechthoek hierin is opgenomen`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_9)(int, int, int, int) | Test of een deel van de opgegeven rechthoek hierin is opgenomen`Region` . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_14)(float, float, float, float, Graphics) | Test of een deel van de opgegeven rechthoek hierin is opgenomen`Region` wanneer getekend met behulp van de opgegeven[`Graphics`](../graphics/) . |
| [IsVisible](../../aspose.psd/region/isvisible/#isvisible_10)(int, int, int, int, Graphics) | Test of een deel van de opgegeven rechthoek hierin is opgenomen`Region` wanneer getekend met behulp van de opgegeven[`Graphics`](../graphics/) . |
| [MakeEmpty](../../aspose.psd/region/makeempty/)() | Initialiseert dit`Region` naar een leeg interieur. |
| [MakeInfinite](../../aspose.psd/region/makeinfinite/)() | Initialiseert dit`Region` bezwaar maken tegen een oneindig interieur. |
| [Transform](../../aspose.psd/region/transform/)(Matrix) | Transformeert dit`Region` door de opgegeven[`Matrix`](../matrix/) . |
| [Translate](../../aspose.psd/region/translate/#translate_1)(float, float) | Verplaatst de coördinaten hiervan`Region`met het opgegeven bedrag. |
| [Translate](../../aspose.psd/region/translate/#translate)(int, int) | Verplaatst de coördinaten hiervan`Region`met het opgegeven bedrag. |
| [Union](../../aspose.psd/region/union/#union)(GraphicsPath) | Werkt dit bij`Region` tot de vereniging van zichzelf en het gespecificeerde[`GraphicsPath`](../graphicspath/) . |
| [Union](../../aspose.psd/region/union/#union_1)(Rectangle) | Werkt dit bij`Region` tot de vereniging van zichzelf en het gespecificeerde[`Rectangle`](../rectangle/)structuur. |
| [Union](../../aspose.psd/region/union/#union_2)(RectangleF) | Werkt dit bij`Region` tot de vereniging van zichzelf en het gespecificeerde[`RectangleF`](../rectanglef/)structuur. |
| [Union](../../aspose.psd/region/union/#union_3)(Region) | Werkt dit bij`Region` tot de vereniging van zichzelf en het gespecificeerde`Region` . |
| [Xor](../../aspose.psd/region/xor/#xor)(GraphicsPath) | Werkt dit bij`Region` naar de unie minus het snijpunt van zichzelf met het gespecificeerde[`GraphicsPath`](../graphicspath/) . |
| [Xor](../../aspose.psd/region/xor/#xor_1)(Rectangle) | Werkt dit bij`Region` naar de unie minus het snijpunt van zichzelf met het gespecificeerde[`Rectangle`](../rectangle/)structuur. |
| [Xor](../../aspose.psd/region/xor/#xor_2)(RectangleF) | Werkt dit bij`Region` naar de unie minus het snijpunt van zichzelf met het gespecificeerde[`RectangleF`](../rectanglef/)structuur. |
| [Xor](../../aspose.psd/region/xor/#xor_3)(Region) | Werkt dit bij`Region` naar de unie minus het snijpunt van zichzelf met het gespecificeerde`Region` . |

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


