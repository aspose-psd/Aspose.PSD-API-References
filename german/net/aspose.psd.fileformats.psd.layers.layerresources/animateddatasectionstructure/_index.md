---
title: Class AnimatedDataSectionStructure
second_title: Aspose.PSD für .NET-API-Referenz
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.AnimatedDataSectionStructure klas. Der Abschnitt mit animierten Daten.
type: docs
weight: 2300
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/
---
## AnimatedDataSectionStructure class

Der Abschnitt mit animierten Daten.

```csharp
public class AnimatedDataSectionStructure : OSTypeStructure
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Items](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/items/) { get; } | Ruft die animierten Datenabschnittsstrukturen ab oder legt sie fest. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/key/) { get; } | Ruft den Strukturschlüssel ab. |
| [KeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/keyname/) { get; set; } | Ruft den Schlüsselnamen ab oder legt ihn fest. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/length/) { get; } | Ruft die ab[`OSTypeStructure`](../ostypestructure/) Länge in Bytes. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| virtual [GetHeaderLength](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/getheaderlength/)() | Ruft die Kopfzeilenlänge ab. |
| [Save](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/save/)(StreamContainer) | Speichert die Struktur im angegebenen Stream-Container. |
| [SaveWithoutKeyName](../../aspose.psd.fileformats.psd.layers.layerresources/ostypestructure/savewithoutkeyname/)(StreamContainer) | Speichert die Struktur im angegebenen Stream-Container. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [StructureKey](../../aspose.psd.fileformats.psd.layers.layerresources/animateddatasectionstructure/structurekey/) | Identifiziert den Strukturschlüssel von AnDs. |

### Beispiele

Der folgende Code zeigt, wie die Verzögerungszeit im Zeitachsenrahmen von animierten Daten festgelegt/aktualisiert wird.

```csharp
[C#]

string sourceFile = "3_animated.psd";
string outputPsd = "output_3_animated.psd";

T FindStructure<T>(IEnumerable<OSTypeStructure> structures, string keyName) where T : OSTypeStructure
{
    foreach (var structure in structures)
    {
        if (structure.KeyName.ClassName == keyName)
        {
            return structure as T;
        }
    }

    return null;
}

OSTypeStructure[] AddOrReplaceStructure(IEnumerable<OSTypeStructure> structures, OSTypeStructure newStructure)
{
    List<OSTypeStructure> listOfStructures = new List<OSTypeStructure>(structures);

    for (int i = 0; i < listOfStructures.Count; i++)
    {
        OSTypeStructure structure = listOfStructures[i];
        if (structure.KeyName.ClassName == newStructure.KeyName.ClassName)
        {
            listOfStructures.RemoveAt(i);
            break;
        }
    }

    listOfStructures.Add(newStructure);

    return listOfStructures.ToArray();
}

using (PsdImage image = (PsdImage)Image.Load(sourceFile))
{
    foreach (var imageResource in image.ImageResources)
    {
        if (imageResource is AnimatedDataSectionResource)
        {
            var animatedData =
                (AnimatedDataSectionStructure) (imageResource as AnimatedDataSectionResource).AnimatedDataSection;
            var framesList = FindStructure<ListStructure>(animatedData.Items, "FrIn");

            var frame1 = (DescriptorStructure)framesList.Types[1];

            // Erstellt den Frame-Delay-Record mit dem Wert 100 Zenti-Sekunde, was 1 Sekunde entspricht.
            var frameDelay = new IntegerStructure(new ClassID("FrDl"));
            frameDelay.Value = 100; // Zeit in Centisekunden einstellen.

            frame1.Structures = AddOrReplaceStructure(frame1.Structures, frameDelay);

            break;
        }
    }

    image.Save(outputPsd);
}
```

### Siehe auch

* class [OSTypeStructure](../ostypestructure/)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* Montage [Aspose.PSD](../../)


