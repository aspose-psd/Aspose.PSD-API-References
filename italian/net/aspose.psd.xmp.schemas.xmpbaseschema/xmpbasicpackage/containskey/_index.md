---
title: "XmpBasicPackage.ContainsKey"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Metodo XmpBasicPackage. Determina se la chiave specificata contiene la chiave"
type: docs
weight: 40
url: /it/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/containskey/
---
{{< psd/tize >}}
## XmpBasicPackage.ContainsKey method

Determina se la chiave specificata contiene la chiave.

```csharp
public override bool ContainsKey(string key)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | Stringa | La chiave da verificare. |

### Valore di ritorno

Restituisce true se la chiave specificata contiene la chiave.

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


