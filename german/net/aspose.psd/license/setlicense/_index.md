---
title: License.SetLicense
second_title: Aspose.PSD für .NET-API-Referenz
description: License methode. Lizenziert die Komponente.
type: docs
weight: 20
url: /de/net/aspose.psd/license/setlicense/
---
## SetLicense(string) {#setlicense_1}

Lizenziert die Komponente.

```csharp
public void SetLicense(string licenseName)
```

### Bemerkungen

Versucht, die Lizenz an den folgenden Orten zu finden:

1. Explizite Pfad.

2. Der Ordner, der die Aspose-Komponentenbaugruppe enthält.

3. Der Ordner, der die aufrufende Assembly des Clients enthält.

4. Der Ordner, der den Eintrag (Startup) Assembly enthält.

5. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

**Notiz:**Versucht in .NET Compact Framework, die Lizenz nur an diesen Speicherorten zu finden:

1. Explizite Pfad.

2. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

### Beispiele

In diesem Beispiel wird versucht, eine Lizenzdatei mit dem Namen MyLicense.lic in dem Ordner zu finden, der die Komponente enthält, in dem Ordner, der die aufrufende Assembly enthält, im Ordner des Eintrags Assembly und dann in die eingebetteten Ressourcen der aufrufenden Assembly. Kann ein vollständiger oder kurzer Dateiname oder Name einer eingebetteten Ressource sein. Verwenden Sie eine leere Zeichenfolge, um in den Evaluierungsmodus zu wechseln.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

### Siehe auch

* class [License](../)
* namensraum [Aspose.PSD](../../license/)
* Montage [Aspose.PSD](../../../)

---

## SetLicense(Stream) {#setlicense}

Lizenziert die Komponente.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Ein Stream, der die Lizenz enthält. |

### Bemerkungen

Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden.

### Beispiele

```csharp
[C#]

License license = new License();
license.SetLicense(myStream);


[Visual Basic]

Dim license as License = new License
license.SetLicense(myStream)
```

### Siehe auch

* class [License](../)
* namensraum [Aspose.PSD](../../license/)
* Montage [Aspose.PSD](../../../)


