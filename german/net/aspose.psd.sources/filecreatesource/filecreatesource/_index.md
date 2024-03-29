---
title: FileCreateSource.FileCreateSource
second_title: Aspose.PSD für .NET-API-Referenz
description: FileCreateSource constructeur. Initialisiert eine neue Instanz vonFileCreateSource Klasse.
type: docs
weight: 10
url: /de/net/aspose.psd.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

Initialisiert eine neue Instanz von[`FileCreateSource`](../) Klasse.

```csharp
public FileCreateSource(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der zu erstellende Dateipfad. |

### Beispiele

Dieses Beispiel erstellt eine neue Image-Datei an einem Speicherort auf dem Datenträger, wie von der Source-Eigenschaft der BmpOptions-Instanz angegeben. Wenn der zweite Parameter nicht an den Konstruktor von FileCreateSource übergeben wird, hat die zu erstellende Datei standardmäßig die Eigenschaft IsTemporal auf True gesetzt. Wenn IsTemporal auf True gesetzt ist, wird am Ende der Ausführung keine Datei auf der Festplatte gespeichert.

```csharp
[C#]

string path = "C:\\temp\\image.psd";
    
//Erzeugt eine Instanz von PsdOptions und legt ihre verschiedenen Eigenschaften fest
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Eine Instanz von FileCreateSource erstellen und als Quelle für die Instanz von PsdOptions zuweisen
//Wenn der zweite Parameter nicht übergeben wird, ist IsTemporal für die Datei standardmäßig auf True gesetzt
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Erzeugt eine Instanz von Image 
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // Bildverarbeitung durchführen
}
```

### Siehe auch

* class [FileCreateSource](../)
* namensraum [Aspose.PSD.Sources](../../filecreatesource/)
* Montage [Aspose.PSD](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Initialisiert eine neue Instanz von[`FileCreateSource`](../) Klasse.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der zu erstellende Dateipfad. |
| isTemporal | Boolean | Wenn eingestellt`WAHR` Die erstellte Datei ist zeitlich. |

### Beispiele

In diesem Beispiel wird eine neue Bilddatei an einem Speicherort auf dem Datenträger erstellt, wie durch die Source-Eigenschaft der PsdOptions-Instanz angegeben. Mehrere Eigenschaften für die PsdOptions-Instanz werden festgelegt, bevor das eigentliche Bild erstellt wird. Insbesondere die Source-Eigenschaft, die sich in diesem Fall auf den tatsächlichen Speicherort der Festplatte bezieht.

```csharp
[C#]

//Eine Instanz von PsdOptions erstellen und ihre verschiedenen Eigenschaften festlegen
Aspose.PSD.ImageOptions.PsdOptions psdOptions = new Aspose.PSD.ImageOptions.PsdOptions();

//Eine Instanz von FileCreateSource erstellen und als Quelle für die Instanz von PsdOptions zuweisen
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei Temporär ist oder nicht
psdOptions.Source = new Aspose.PSD.Sources.FileCreateSource(@"C:\temp\sample.psd", false);

// Erstellen Sie eine Instanz von Image und initialisieren Sie sie mit einer Instanz von PsdOptions, indem Sie die Create-Methode aufrufen
using (Aspose.PSD.Image image = Aspose.PSD.Image.Create(psdOptions, 500, 500))
{
    // Bildverarbeitung durchführen

    // Alle Änderungen speichern
    image.Save();
}
```

### Siehe auch

* class [FileCreateSource](../)
* namensraum [Aspose.PSD.Sources](../../filecreatesource/)
* Montage [Aspose.PSD](../../../)


