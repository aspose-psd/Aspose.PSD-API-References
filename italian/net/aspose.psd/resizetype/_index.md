---
title: Enum ResizeType
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.ResizeType enum. Specifica il tipo di ridimensionamento.
type: docs
weight: 5370
url: /it/net/aspose.psd/resizetype/
---
## ResizeType enumeration

Specifica il tipo di ridimensionamento.

```csharp
public enum ResizeType
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| None | `0` | I pixel non vengono conservati durante l'operazione di ridimensionamento. |
| LeftTopToLeftTop | `1` | Il punto superiore sinistro della nuova immagine coinciderà con il punto superiore sinistro dell'immagine originale. Il ritaglio verrà eseguito se necessario. |
| RightTopToRightTop | `2` | Il punto in alto a destra della nuova immagine coinciderà con il punto in alto a destra dell'immagine originale. Il ritaglio verrà eseguito se necessario. |
| RightBottomToRightBottom | `3` | Il punto in basso a destra della nuova immagine coinciderà con il punto in basso a destra dell'immagine originale. Il ritaglio verrà eseguito se necessario. |
| LeftBottomToLeftBottom | `4` | Il punto inferiore sinistro della nuova immagine coinciderà con il punto inferiore sinistro dell'immagine originale. Il ritaglio verrà eseguito se necessario. |
| CenterToCenter | `5` | Il centro della nuova immagine coinciderà con il centro dell'immagine originale. Il ritaglio verrà eseguito se necessario. |
| LanczosResample | `6` | Ricampiona usando l'algoritmo lanczos con a=3. |
| NearestNeighbourResample | `7` | Ricampiona utilizzando l'algoritmo del vicino più vicino. |
| AdaptiveResample | `8` | Ricampionamento utilizzando algoritmi adattivi basati su funzioni razionali pesate e miste e algoritmi di interpolazione lanczos3. |
| BilinearResample | `9` | Ricampiona usando l'interpolazione bilineare. Il pre-filtraggio dell'immagine è consentito per rimuovere il rumore prima del ricampionamento, quando necessario |
| HighQualityResample | `10` | Il resample di alta qualità |
| CatmullRom | `11` | Il metodo di interpolazione cubica Catmull-Rom. |
| CubicConvolution | `12` | Il metodo di interpolazione della convoluzione cubica |
| CubicBSpline | `13` | Il metodo di interpolazione cubica CubicBSpline |
| Mitchell | `14` | Il metodo di interpolazione cubica di Mitchell |
| SinC | `15` | Il metodo di interpolazione cubica Sinc (Lanczos3) |
| Bell | `16` | Il metodo di interpolazione di Bell |

### Esempi

Il codice seguente mostra come ridimensionare un'immagine con un nuovo tipo di ridimensionamento SinC.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerSinCStripes_after.psd";

// Carica un'immagine esistente in un'istanza della classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.SinC);
    image.Save(destName, new PsdOptions(image));
}
```

Il codice seguente mostra come ridimensionare un'immagine con un nuovo tipo di ridimensionamento Bell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerBellStripes_after.psd";

// Carica un'immagine esistente in un'istanza della classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Bell);
    image.Save(destName, new PsdOptions(image));
}
```

Il codice seguente illustra come ridimensionare un'immagine con un nuovo tipo di ridimensionamento Mitchell.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerMitchellStripes_after.psd";

// Carica un'immagine esistente in un'istanza della classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.Mitchell);
    image.Save(destName, new PsdOptions(image));
}
```

Il codice seguente mostra come ridimensionare un'immagine con un nuovo tipo di ridimensionamento CatmullRom.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCatmullRomStripes_after.psd";

// Carica un'immagine esistente in un'istanza della classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CatmullRom);
    image.Save(destName, new PsdOptions(image));
}
```

Il codice seguente mostra come ridimensionare un'immagine con un nuovo tipo di ridimensionamento CubicBSpline.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicBSplineStripes_after.psd";

// Carica un'immagine esistente in un'istanza della classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicBSpline);
    image.Save(destName, new PsdOptions(image));
}
```

Il codice seguente illustra come ridimensionare un'immagine con un nuovo tipo di ridimensionamento CubicConvolution.

```csharp
[C#]

string sourceFile = "sample.psd";
string destName = "ResamplerCubicConvolutionStripes_after.psd";

// Carica un'immagine esistente in un'istanza della classe PsdImage
using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    image.Resize(300, 300, ResizeType.CubicConvolution);
    image.Save(destName, new PsdOptions(image));
}
```

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


