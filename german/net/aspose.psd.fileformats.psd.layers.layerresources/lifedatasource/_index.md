---
title: LiFeDataSource
second_title: Aspose.PSD für .NET-API-Referenz
description: Definiert die LnkeDataSourceKlasse die Informationen über extern verknüpfte Dateien enthält. Dies ist Teil der PSDDateiformatManipulationsAPI die hilft Adobe PhotoshopDateien zu ändern
type: docs
weight: 2660
url: /de/net/aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/
---
## LiFeDataSource class

Definiert die LnkeDataSource-Klasse, die Informationen über extern verknüpfte Dateien enthält. Dies ist Teil der PSD-Dateiformat-Manipulations-API, die hilft, Adobe® Photoshop®-Dateien zu ändern

```csharp
public class LiFeDataSource : LinkDataSource
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [LiFeDataSource](lifedatasource#constructor)() | Initialisiert eine neue Instanz von[`LiFeDataSource`](../lifedatasource) Klasse. |
| [LiFeDataSource](lifedatasource#constructor_1)(int, Guid, string, string, string) | Initialisiert eine neue Instanz von[`LiFeDataSource`](../lifedatasource) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AdobeStockId](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/adobestockid) { get; set; } | Ruft die AdobeStockId der Grafikbibliothek für Adobe® Photoshop® CC-Bibliotheken ab oder legt sie fest. |
| [AdobeStockLicenseState](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/adobestocklicensestate) { get; } | Ruft den Status der Adobe Stock-Lizenz ab, falls verfügbar, für Adobe® Photoshop® CC-Bibliotheken. |
| [AssetLockedState](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetlockedstate) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob das PSD-Asset gesperrt ist. Der Asset-Sperrstatus für Adobe® Photoshop® СС Libraries-Assets. |
| [AssetModTime](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/assetmodtime) { get; set; } | Ruft die Änderungszeit des Assets für Adobe® Photoshop® СС Libraries-Assets ab oder legt sie fest. |
| [ChildDocId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/childdocid) { get; set; } | Ruft die untergeordnete Dokumentkennung in der liFE- oder liFD-Datenquelle der Lnk2-/LnkE-Adobe® Photoshop®-Ressource ab oder legt sie fest. |
| [CompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/compid) { get; set; } | Erhält oder setzt die ID der aktuell ausgewählten Komposition für das untergeordnete Dokument, die -1 ist, wenn keine ausgewählt ist. Kompositionen sind Kompositionen eines Seitenlayouts, die Designer erstellen können. Mithilfe von Ebenenkompositionen können Sie mehrere Versionen eines Layouts in einer einzigen Adobe® Photoshop®-Datei erstellen, verwalten und anzeigen. Eine Ebenenkomposition ist eine Momentaufnahme eines Zustands des Ebenenbedienfelds. Ebenenkompositionen speichern drei Arten von Ebenenoptionen, aber diese Eigenschaft erhält die Auswahlkennung der Ebenenkomposition für Smart Objects. [Ebenenkompositionen in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [Date](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/date) { get; set; } | Ruft Datum und Uhrzeit des letzten Schreibens der externen Datei in der LiFE-Datenquelle der PSD-LnkE-Ressource ab oder legt sie fest. |
| [ElementName](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/elementname) { get; set; } | Ruft den Elementnamen der Grafikbibliothek für Adobe® Photoshop® CC-Bibliotheken ab oder legt ihn fest. |
| [ElementRef](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/elementref) { get; set; } | Ruft die Elementreferenz der Grafikbibliothek für Adobe® Photoshop® CC-Bibliotheken ab oder legt sie fest. |
| [FileCreator](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filecreator) { get; set; } | Holt oder setzt den Dateiersteller im PSD-Format LnkE / Lnk2-Ressource. |
| [FileName](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/filename) { get; set; } | Ruft den Namen der externen oder eingebetteten Datei in der PSD-Link-Ressource ab oder legt ihn fest. |
| [FileSize](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/filesize) { get; set; } | Ruft die Größe der externen Datei in der LiFE-Datenquelle der PSD-LnkE-Ressource ab oder legt sie fest. |
| [FileType](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/filetype) { get; set; } | Ermittelt oder setzt den Typ der eingebetteten oder externen Datei, die die Adobe® Photoshop® Lnk2/LnkE-Ressource enthält oder verlinkt. |
| [FullPath](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/fullpath) { get; set; } | Ruft den vollständigen Pfad der externen Datei in der LiFE-Datenquelle der PSD-LnkE-Ressource ab oder legt ihn fest. |
| [HasFileOpenDescriptor](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/hasfileopendescriptor) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob diese Verknüpfungsdatenquelle den Dateiöffnungsdeskriptor hat: CompId und OriginalCompId. |
| [IsLibraryLink](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/islibrarylink) { get; } | Ruft einen Wert ab, der angibt, ob diese PSD-Link-Datenquelle mit dem Adobe® Photoshop® СС-Bibliothekselement verknüpft ist. |
| [Length](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/length) { get; } | Ruft die Länge der Link-Datenquelle in Bytes ab. |
| [OriginalCompId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalcompid) { get; } | Ruft die ursprüngliche ID der aktuell ausgewählten Komposition für das untergeordnete Dokument ab, die -1 ist, wenn keine ausgewählt ist. Diese Eigenschaft erhält die ursprüngliche Layer-Kompositionsauswahlkennung für Smart Objects. [Ebenenkompositionen in Smart Objects](https://helpx.adobe.com/photoshop/using/layer-comps.html) |
| [OriginalFileName](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/originalfilename) { get; } | Ruft den ursprünglichen Dateinamen der Datenquelle in der globalen Link-Ressource von Adobe® Photoshop® ab. |
| [RelativePath](../../aspose.psd.fileformats.psd.layers.layerresources/lifedatasource/relativepath) { get; set; } | Ruft den relativen Pfad der externen Datei in der LiFE-Datenquelle der PSD-LnkE-Ressource ab oder legt ihn fest. |
| [Type](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/type) { get; } | Ruft den Datenquellentyp des globalen Links von Adobe® Photoshop® ab, der einer der folgenden oder keiner sein kann: Die eingebettete verknüpfte Datei liFD, die der PSD Lnk2Resource entspricht Die externe verknüpfte Datei liFE, die der PSD LnkeResource entspricht Der Alias der verknüpften Datei liFA |
| [UniqueId](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/uniqueid) { get; } | Ruft die globale eindeutige Kennung der Datenquelle in der PSD-Link-Ressource ab. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/linkdatasource/version) { get; } | Ruft die Version der Datenquelle in der PSD-LnkE-/Lnk2-Ressource ab. |

### Beispiele

Dieses Beispiel zeigt, wie Eigenschaften der Psd LnkE-Ressource abgerufen und festgelegt werden.

```csharp
[C#]

string message = "The example works incorrectly.";
void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(message);
    }
}

