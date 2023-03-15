---
title: Class VsmsResource
second_title: Aspose.PSD för .NET API-referens
description: Aspose.PSD.FileFormats.Psd.Layers.LayerResources.VsmsResource klass. Klass VsmsResource. Denna resurs innehåller information om vektorlager mask
type: docs
weight: 3380
url: /sv/net/aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/
---
## VsmsResource class

Klass VsmsResource. Denna resurs innehåller information om vektorlager mask

```csharp
public class VsmsResource : VectorPathDataResource
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [VsmsResource](vsmsresource/#constructor)() | Initierar en ny instans av`VsmsResource` class. |
| [VsmsResource](vsmsresource/#constructor_1)(byte[]) | Initierar en ny instans av`VsmsResource` class. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [IsDisabled](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isdisabled/) { get; set; } | Hämtar eller ställer in ett värde som anger om denna instans är inaktiverad. |
| [IsInverted](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isinverted/) { get; set; } | Hämtar eller ställer in ett värde som anger om denna instans är inverterad. |
| [IsNotLinked](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/isnotlinked/) { get; set; } | Hämtar eller ställer in ett värde som anger om denna instans inte är länkad. |
| override [Key](../../aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/key/) { get; } | Hämtar lagerresursnyckeln. |
| override [Length](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/length/) { get; } | Hämtar lagerresurslängden i byte. |
| [Paths](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/paths/) { get; set; } | Hämtar eller sätter sökvägsposterna. |
| override [PsdVersion](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/psdversion/) { get; } | Hämtar psd-versionen. |
| override [Signature](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/signature/) { get; } | Får signaturen. |
| [Version](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/version/) { get; set; } | Hämtar eller ställer in versionen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Save](../../aspose.psd.fileformats.psd.layers.layerresources/vectorpathdataresource/save/)(StreamContainer, int) | Sparar resursen till den angivna strömbehållaren. |
| override [ToString](../../aspose.psd.fileformats.psd.layers/layerresource/tostring/)() | Returnerar enString som representerar denna instans. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [TypeToolKey](../../aspose.psd.fileformats.psd.layers.layerresources/vsmsresource/typetoolkey/) | Typverktygets infonyckel. |

### Exempel

Följande exempel visar stödet för VsmsResource resursladdning. Hur fungerar redigeringen av banor.

```csharp
[C#]

[Test]
public void TestPsdNet140()
{
    // VsmsResource Support
    string sourceFileName = "EmptyRectangle.psd";
    string exportPath = "EmptyRectangle_changed.psd";
    var im = (PsdImage)Image.Load(sourceFileName);
    using (im)
    {
        var resource = GetVsmsResource(im);
        // Läser
        if (resource.IsDisabled != false ||
            resource.IsInverted != false ||
            resource.IsNotLinked != false ||
            resource.Paths.Length != 7 ||
            resource.Paths[0].Type != VectorPathType.PathFillRuleRecord ||
            resource.Paths[1].Type != VectorPathType.InitialFillRuleRecord ||
            resource.Paths[2].Type != VectorPathType.ClosedSubpathLengthRecord ||
            resource.Paths[3].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
            resource.Paths[4].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
            resource.Paths[5].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked ||
            resource.Paths[6].Type != VectorPathType.ClosedSubpathBezierKnotUnlinked)
        {
            throw new Exception("VsmsResource was read wrong");
        }

        var pathFillRule = (PathFillRuleRecord)resource.Paths[0];
        var initialFillRule = (InitialFillRuleRecord)resource.Paths[1];
        var subpathLength = (LengthRecord)resource.Paths[2];

        // Sökvägsfyllningsregeln innehåller ingen ytterligare information
        if (pathFillRule.Type != VectorPathType.PathFillRuleRecord ||
        initialFillRule.Type != VectorPathType.InitialFillRuleRecord ||
        initialFillRule.IsFillStartsWithAllPixels != false ||
        subpathLength.Type != VectorPathType.ClosedSubpathLengthRecord ||
        subpathLength.IsClosed != true ||
        subpathLength.IsOpen != false)
        {
            throw new Exception("VsmsResource paths were read wrong");
        }

        // Redigering
        resource.IsDisabled = true;
        resource.IsInverted = true;
        resource.IsNotLinked = true;
        var bezierKnot = (BezierKnotRecord)resource.Paths[3];
        bezierKnot.Points[0] = new Point(0, 0);
        bezierKnot = (BezierKnotRecord)resource.Paths[4];
        bezierKnot.Points[0] = new Point(8039798, 10905191);
        initialFillRule.IsFillStartsWithAllPixels = true;
        subpathLength.IsClosed = false;
        im.Save(exportPath);
    }
}

private VsmsResource GetVsmsResource(PsdImage image)
{
    var layer = image.Layers[1];
    VsmsResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VsmsResource)
        {
            resource = (VsmsResource)resources[i];
            break;
        }
    }
    if (resource == null)
    {
        throw new Exception("VsmsResource not found");
    }
    return resource;
}
```

### Se även

* class [VectorPathDataResource](../vectorpathdataresource/)
* class [LayerResource](../../aspose.psd.fileformats.psd.layers/layerresource/)
* namnutrymme [Aspose.PSD.FileFormats.Psd.Layers.LayerResources](../../aspose.psd.fileformats.psd.layers.layerresources/)
* hopsättning [Aspose.PSD](../../)


