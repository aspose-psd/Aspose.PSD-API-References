---
title: "FileCreateSource.FileCreateSource"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "FileCreateSource-Konstruktor. Initialisiert eine neue Instanz der FileCreateSource-Klasse"
type: docs
weight: 10
url: /de/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
{{< psd/tize >}}
## FileCreateSource(string) {#constructor}

Initialisiert eine neue Instanz der [`FileCreateSource`](../)-Klasse.

```csharp
public FileCreateSource(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zum Erstellen. |

## Beispiele

Dieses Beispiel erstellt eine neue Bilddatei an einem beliebigen Speicherort, wie durch die Source‑Eigenschaft der BmpOptions‑Instanz angegeben. Wenn dem Konstruktor von FileCreateSource kein zweiter Parameter übergeben wird, hat die zu erstellende Datei standardmäßig die Eigenschaft IsTemporal auf True gesetzt. Ist IsTemporal auf True gesetzt, wird am Ende der Ausführung keine Datei auf dem Datenträger gespeichert.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//Erstellt eine Instanz von PsdOptions und setzt deren verschiedene Eigenschaften.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Source für die Instanz von PsdOptions zu.
//Wird kein zweiter Parameter übergeben, hat die Datei standardmäßig IsTemporal auf True gesetzt.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Erstellt eine Instanz von Image 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Führe einige Bildverarbeitungen durch
}
```

### Siehe auch

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Initialisiert eine neue Instanz der [`FileCreateSource`](../)-Klasse.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad zum Erstellen. |
| isTemporal | Boolean | Wenn auf `true` gesetzt, wird die erstellte Datei temporär sein. |

## Beispiele

Dieses Beispiel erstellt eine neue Bilddatei an einem Speicherort, der durch die Source‑Eigenschaft der PsdOptions‑Instanz angegeben ist. Mehrere Eigenschaften der PsdOptions‑Instanz werden gesetzt, bevor das eigentliche Bild erstellt wird. Insbesondere die Source‑Eigenschaft, die in diesem Fall auf den tatsächlichen Speicherort verweist.

```csharp
[C#]

//Erstellen Sie eine Instanz von PsdOptions und setzen Sie deren verschiedene Eigenschaften.
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Source für die Instanz von PsdOptions zu.
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei temporär ist oder nicht.
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

//Erstellen Sie eine Instanz von Image und initialisieren Sie sie mit einer Instanz von PsdOptions, indem Sie die Create‑Methode aufrufen.
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    //Führe einige Bildverarbeitungen durch

    // Alle Änderungen speichern
    image.Save();
}
```

### Siehe auch

* class [FileCreateSource](../)
* namespace [Aspose.PSD.Sources](../../../aspose.psd.sources/)
* assembly [Aspose.PSD](../../../)


