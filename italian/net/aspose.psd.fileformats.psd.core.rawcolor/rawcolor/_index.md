---
title: "Classe RawColor"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Aspose.PSD.FileFormats.Psd.Core.RawColor.RawColor classe. La classe Raw Color aiuta a memorizzare colori con qualsiasi numero di canali, qualsiasi modalità colore e qualsiasi profondità di bit. Si noti che alcune classi interne possono avere problemi nella conversione di RawColor al suo formato nativo, quindi se l'API fornisce un colore CMYK è più affidabile utilizzare il formato fornito. Inoltre possono esserci alcuni casi in cui Raw Color può essere convertito."
type: docs
weight: 1650
url: /it/net/aspose.psd.fileformats.psd.core.rawcolor/rawcolor/
---
{{< psd/tize >}}
## RawColor class

La classe Raw Color aiuta a memorizzare i colori con qualsiasi numero di canali, qualsiasi modalità colore e qualsiasi profondità di bit. Si prega di notare che alcune classi interne possono avere problemi nella conversione di RawColor nel suo formato nativo, quindi se l'API fornisce un colore CMYK, è più affidabile utilizzare il formato fornito. Inoltre, possono esserci alcuni casi in cui Raw Color può essere convertito.

```csharp
public sealed class RawColor
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [RawColor](rawcolor/#constructor)(ColorComponent[]) | Inizializza una nuova istanza della classe `RawColor`. |
| [RawColor](rawcolor/#constructor_1)(PixelDataFormat, short) | Inizializza una nuova istanza della classe `RawColor` dal formato dei dati pixel utilizzando modalità colore predefinite |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [ColorMode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/colormode/) { get; set; } | Modalità da seguire per il colore. |
| [Components](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/components/) { get; } | Ottiene i componenti del colore. Ogni componente è un canale separato e, se utilizzi uno schema colore non comune, è meglio lavorare con ciascun canale separatamente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/equals/)(object) | Determina se l'Object specificato è uguale a questa istanza. |
| [GetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getasint/)() | Ottiene il colore come int nel caso sia possibile ottenerlo. |
| [GetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getaslong/)() | Ottiene il colore come long nel caso sia possibile ottenerlo. |
| [GetBitDepth](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getbitdepth/)() | Ottiene la profondità di bit del Raw Color. Ad esempio, per un colore ARGB con 8 bit per canale/componente la profondità è 32 bit; per un colore ARGB completo con 16 bit per canale/componente è 64. La profondità di bit è accumulata dalla somma delle profondità di bit dei canali. È possibile se i diversi canali hanno profondità di bit differenti. |
| [GetColorModeName](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/getcolormodename/)() | Ottiene il nome della modalità colore. Il nome della modalità colore è accumulato dai nomi dei canali/componenti. |
| override [GetHashCode](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/gethashcode/)() | Ottiene il codice hash dell'oggetto corrente. |
| [SetAsInt](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setasint/)(int) | Imposta i dati a tutti i canali dall'argomento int se è possibile. |
| [SetAsLong](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/setaslong/)(long) | Imposta i dati a tutti i canali dall'argomento int se è possibile. |
| [operator ==](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_equality/) | Implementa l'operatore ==. |
| [operator !=](../../aspose.psd.fileformats.psd.core.rawcolor/rawcolor/op_inequality/) | Implementa l'operatore !=. |

## Esempi

Il codice seguente dimostra il supporto della classe RawColor al posto della struttura Color obsoleta.

```csharp
[C#]

void AssertAreEqual(object expected, object actual, string message = null)
{
    if (!object.Equals(expected, actual))
    {
        throw new Exception(message ?? "Objects are not equal.");
    }
}

var color = new RawColor(PixelDataFormat.Rgba32Bpp);
var oldColor = Color.FromArgb(5, 1, 2, 3);

var argbValue = oldColor.ToArgb();
color.SetAsInt(argbValue);

AssertAreEqual("ARGB", color.GetColorModeName());
AssertAreEqual(32, color.GetBitDepth());
AssertAreEqual("A Alpha", color.Components[0].FullName);
AssertAreEqual(5, (int)color.Components[0].Value);
AssertAreEqual("R Red", color.Components[1].FullName);
AssertAreEqual(1, (int)color.Components[1].Value);
AssertAreEqual("G Green", color.Components[2].FullName);
AssertAreEqual(2, (int)color.Components[2].Value);
AssertAreEqual("B Blue", color.Components[3].FullName);
AssertAreEqual(3, (int)color.Components[3].Value);

AssertAreEqual(argbValue, color.GetAsInt());
```

### Vedi anche

* namespace [Aspose.PSD.FileFormats.Psd.Core.RawColor](../../aspose.psd.fileformats.psd.core.rawcolor/)
* assembly [Aspose.PSD](../../)


