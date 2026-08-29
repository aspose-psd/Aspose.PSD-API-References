---
title: "License.SetLicense"
second_title: "Aspose.PSD für .NET API-Referenz"
description: "License-Methode. Lizenziert die Komponente"
type: docs
weight: 20
url: /de/net/aspose.psd/license/setlicense/
---
{{< psd/tize >}}
## SetLicense(string) {#setlicense_1}

Lizenziert die Komponente.

```csharp
public void SetLicense(string licenseName)
```

## Hinweise

Versucht, die Lizenz an den folgenden Orten zu finden:

1. Expliziter Pfad.

2. Der Ordner, der die Aspose-Komponenten‑Assembly enthält.

3. Der Ordner, der die aufrufende Assembly des Clients enthält.

4. Der Ordner, der die Einstieg‑(Start‑)Assembly enthält.

5. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

**Note:**On the .NET Compact Framework, tries to find the license only in these locations:

1. Expliziter Pfad.

2. Eine eingebettete Ressource in der aufrufenden Assembly des Clients.

## Beispiele

In diesem Beispiel wird versucht, eine Lizenzdatei namens MyLicense.lic im Ordner zu finden, der die Komponente enthält, im Ordner, der die aufrufende Assembly enthält, im Ordner der Einstieg-Assembly und anschließend in den eingebetteten Ressourcen der aufrufenden Assembly.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As License = New License
license.SetLicense("MyLicense.lic")
```

Kann ein vollständiger oder kurzer Dateiname oder der Name einer eingebetteten Ressource sein. Verwenden Sie eine leere Zeichenfolge, um in den Evaluierungsmodus zu wechseln.

### Siehe auch

* class [License](../)
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)

---

## SetLicense(Stream) {#setlicense}

Lizenziert die Komponente.

```csharp
public void SetLicense(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Strom | Stream | Ein Stream, der die Lizenz enthält. |

## Hinweise

Verwenden Sie diese Methode, um eine Lizenz aus einem Stream zu laden.

## Beispiele

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
* namespace [Aspose.PSD](../../../aspose.psd/)
* assembly [Aspose.PSD](../../../)


