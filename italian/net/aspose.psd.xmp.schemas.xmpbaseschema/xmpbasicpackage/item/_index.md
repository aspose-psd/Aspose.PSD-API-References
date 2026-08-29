---
title: "XmpBasicPackage.Item"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Proprietà XmpBasicPackage. Ottiene o imposta l'Object con la chiave specificata"
type: docs
weight: 20
url: /it/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/item/
---
{{< psd/tize >}}
## XmpBasicPackage indexer

Ottiene o imposta l'Object con la chiave specificata.

```csharp
public override object this[string key] { get; set; }
```

| Parametro | Descrizione |
| --- | --- |
| chiave | La chiave che identifica il valore. |

### Valore di ritorno

Restituisce l'Object con la chiave specificata.

### Property Value

L'Object.

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

* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


