---
title: "PsdOptions.UpdateMetadata"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà PsdOptions. Ottiene o imposta un valore che indica se aggiornare i metadati. Se il valore è true i metadati saranno aggiornati durante il salvataggio di un'immagine"
type: docs
weight: 110
url: /it/net/aspose.psd.imageoptions/psdoptions/updatemetadata/
---
{{< psd/tize >}}
## PsdOptions.UpdateMetadata property

Ottiene o imposta un valore che indica se [aggiornare i metadati]. Se il valore è true, i metadati saranno aggiornati durante il salvataggio di un'immagine.

```csharp
public bool UpdateMetadata { get; set; }
```

### Property Value

`true` se [aggiornare i metadati]; altrimenti, `false`.

## Esempi

Il codice seguente dimostra l'uso dell'opzione UpdateMetadata per aggiornare il valore CreatorTool nei dati xmp.

```csharp
[C#]

string path = "output.psd";

using (var image = new PsdImage(100, 100))
{
    // Se vuoi che lo strumento creatore cambi, assicurati che la proprietà "UpdateMetadata" sia impostata su true. È impostata su true per impostazione predefinita.
    var psdOptions = new PsdOptions();
    psdOptions.UpdateMetadata = true;

    // Salvataggio dell'immagine. 
    image.Save(path, psdOptions);

    // Verifica dello strumento creatore nel codice.
    var xmpData = image.XmpData;
    var basicPackage = image.XmpData.GetPackage(Namespaces.XmpBasic);

    // Qui verranno aggiornate le informazioni sullo strumento creatore.
    var currentCreatorTool = (string)basicPackage[":CreatorTool"];
}
```

### Vedi anche

* class [PsdOptions](../)
* namespace [Aspose.PSD.ImageOptions](../../../aspose.psd.imageoptions/)
* assembly [Aspose.PSD](../../../)