// Dieses Beispiel zeigt, wie Eigenschaften der Psd LnkE-Ressource abgerufen und festgelegt werden, die Informationen zu einer extern verknüpften Datei enthält.
void ExampleOfLnkEResourceSupport(
    string fileName,
    int length,
    int length2,
    int length3,
    int length4,
    string fullPath,
    string date,
    double assetModTime,
    string childDocId,
    bool locked,
    string uid,
    string name,
    string originalFileName,
    string fileType,
    long size,
    int version)
{
    string outputPath = fileName;
    using (PsdImage image = (PsdImage)Image.Load(fileName))
    {
        LnkeResource lnkeResource = null;
        foreach (var resource in image.GlobalLayerResources)
        {
            lnkeResource = resource as LnkeResource;
            if (lnkeResource != null)
            {
                LiFeDataSource lifeSource = lnkeResource[0];
                AssertAreEqual(lnkeResource.Length, length);
                AssertAreEqual(lifeSource.UniqueId, new Guid(uid));
                AssertAreEqual(lifeSource.FullPath, fullPath);
                AssertAreEqual(lifeSource.Date.ToString(CultureInfo.InvariantCulture), date);
                AssertAreEqual(lifeSource.AssetModTime, assetModTime);
                AssertAreEqual(lifeSource.FileName, name);
                AssertAreEqual(lifeSource.FileSize, size);
                AssertAreEqual(lifeSource.ChildDocId, childDocId);
                AssertAreEqual(lifeSource.Version, version);
                AssertAreEqual(lifeSource.FileType.TrimEnd(' '), fileType);
                AssertAreEqual(lifeSource.FileCreator.TrimEnd(' '), string.Empty);
                AssertAreEqual(lifeSource.OriginalFileName, originalFileName);
                AssertAreEqual(false, lnkeResource.IsEmpty);
                AssertAreEqual(true, lifeSource.Type == LinkDataSourceType.liFE);
                if (version == 7)
                {
                    AssertAreEqual(lifeSource.AssetLockedState, locked);
                }

                if (lifeSource.HasFileOpenDescriptor)
                {
                    AssertAreEqual(lifeSource.CompId, -1);
                    AssertAreEqual(lifeSource.OriginalCompId, -1);
                }

                lifeSource.FullPath =
                    @"file:///C:/Aspose/net/Aspose.Psd/test/testdata/Images/Psd/SmartObjects/rgb8_2x2.png";
                AssertAreEqual(lnkeResource.Length, length2);
                lifeSource.FileName = "rgb8_2x23.png";
                AssertAreEqual(lnkeResource.Length, length3);
                lifeSource.ChildDocId = Guid.NewGuid().ToString();
                AssertAreEqual(lnkeResource.Length, length4);
                lifeSource.Date = DateTime.Now;
                lifeSource.AssetModTime = double.MaxValue;
                lifeSource.FileSize = long.MaxValue;
                lifeSource.FileType = "test";
                lifeSource.FileCreator = "file";
                lifeSource.CompId = int.MaxValue;
                break;
            }
        }

        AssertAreEqual(true, lnkeResource != null);

        image.Save(outputPath, new PsdOptions(image));
    }
}

