---
title: Class Matrix
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.Matrix klass. Ersätter GDImatrisen.
type: docs
weight: 5090
url: /sv/net/aspose.psd/matrix/
---
## Matrix class

Ersätter GDI+-matrisen.

```csharp
public class Matrix
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [Matrix](matrix/#constructor)() | Initierar en ny instans av Matrix-klassen som identitetsmatris. |
| [Matrix](matrix/#constructor_1)(Matrix) | Gör en kopia av`Matrix` class. |
| [Matrix](matrix/#constructor_2)(Rectangle, Point[]) | Initierar en ny instans av`Matrix` klass till den geometriska transformationen som definieras av den specificerade rektangeln och matrisen av punkter. |
| [Matrix](matrix/#constructor_3)(RectangleF, PointF[]) | Initierar en ny instans av`Matrix` klass till den geometriska transformationen som definieras av den specificerade rektangeln och matrisen av punkter. |
| [Matrix](matrix/#constructor_4)(float, float, float, float, float, float) | Initierar en ny instans av`Matrix` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Elements](../../aspose.psd/matrix/elements/) { get; } | Får en matris med flyttalsvärden som representerar elementen i detta`Matrix` . |
| [M11](../../aspose.psd/matrix/m11/) { get; } | Hämtar matriselementet vid första radens första kolumn. Representerar skala längs X-axeln. |
| [M12](../../aspose.psd/matrix/m12/) { get; } | Hämtar matriselementet vid första radens andra kolumn. Representerar skjuvning längs Y-axeln. |
| [M21](../../aspose.psd/matrix/m21/) { get; } | Hämtar matriselementet vid andra radens första kolumn. Representerar skjuvning längs X-axeln. |
| [M22](../../aspose.psd/matrix/m22/) { get; } | Hämtar matriselementet vid andra radens andra kolumn. Representerar skala längs Y-axeln. |
| [M31](../../aspose.psd/matrix/m31/) { get; } | Hämtar matriselementet vid tredje radens första kolumn. Representerar översättning längs X-axeln. |
| [M32](../../aspose.psd/matrix/m32/) { get; } | Hämtar matriselementet vid tredje radens första kolumn. Representerar översättning längs Y-axeln. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Equals](../../aspose.psd/matrix/equals/)(object) | Bestämmer om den angivnaObject är lika med denna instans. |
| [GetElements](../../aspose.psd/matrix/getelements/)() | Hämtar kopian av matriselement. |
| override [GetHashCode](../../aspose.psd/matrix/gethashcode/)() | Returnerar en hash-kod för denna instans. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply)(Matrix) | Multiplicerar denna matris med matrisen som anges i matrisparametern med hjälp av (standard) Prepend order. |
| [Multiply](../../aspose.psd/matrix/multiply/#multiply_1)(Matrix, MatrixOrder) | Multiplicerar denna matris med matrisen som anges i matrisparametern och i den ordning som anges i orderparametern. |
| [Reset](../../aspose.psd/matrix/reset/)() | Återställer denna matris för att ha elementen i identitetsmatrisen. |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate)(float) | Tillämpar en medurs rotation av en mängd som anges i vinkelparametern, runt origo (noll x- och y-koordinater) för denna matris i standardordningen (Prepend). |
| [Rotate](../../aspose.psd/matrix/rotate/#rotate_1)(float, MatrixOrder) | Tillämpar en medurs rotation av en mängd som anges i vinkelparametern, runt origo (noll x- och y-koordinater) för denna matris i angiven ordning. |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat)(float, PointF) | Tillämpar en medurs rotation kring den angivna punkten på denna matris i standardordningen (Prepend). |
| [RotateAt](../../aspose.psd/matrix/rotateat/#rotateat_1)(float, PointF, MatrixOrder) | Tillämpar en medurs rotation kring den angivna punkten på denna matris i angiven ordning. |
| [Scale](../../aspose.psd/matrix/scale/#scale)(float, float) | Tillämpar den angivna skalvektorn (scaleX och scaleY) på denna matris med hjälp av (standard) Prepend order. |
| [Scale](../../aspose.psd/matrix/scale/#scale_1)(float, float, MatrixOrder) | Tillämpar den angivna skalvektorn (scaleX och scaleY) på detta`Matrix` med den angivna ordningen. |
| override [ToString](../../aspose.psd/matrix/tostring/)() | Returnerar enString som representerar denna instans. |
| [TransformPoints](../../aspose.psd/matrix/transformpoints/)(PointF[]) | Tillämpar den geometriska transformationen som representeras av detta`Matrix` till en specificerad uppsättning punkter. |
| [Translate](../../aspose.psd/matrix/translate/#translate)(float, float) | Tillämpar den angivna översättningsvektorn på detta`Matrix` använder (standard) Prepend order. |
| [Translate](../../aspose.psd/matrix/translate/#translate_1)(float, float, MatrixOrder) | Tillämpar den angivna översättningsvektorn på denna matris i angiven ordning. |
| static [Equals](../../aspose.psd/matrix/equals/)(Matrix, Matrix) | Bestämmer om två matriser är lika. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [TypeFlip](../../aspose.psd/matrix/typeflip/) | Denna flaggbit indikerar att omvandlingen som definieras av detta objekt utför en spegelvändning kring någon axel som ändrar normalt högerhänt koordinatsystem till ett vänsterhänt förutom omvandlingarna som indikeras av andra flaggbitar. Ett högerhänt koordinatsystem är en där den positiva X -axeln roterar moturs för att överlägga den positiva Y-axeln liknande riktningen som fingrarna på din högra hand kröker sig när du stirrar på tummen. Ett vänsterhänt koordinatsystem är ett där det positiva X_x000 roterar medurs för att överlägga den positiva Y-axeln similar i den riktning som fingrarna på din vänstra hand kröker sig. Det finns inget matematiskt sätt att bestämma vinkeln för den ursprungliga vändnings- eller speglingstransformationen eftersom alla vinklar av vändningen är identiska med en lämplig justeringsrotation. OBS: TypeFlip lades till efter GENERAL_TRANSFORM var i public cirkulation och flaggbitarna kunde inte längre bekvämt numreras om utan att introducera binär inkompatibilitet i outside kod. |
| const [TypeGeneralRotation](../../aspose.psd/matrix/typegeneralrotation/) | Denna flaggbit indikerar att transformationen som definieras av detta objekt utför en rotation med en godtycklig vinkel utöver de omvandlingarna som indikeras av andra flaggbitar. En rotation ändrar vinklarna för vektorerna med samma mängd i vektorns riktning oavsett den ursprungliga riktningen och utan att ändra längden på vektorn. Denna flaggbit är ömsesidigt uteslutande med the |
| const [TypeGeneralScale](../../aspose.psd/matrix/typegeneralscale/) | En generell skala multiplicerar längden på vektorer med olika mängder i x- och y-riktningarna utan att ändra vinkeln mellan vinkelräta vektorer. Denna flaggbit är ömsesidigt uteslutande med flaggan TypeUniformScale. |
| const [TypeGeneralTransform](../../aspose.psd/matrix/typegeneraltransform/) | Denna konstant indikerar att transformationen som definieras av detta objekt utför en godtycklig omvandling av de ingående koordinaterna. Om denna transformation kan klassificeras av någon av ovanstående konstanter, kommer typen antingen att vara konstant TypeIdentity eller a kombination av lämplig flagga bitar för de olika koordinat -omvandlingarna som denna transformation utför. |
| const [TypeIdentity](../../aspose.psd/matrix/typeidentity/) | En identitetstransform är en där utgångskoordinaterna är alltid desamma som ingångskoordinaterna. Om denna transformation är något annat än identitetstransformen, kommer typen antingen att vara den konstanta GENERAL_TRANSFORM eller a kombinationen av lämpliga flaggbitar för de olika koordinat omvandlingarna som denna transformation utför. |
| const [TypeMaskRotation](../../aspose.psd/matrix/typemaskrotation/) | Denna konstant är en bitmask för någon av rotationsflaggans bitar. |
| const [TypeMaskScale](../../aspose.psd/matrix/typemaskscale/) | Denna konstant är en bitmask för vilken som helst av skalflaggbitarna. |
| const [TypeQuadrantRotation](../../aspose.psd/matrix/typequadrantrotation/) | Denna flaggbit indikerar att transformationen som definieras av detta objekt utför en kvadrantrotation med någon multipel av 90 grader in tillägg till de omvandlingar som indikeras av andra flaggbitar. En rotation ändrar vinklarna för vektorer med samma mängd oavsett originalriktningen_ av vektorn och utan att ändra längden på vektorn. Denna flaggbit är ömsesidigt uteslutande med flaggan TypeGeneralRotation. |
| const [TypeTranslation](../../aspose.psd/matrix/typetranslation/) | En översättning flyttar koordinaterna med en konstant mängd i x och y utan att ändra längden eller vinkeln på vektorerna. |
| const [TypeUniformScale](../../aspose.psd/matrix/typeuniformscale/) | En enhetlig skala multiplicerar längden på vektorer med samma mängd i både x- och y-riktningarna utan att ändra vinkeln mellan vektorer. Denna flaggbit är ömsesidigt uteslutande med flaggan TypeGeneralScale. |

### Anmärkningar

De flesta algoritmer hämtade från Suns AffineTransform.java. Javas namn för matriselement som används internt. Karta över java-namn till .net ettor till beskrivning: m00 M11 Skala X mx2 Scale She m10 M10 M10 M10 M10 M10 M10 M10 M10 M10 M10 M10 M10 M10 M10 M10 M2 Översätt X m12 M32 Översätt Y

### Se även

* namnutrymme [Aspose.PSD](../../aspose.psd/)
* hopsättning [Aspose.PSD](../../)


