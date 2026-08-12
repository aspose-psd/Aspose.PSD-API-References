---
title: "Klass Matrix"
second_title: "Aspose.PSD för .NET API‑referens"
description: "Aspose.PSD.Matrix-klass. Ersätter GDI Matrix."
type: docs
weight: 5580
url: /sv/net/aspose.psd/matrix/
---
{{< psd/tize >}}
## Matrix class

Ersätter GDI+‑matrisen.

```csharp
public class Matrix
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [Matrix](matrix/#constructor)() | Initierar en ny instans av Matrix-klassen som identitetsmatris. |
| [Matrix](matrix/#constructor_1)(Matrix) | Skapar en kopia av `Matrix`-klassen. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | Initierar en ny instans av `Matrix`-klassen till den geometriska transformation som definieras av den angivna rektangeln och arrayen av punkter. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | Initierar en ny instans av `Matrix`-klassen till den geometriska transformation som definieras av den angivna rektangeln och arrayen av punkter. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | Initierar en ny instans av `Matrix`-klassen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | Hämtar en array av flyttal som representerar elementen i denna `Matrix`. |
| [M11](../../aspose.psd/matrix/m11/) { get; } | Hämtar matrisens element i första raden första kolumnen. Representerar skalning längs X-axeln. |
| [M12](../../aspose.psd/matrix/m12/) { get; } | Hämtar matrisens element i första raden andra kolumnen. Representerar skevning längs Y-axeln. |
| [M21](../../aspose.psd/matrix/m21/) { get; } | Hämtar matrisens element i andra raden första kolumnen. Representerar skevning längs X-axeln. |
| [M22](../../aspose.psd/matrix/m22/) { get; } | Hämtar matrisens element i andra raden andra kolumnen. Representerar skalning längs Y-axeln. |
| [M31](../../aspose.psd/matrix/m31/) { get; } | Hämtar matrisens element i tredje raden första kolumnen. Representerar translation längs X-axeln. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | Hämtar matrisens element i tredje raden första kolumnen. Representerar translation längs Y-axeln. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | Bestämmer om det angivna objektet är lika med denna instans. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | Hämtar en kopia av matrisens element. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | Returnerar en hashkod för denna instans. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | Multiplicerar denna `Matrix` med matrisen som anges i matrix‑parametern med (standard) Prepend‑ordning. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | Multiplicerar denna `Matrix` med matrisen som anges i matrix‑parametern, och i den ordning som anges i order‑parametern. |
| [Reset](../../aspose.psd/matrix/reset/)() | Återställer denna `Matrix` så att den har elementen i identitetsmatrisen. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | Tillämpar en medursrotation med en mängd som anges i vinkel‑parametern, kring origo (noll‑x‑ och y‑koordinater) för denna `Matrix` i standard‑ (Prepend)‑ordning. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | Tillämpar en medursrotation med en mängd som anges i vinkel‑parametern, kring origo (noll‑x‑ och y‑koordinater) för denna `Matrix` i den angivna ordningen. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | Tillämpar en medursrotation kring den angivna punkten på denna `Matrix` i standard‑ (Prepend)‑ordning. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | Tillämpar en medursrotation kring den angivna punkten på denna `Matrix` i den angivna ordningen. |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | Tillämpar den angivna skalvektorn (scaleX och scaleY) på denna `Matrix` med (standard) Prepend‑ordning. |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | Tillämpar den angivna skalvektorn (scaleX och scaleY) på denna `Matrix` med den angivna ordningen. |
| override [ToString](../../aspose.psd/matrix/tostring/)() | Returnerar en String som representerar detta objekt. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | Tillämpar den geometriska transformen som representeras av denna `Matrix` på en angiven array av punkter. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | Tillämpar den angivna translationsvektorn på denna `Matrix` med (standard) Prepend‑ordning. |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | Tillämpar den angivna translationsvektorn på denna `Matrix` i den angivna ordningen. |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | Bestämmer om två matriser är lika. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | Detta flaggbit indikerar att den transform som definieras av detta objekt utför en spegelvändning kring någon axel, vilket förändrar det normalt högrehandskoordinatsystemet till ett vänsterhandsystem utöver de konverteringar som anges av andra flaggbitar. Ett högrehandskoordinatsystem är ett där den positiva X‑axeln roterar moturs för att överlappa den positiva Y‑axeln, liknande den riktning som fingrarna på din högra hand kröker sig när du tittar rakt på tummen. Ett vänsterhandskoordinatsystem är ett där den positiva X‑axeln roterar medurs för att överlappa den positiva Y‑axeln, liknande den riktning som fingrarna på din vänstra hand kröker sig. Det finns inget matematiskt sätt att bestämma vinkeln för den ursprungliga vändnings- eller speglingstransformen eftersom alla vinkelvärden för vändning är identiska givet en lämplig justerande rotation. OBS: TypeFlip lades till efter att GENERAL_TRANSFORM var i offentlig cirkulation och flaggbitarna kunde inte längre bekvämt omnumreras utan att introducera binär inkompatibilitet i extern kod. |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | Denna flaggbits indikerar att den transformation som definieras av detta objekt utför en rotation med en godtycklig vinkel utöver de konverteringar som anges av andra flaggbitar. En rotation ändrar vektorns vinklar med samma mängd oavsett vektorns ursprungliga riktning och utan att ändra vektorns längd. Denna flaggbits är ömsesidigt uteslutande med den |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | En generell skalning multiplicerar vektorns längd med olika mängder i x- och y-riktningarna utan att ändra vinkeln mellan ortogonala vektorer. Denna flaggbits är ömsesidigt uteslutande med flaggan TypeUniformScale. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | Denna konstant indikerar att den transformation som definieras av detta objekt utför en godtycklig konvertering av inmatningskoordinaterna. Om denna transformation kan klassificeras av någon av ovanstående konstanter kommer typen antingen att vara konstanten TypeIdentity eller en kombination av lämpliga flaggbitar för de olika koordinatkonverteringar som denna transformation utför. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | En identitetstransform är en där utdata-koordinaterna alltid är samma som indata-koordinaterna. Om denna transform är något annat än identitetstransformen kommer typen antingen att vara konstanten GENERAL_TRANSFORM eller en kombination av lämpliga flaggbitar för de olika koordinatkonverteringar som denna transform utför. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | Denna konstant är en bitmask för någon av rotationsflaggbitarna. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | Denna konstant är en bitmask för någon av skalningsflaggbitarna. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | Denna flaggbits indikerar att den transformation som definieras av detta objekt utför en kvadrantrotation med någon multipel av 90 grader utöver de konverteringar som anges av andra flaggbitar. En rotation ändrar vektorns vinklar med samma mängd oavsett vektorns ursprungliga riktning och utan att ändra vektorns längd. Denna flaggbits är ömsesidigt uteslutande med flaggan TypeGeneralRotation. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | En translation flyttar koordinaterna med ett konstant värde i x och y utan att ändra vektorns längd eller vinkel. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | En enhetlig skalning multiplicerar vektorns längd med samma mängd i både x- och y-riktningarna utan att ändra vinkeln mellan vektorer. Denna flaggbits är ömsesidigt uteslutande med flaggan TypeGeneralScale. |

## Anmärkningar

De flesta algoritmerna är hämtade från Suns AffineTransform.java. Javas namn för matriselement som används internt. Karta över java-namn till .net-namn till beskrivning: m00 M11 Skala X m10 M12 Skjuv Y m01 M21 Skjuv X m11 M22 Skala Y m02 M31 Översätt X m12 M32 Översätt Y

### Se även

* namespace [Aspose.PSD](../../aspose.psd/)
* assembly [Aspose.PSD](../../)