// Dieses Beispiel zeigt, wie Eigenschaften der Psd LnkeResource abgerufen und festgelegt werden, die Informationen über extern verknüpfte JPEG-Dateien enthält.
ExampleOfLnkEResourceSupport(
    @"photooverlay_5_new.psd",
    0x21c,
    0x26c,
    0x274,
    0x27c,
    @"file:///C:/Users/cvallejo/Desktop/photo.jpg",
    "05/09/2017 22:24:51",
    0,
    "F062B9DB73E8D124167A4186E54664B0",
    false,
    "02df245c-36a2-11e7-a9d8-fdb2b61f07a7",
    "photo.jpg",
    "photo.jpg",
    "JPEG",
    0x1520d,
    7);

// Dieses Beispiel zeigt, wie Eigenschaften der PSD LnkeResource abgerufen und festgelegt werden, die Informationen zu einer extern verknüpften PNG-Datei enthält.
ExampleOfLnkEResourceSupport(
    "rgb8_2x2_linked.psd",
    0x284,
    0x290,
    0x294,
    0x2dc,
    @"file:///C:/Aspose/net/Aspose.Psd/test/testdata/Issues/PSDNET-491/rgb8_2x2.png",
    "04/14/2020 14:23:44",
    0,
    string.Empty,
    false,
    "5867318f-3174-9f41-abca-22f56a75247e",
    "rgb8_2x2.png",
    "rgb8_2x2.png",
    "png",
    0x53,
    7);

