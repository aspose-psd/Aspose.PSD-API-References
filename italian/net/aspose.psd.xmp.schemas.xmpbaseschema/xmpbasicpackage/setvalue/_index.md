---
title: "XmpBasicPackage.SetValue"
second_title: "Riferimento API Aspose.PSD per .NET"
description: "Metodo XmpBasicPackage. Imposta il valore"
type: docs
weight: 120
url: /it/net/aspose.psd.xmp.schemas.xmpbaseschema/xmpbasicpackage/setvalue/
---
{{< psd/tize >}}
## XmpBasicPackage.SetValue method

Imposta il valore.

```csharp
public override void SetValue(string key, IXmlValue value)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| chiave | Stringa | La rappresentazione stringa della chiave identificata con il valore aggiunto. |
| valore | IXmlValue | Il valore a cui aggiungere. |

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

* interface [IXmlValue](../../../aspose.psd.xmp/ixmlvalue/)
* class [XmpBasicPackage](../)
* namespace [Aspose.PSD.Xmp.Schemas.XmpBaseSchema](../../../aspose.psd.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.PSD](../../../)


