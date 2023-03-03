---
title: Class Font
second_title: Aspose.PSD per riferimento API .NET
description: Aspose.PSD.Font classe. Definisce un particolare formato per il testo inclusi caratteri dimensioni e attributi di stile. Questa classe non può essere ereditata.
type: docs
weight: 4280
url: /it/net/aspose.psd/font/
---
## Font class

Definisce un particolare formato per il testo, inclusi caratteri, dimensioni e attributi di stile. Questa classe non può essere ereditata.

```csharp
public sealed class Font
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Font](font/#constructor)(Font, FontStyle) | Inizializza un nuovo`Font` che utilizza l'esistente specificato`Font` E[`FontStyle`](../fontstyle/) enumerazione. |
| [Font](font/#constructor_1)(string, float) | Inizializza un nuovo`Font` utilizzando una dimensione specificata. Il set di caratteri è impostato suDefault , l'unità grafica aPoint , lo stile del carattere aRegular . |
| [Font](font/#constructor_2)(string, float, FontStyle) | Inizializza un nuovo`Font` utilizzando una dimensione e uno stile specificati. Il set di caratteri è impostato suDefault , l'unità grafica aPoint . |
| [Font](font/#constructor_5)(string, float, GraphicsUnit) | Inizializza un nuovo`Font` utilizzando una dimensione e un'unità specificate. Il set di caratteri è impostato suDefault lo stile è impostato suRegular . |
| [Font](font/#constructor_3)(string, float, FontStyle, GraphicsUnit) | Inizializza un nuovo`Font` utilizzando una dimensione, uno stile e un'unità specificati. |
| [Font](font/#constructor_4)(string, float, FontStyle, GraphicsUnit, CharacterSet) | Inizializza un nuovo`Font` utilizzando una dimensione, uno stile, un'unità e un set di caratteri specificati. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Bold](../../aspose.psd/font/bold/) { get; } | Ottiene un valore che indica se this`Font` è in grassetto. |
| [CharacterSet](../../aspose.psd/font/characterset/) { get; } | Ottiene un valore in byte che specifica il set di caratteri che this`Font` usa. |
| [Italic](../../aspose.psd/font/italic/) { get; } | Ottiene un valore che indica se this`Font`è in corsivo. |
| [Name](../../aspose.psd/font/name/) { get; } | Ottiene il nome del volto di this`Font` . |
| [Size](../../aspose.psd/font/size/) { get; } | Ottiene la dimensione em di questo`Font` misurato nelle unità specificate dal[`Unit`](./unit/) proprietà. |
| [Strikeout](../../aspose.psd/font/strikeout/) { get; } | Ottiene un valore che indica se this`Font` specifica una linea orizzontale attraverso il font. |
| [Style](../../aspose.psd/font/style/) { get; } | Ottiene informazioni sullo stile per questo`Font` . |
| [Underline](../../aspose.psd/font/underline/) { get; } | Ottiene un valore che indica se this`Font` è sottolineato. |
| [Unit](../../aspose.psd/font/unit/) { get; } | Ottiene l'unità di misura per questo`Font` . |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [DeepClone](../../aspose.psd/font/deepclone/)() | Crea una copia profonda esatta di questo`Font` . |
| override [Equals](../../aspose.psd/font/equals/)(object) | Indica se l'oggetto specificato è a`Font` e ha gli stessi valori di proprietà di this`Font` . |
| override [GetHashCode](../../aspose.psd/font/gethashcode/)() | Ottiene il codice hash per questo`Font` . |
| override [ToString](../../aspose.psd/font/tostring/)() | Restituisce una rappresentazione di stringa leggibile dall'uomo di this`Font` . |

### Esempi

Questo esempio dimostra l'uso della classe Font e SolidBrush per disegnare stringhe sulla superficie dell'immagine. L'esempio crea una nuova immagine Image e disegna forme usando Figures e GraphicsPath

```csharp
[C#]

//Crea un'istanza di Image
using (Aspose.PSD.Image image = new Aspose.PSD.FileFormats.Psd.PsdImage(500, 500))
{
    //Crea e inizializza un'istanza della classe Graphics
    Aspose.PSD.Graphics graphics = new Aspose.PSD.Graphics(image);

    //Cancella la superficie grafica
    graphics.Clear(Color.Wheat);

    //Crea un'istanza di Font
    Aspose.PSD.Font font = new Aspose.PSD.Font("Times New Roman", 16);

    //Crea un'istanza di SolidBrush con colore rosso
    Aspose.PSD.Brushes.SolidBrush brush = new Aspose.PSD.Brushes.SolidBrush(Color.Red);

    // Disegna una stringa
    graphics.DrawString("Created by Aspose.PSD for .Net", font, brush, new PointF(100, 100));

    // crea opzioni di esportazione.
    Aspose.PSD.ImageOptions.GifOptions options = new Aspose.PSD.ImageOptions.GifOptions();

    // salva tutte le modifiche
    image.Save("C:\\temp\\output.gif", options);
}
```

### Guarda anche

* spazio dei nomi [Aspose.PSD](../../aspose.psd/)
* assemblea [Aspose.PSD](../../)