// Dieses Beispiel zeigt, wie Eigenschaften der PSD LnkeResource abgerufen und festgelegt werden, die Informationen zu zwei extern verknüpften PNG- und PSD-Dateien enthält.
ExampleOfLnkEResourceSupport(
    "rgb8_2x2_linked2.psd",
    0x590,
    0x580,
    0x554,
    0x528,
    @"file:///C:/Aspose/net/Aspose.Psd/test/testdata/Images/Psd/AddColorBalanceAdjustmentLayer.psd",
    "01/15/2020 13:02:00",
    0,
    "adobe:docid:photoshop:9312f484-3403-a644-8973-e725abc95fb7",
    false,
    "78a5b588-364f-0940-a2e5-a450a031aa48",
    "AddColorBalanceAdjustmentLayer.psd",
    "AddColorBalanceAdjustmentLayer.psd",
    "8BPS",
    0x4aea,
    7);

// Dieses Beispiel zeigt, wie Eigenschaften der Photoshop Psd LnkeResource abgerufen und festgelegt werden, die Informationen zu einem extern verknüpften CC Libraries-Asset enthält.
ExampleOfLnkEResourceSupport(
    "rgb8_2x2_asset_linked.psd",
    0x398,
    0x38c,
    0x388,
    0x3d0,
    @"CC Libraries Asset “rgb8_2x2_linked/rgb8_2x2” (Feature is available in Photoshop CC 2015)",
    "01/01/0001 00:00:00",
    1588890915488.0d,
    string.Empty,
    false,
    "ec15f0a8-7f13-a640-b928-7d29c6e9859c",
    "rgb8_2x2_linked",
    "rgb8_2x2.png",
    "png",
    0,
    7);
