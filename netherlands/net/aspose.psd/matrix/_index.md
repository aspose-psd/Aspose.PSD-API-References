---
title: Class Matrix
second_title: Aspose.PSD voor .NET API-referentie
description: Aspose.PSD.Matrix klas. Vervangt de GDI Matrix.
type: docs
weight: 5090
url: /nl/net/aspose.psd/matrix/
---
## Matrix class

Vervangt de GDI+ Matrix.

```csharp
public class Matrix
```

## Constructeurs

| Naam | Beschrijving |
| --- | --- |
| [Matrix](matrix/#constructor)() | Initialiseert een nieuwe instantie van de klasse Matrix als identiteitsmatrix. |
| [Matrix](matrix/#constructor_1)(Matrix) | Maakt een kopie van het`Matrix` klasse. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | Initialiseert een nieuw exemplaar van het`Matrix` class naar de geometrische transformatie gedefinieerd door de opgegeven rechthoek en reeks punten. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | Initialiseert een nieuw exemplaar van het`Matrix` class naar de geometrische transformatie gedefinieerd door de opgegeven rechthoek en reeks punten. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | Initialiseert een nieuw exemplaar van het`Matrix` klasse. |

## Eigenschappen

| Naam | Beschrijving |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | Krijgt een array van drijvende-kommawaarden die de elementen hiervan vertegenwoordigen`Matrix` . |
| [M11](../../aspose.psd/matrix/m11/) { get; } | Krijgt het matrixelement op de eerste rij eerste kolom. Vertegenwoordigt schaal langs X-as. |
| [M12](../../aspose.psd/matrix/m12/) { get; } | Haalt het matrixelement op in de eerste rij tweede kolom. Vertegenwoordigt afschuiving langs de Y-as. |
| [M21](../../aspose.psd/matrix/m21/) { get; } | Krijgt het matrixelement op de tweede rij eerste kolom. Vertegenwoordigt afschuiving langs X-as. |
| [M22](../../aspose.psd/matrix/m22/) { get; } | Haalt het matrixelement op in de tweede rij tweede kolom. Vertegenwoordigt schaal langs de Y-as. |
| [M31](../../aspose.psd/matrix/m31/) { get; } | Krijgt het matrixelement op de derde rij eerste kolom. Vertegenwoordigt vertaling langs X-as. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | Krijgt het matrixelement op de derde rij eerste kolom. Vertegenwoordigt vertaling langs Y-as. |

## methoden

| Naam | Beschrijving |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | Bepaalt of de opgegevenObject is gelijk aan deze instantie. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | Haalt de kopie van matrixelementen op. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | Retourneert een hash-code voor deze instantie. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | Vermenigvuldigt deze matrix met de matrix die is opgegeven in de matrixparameter met behulp van (standaard) Prepend-volgorde. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | Vermenigvuldigt deze matrix met de matrix die is opgegeven in de matrixparameter en in de volgorde die is opgegeven in de volgordeparameter. |
| [Reset](../../aspose.psd/matrix/reset/)() | Reset deze matrix om de elementen van de identiteitsmatrix te hebben. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | Past een rechtsom draaien toe van een hoeveelheid gespecificeerd in de hoekparameter, rond de oorsprong (nul x- en y-coördinaten) voor deze Matrix in de standaard (Prepend) volgorde. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | Past een rechtsom draaien toe van een hoeveelheid gespecificeerd in de hoekparameter, rond de oorsprong (nul x- en y-coördinaten) voor deze Matrix in de gespecificeerde volgorde. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | Past een rotatie met de klok mee rond het gespecificeerde punt toe op deze Matrix in de standaard (Prepend) volgorde. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | Past een rotatie met de klok mee rond het gespecificeerde punt toe op deze Matrix in de gespecificeerde volgorde. |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | Past de opgegeven schaalvector (scaleX en scaleY) toe op deze matrix met behulp van (standaard) Prepend-volgorde. |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | Past de gespecificeerde schaalvector (scaleX en scaleY) hierop toe`Matrix` met behulp van de opgegeven volgorde. |
| override [ToString](../../aspose.psd/matrix/tostring/)() | Geeft als resultaat eenString die deze instantie vertegenwoordigt. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | Past de geometrische transformatie toe die hierdoor wordt weergegeven`Matrix` naar een gespecificeerde reeks punten. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | Past de gespecificeerde translatievector hierop toe`Matrix` met behulp van (standaard) Prepend order. |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | Past de opgegeven translatievector toe op deze matrix in de opgegeven volgorde. |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | Bepaalt of twee matrices gelijk zijn. |

## Velden

| Naam | Beschrijving |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | Dit vlagbit geeft aan dat de transformatie gedefinieerd door dit object een spiegelbeeldomkering uitvoert rond een as die het normaal rechtshandige coördinatensysteem verandert in een linkshandig systeem naast de conversies aangegeven door andere vlagbits. Een rechtshandig coördinatensysteem is er een waarbij de positieve X -as tegen de klok in draait om de positieve Y-as te bedekken vergelijkbaar met de richting waarin de vingers aan uw rechterhand krullen wanneer u naar uw duim staart. Een linkshandig coördinatensysteem is er een waarbij de positieve X -as roteert met de klok mee om de positieve Y-as te bedekken vergelijkbaar met de richting waarin de vingers aan uw linkerhand krullen. Er is geen wiskundige manier om de hoek van de oorspronkelijke omdraaiende of spiegelende transformatie te bepalen, aangezien alle hoeken van omdraaien identiek zijn, gegeven een geschikte aanpassingsrotatie. OPMERKING: TypeFlip is toegevoegd na GENERAL_TRANSFORM was in public circulatie en de vlagbits konden niet langer handig hernummerd worden zonder binaire incompatibiliteit te introduceren in outside code. |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | Deze vlagbit geeft aan dat de transformatie gedefinieerd door dit object een rotatie uitvoert over een willekeurige hoek naast de conversies aangegeven door andere vlagbits. Een rotatie verandert de hoeken van vectoren met dezelfde hoeveelheid ongeacht de oorspronkelijke richting van de vector en zonder de lengte van de vector te veranderen. Deze vlagbit sluit elkaar wederzijds uit met de |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | Een algemene schaal vermenigvuldigt de lengte van vectoren met verschillende hoeveelheden in de x- en y-richting zonder de hoek tussen loodrechte vectoren te veranderen. Deze vlagbit sluit elkaar uit met de TypeUniformScale-vlag. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | Deze constante geeft aan dat de transformatie gedefinieerd door dit object een willekeurige conversie uitvoert van de ingevoerde coördinaten. Als deze transformatie kan worden geclassificeerd door een van de bovenstaande constanten, is het type ofwel de constante TypeIdentity of een combinatie van de juiste vlag bits voor de verschillende coordinate conversies die deze transformatie uitvoert. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | Een identiteitstransformatie is er een waarin de uitvoercoördinaten altijd hetzelfde zijn als de invoercoördinaten. Als deze transformatie iets anders is dan de identiteitstransformatie, zal het type ofwel de constante GENERAL_TRANSFORM zijn of een combinatie van de juiste vlagbits voor de verschillende coordinaten conversies die deze transformatie uitvoert. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | Deze constante is een bitmasker voor elk van de rotatievlagbits. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | Deze constante is een bitmasker voor elk van de schaalvlagbits. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | Deze vlagbit geeft aan dat de transformatie gedefinieerd door dit object een kwadrantrotatie uitvoert met een veelvoud van 90 graden in naast de conversies aangegeven door andere vlagbits. Een rotatie verandert de hoeken van vectoren met dezelfde hoeveelheid ongeacht de oorspronkelijke richting van de vector en zonder de lengte van de vector te veranderen. Deze vlagbit sluit elkaar uit met de vlag TypeGeneralRotation. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | Een translatie verplaatst de coördinaten met een constante hoeveelheid in x en y zonder de lengte of hoek van vectoren te veranderen. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | Een uniforme schaal vermenigvuldigt de lengte van vectoren met dezelfde hoeveelheid in zowel de x- als de y-richting zonder de hoek tussen vectoren te veranderen. Deze vlagbit sluit elkaar uit met de vlag TypeGeneralScale. |

### Opmerkingen

De meeste algoritmen zijn overgenomen van Sun's AffineTransform.java. Java's namen voor matrixelementen die intern worden gebruikt. Kaart van Java-namen naar .net-namen naar beschrijving: m00 M11 Schaal X m10 M12 Schuintrekken Y m01 M21 Schuintrekken X m11 M20 Schaal Yȍ1 m01 M21 Schuintrekken X m11 M20_1 Vertalen X m12 M32 Vertalen Y

### Zie ook

* naamruimte [Aspose.PSD](../../aspose.psd/)
* montage [Aspose.PSD](../../)