```

Der folgende Code demonstriert die Unterstützung der LnkeResource-Ressource.

```csharp
[C#]

void AssertIsTrue(bool condition)
{
    if (!condition)
    {
        throw new FormatException(string.Format("Expected true"));
    }
}

void AssertAreEqual(object actual, object expected)
{
    if (!object.Equals(actual, expected))
    {
        throw new FormatException(string.Format("Actual value {0} are not equal to expected {1}.", actual, expected));
    }
}

object[] ComplexLnkEResourceSupportCases = new object[]
{
    new object[]
    {
        "10fc87d0-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/or hdr btns” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633541.0d,
        "uuid:8485ca8d-9496-7f4d-9ef7-4243a00d4161",
        "OneReview-InDesign-InContextTranslation",
        "or hdr btns.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b4
    },
    new object[]
    {
        "10fc87cc-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/cs Id icon” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633512.0d,
        "uuid:c18be832-adf7-4b43-8223-a9740807a66c",
        "OneReview-InDesign-InContextTranslation",
        "cs Id icon.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b0
    },
    new object[]
    {
        "10fef79c-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/pointer cursor” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633570.0d,
        "uuid:9d7ccaac-f094-214b-8721-1a07ae8700a9",
        "OneReview-InDesign-InContextTranslation",
        "pointer cursor.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x03c0
    },
    new object[]
    {
        "10fef79a-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/x” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633555.0d,
        "uuid:b28aa699-21d6-2d4d-a4c7-790234c1b6ba",
        "OneReview-InDesign-InContextTranslation",
        "x.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x38c
    },
    new object[]
    {
        "10fef79b-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/modal btns” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633562.0d,
        "uuid:1bd42767-058d-da44-bdee-eada3b9d40a5",
        "OneReview-InDesign-InContextTranslation",
        "modal btns.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b0
    },
    new object[]
    {
        "10fc87cd-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/cs ppt icon” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633519.0d,
        "uuid:215499ac-ac44-b44d-894b-9ff2c7008d9d",
        "OneReview-InDesign-InContextTranslation",
        "cs ppt icon.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b4
    },
    new object[]
    {
        "10fc87cf-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/cs AI icon” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633534.0d,
        "uuid:a67964d4-8682-d649-8118-474cb1776264",
        "OneReview-InDesign-InContextTranslation",
        "cs AI icon.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b0
    },
    new object[]
    {
        "10fc87ce-688f-1179-9685-9d0a040abdc3",
        @"CC Libraries Asset “OneReview-InDesign-InContextTranslation/cs PSD icon” (Feature is available in Photoshop CC 2015)",
        "01/01/0001 00:00:00",
        1463698633527.0d,
        "uuid:8e9d5745-9f23-6f49-968e-647a45811bcb",
        "OneReview-InDesign-InContextTranslation",
        "cs PSD icon.ai",
        0L,
        "",
        6,
        "unlicensed",
        false,
        0x3b4
    },
};

void ExampleOfComplexLnkEResourceSupport(string filePath, int length, int length2, object[] dataSourceExpectedValues)
{
    filePath = "PSDNET652_1" + Path.DirectorySeparatorChar + filePath;
    string fileName = Path.GetFileName(filePath);
    using (PsdImage image = (PsdImage)Image.Load(filePath))
    {
        LnkeResource lnkeResource = null;
        foreach (var resource in image.GlobalLayerResources)
        {
            lnkeResource = resource as LnkeResource;
            if (lnkeResource != null)
            {
                AssertAreEqual(lnkeResource.DataSourceCount, 8);
                AssertAreEqual(lnkeResource.Length, length);
                AssertAreEqual(lnkeResource.IsEmpty, false);

                for (int i = 0; i < lnkeResource.DataSourceCount; i++)
                {
                    LiFeDataSource liFeSource = lnkeResource[i];
                    object[] expected = (object[])dataSourceExpectedValues[i];
                    AssertAreEqual(liFeSource.Type, LinkDataSourceType.liFE);
                    AssertAreEqual(liFeSource.UniqueId, new Guid((string)expected[0]));
                    AssertAreEqual(liFeSource.FullPath, expected[1]);
                    AssertAreEqual(liFeSource.Date.ToString(CultureInfo.InvariantCulture), expected[2]);
                    AssertAreEqual(liFeSource.AssetModTime, expected[3]);
                    AssertAreEqual(liFeSource.ChildDocId, expected[4]);
                    AssertAreEqual(liFeSource.FileName, expected[5]);
                    AssertAreEqual(liFeSource.OriginalFileName, expected[6]);
                    AssertAreEqual(liFeSource.FileSize, expected[7]);
                    AssertAreEqual(liFeSource.FileType, expected[8]);
                    AssertAreEqual(liFeSource.FileCreator.TrimEnd(' '), string.Empty);
                    AssertAreEqual(liFeSource.Version, expected[9]);
                    AssertAreEqual(liFeSource.AdobeStockLicenseState, expected[10]);
                    AssertAreEqual(liFeSource.HasFileOpenDescriptor, (bool)expected[11]);

                    if (liFeSource.HasFileOpenDescriptor)
                    {
                        AssertAreEqual(liFeSource.CompId, -1);
                        AssertAreEqual(liFeSource.OriginalCompId, -1);
                        liFeSource.CompId = int.MaxValue;
                    }

                    liFeSource.FullPath = @"file:///C:/Aspose/net/Aspose.Psd/test/testdata/Images/Psd/SmartObjects/rgb8_2x2.png";
                    liFeSource.FileName = "rgb8_2x23.png";
                    liFeSource.ChildDocId = Guid.NewGuid().ToString();
                    liFeSource.Date = DateTime.Now;
                    liFeSource.AssetModTime = double.MaxValue;
                    liFeSource.FileSize = long.MaxValue;
                    liFeSource.FileType = "test";
                    liFeSource.FileCreator = "file";
                    AssertAreEqual((int)liFeSource.Length, expected[12]);
                }

                AssertAreEqual(lnkeResource.Length, length2);
                break;
            }
        }

        AssertIsTrue(lnkeResource != null);
    }
}

ExampleOfComplexLnkEResourceSupport(
    "OneReview-InDesign-RefreshPreviewIxD(2).psd",
    0x21ac,
    0x1db8,
    ComplexLnkEResourceSupportCases);
```

### Siehe auch

* class [LinkDataSource](../linkdatasource)
* namensraum [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources)
* Montage [Aspose.PSD](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PSD.dll -->
