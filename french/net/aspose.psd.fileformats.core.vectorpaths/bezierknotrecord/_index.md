---
title: Class BezierKnotRecord
second_title: Référence de l'API Aspose.PSD pour .NET
description: Aspose.PSD.FileFormats.Core.VectorPaths.BezierKnotRecord classe. Classe denregistrement des nœuds de Bézier
type: docs
weight: 1330
url: /fr/net/aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/
---
## BezierKnotRecord class

Classe d'enregistrement des nœuds de Bézier

```csharp
public class BezierKnotRecord : VectorPathRecord
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [BezierKnotRecord](bezierknotrecord/#constructor)() | Initialise une nouvelle instance du`BezierKnotRecord` classe. |
| [BezierKnotRecord](bezierknotrecord/#constructor_1)(byte[]) | Initialise une nouvelle instance du`BezierKnotRecord` classe. |

## Propriétés

| Nom | La description |
| --- | --- |
| [IsClosed](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/isclosed/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est fermée. |
| [IsLinked](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/islinked/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est liée. |
| [IsOpen](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/isopen/) { get; set; } | Obtient ou définit une valeur indiquant si cette instance est ouverte. |
| [PathPoints](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/pathpoints/) { get; set; } | Obtient ou définit les points du chemin. |
| [Points](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/points/) { get; set; } | Obtient ou définit les points. |
| override [Type](../../aspose.psd.fileformats.core.vectorpaths/bezierknotrecord/type/) { get; } | Obtient le type. |

### Exemples

L'exemple suivant illustre la prise en charge du chargement des ressources VmskResource. Comment fonctionne l'édition des chemins.

```csharp
[C#]

[Test]
public void TestPsdNet106()
{
    string sourceFileName = "Rectangle.psd";
    string exportPath = "Rectangle_changed.psd";
    var im = (PsdImage)Image.Load(sourceFileName);
    using (im)
    {
        var resource = GetVmskResource(im);
        // En lisant
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
            throw new Exception("VmskResource was read wrong");
        }
        var pathFillRule = (PathFillRuleRecord)resource.Paths[0];
        var initialFillRule = (InitialFillRuleRecord)resource.Paths[1];
        var subpathLength = (LengthRecord)resource.Paths[2];
        // La règle de remplissage du chemin ne contient aucune information supplémentaire
        if (pathFillRule.Type != VectorPathType.PathFillRuleRecord ||
         initialFillRule.Type != VectorPathType.InitialFillRuleRecord ||
         initialFillRule.IsFillStartsWithAllPixels != false ||
         subpathLength.Type != VectorPathType.ClosedSubpathLengthRecord ||
         subpathLength.IsClosed != true ||
         subpathLength.IsOpen != false)
        {
            throw new Exception("VmskResource paths were read wrong");
        }
        // Édition
        resource.IsDisabled = true;
        resource.IsInverted = true;
        resource.IsNotLinked = true;
        var bezierKnot = (BezierKnotRecord)resource.Paths[3];
        bezierKnot.Points[0] = new Point(0, 0);
        bezierKnot = (BezierKnotRecord)resource.Paths[4];
        bezierKnot.Points[0] = new Point(8039797, 10905190);
        initialFillRule.IsFillStartsWithAllPixels = true;
        subpathLength.IsClosed = false;
        im.Save(exportPath);
    }
}

private VmskResource GetVmskResource(PsdImage image)
{
    var layer = image.Layers[1];
    VmskResource resource = null;
    var resources = layer.Resources;
    for (int i = 0; i < resources.Length; i++)
    {
        if (resources[i] is VmskResource)
        {
            resource = (VmskResource)resources[i];
            break;
        }
    }
    if (resource == null)
    {
        throw new Exception("VmskResource not found");
    }
    return resource;
}
```

L'exemple suivant illustre la prise en charge du chargement des ressources VsmsResource. Comment fonctionne l'édition des chemins.

```csharp
[C#]

[Test]
public void TestPsdNet140()
{
    // Prise en charge de VsmsResource
    string sourceFileName = "EmptyRectangle.psd";
    string exportPath = "EmptyRectangle_changed.psd";
    var im = (PsdImage)Image.Load(sourceFileName);
    using (im)
    {
        var resource = GetVsmsResource(im);
        // En lisant
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

        // La règle de remplissage du chemin ne contient aucune information supplémentaire
        if (pathFillRule.Type != VectorPathType.PathFillRuleRecord ||
        initialFillRule.Type != VectorPathType.InitialFillRuleRecord ||
        initialFillRule.IsFillStartsWithAllPixels != false ||
        subpathLength.Type != VectorPathType.ClosedSubpathLengthRecord ||
        subpathLength.IsClosed != true ||
        subpathLength.IsOpen != false)
        {
            throw new Exception("VsmsResource paths were read wrong");
        }

        // Édition
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

### Voir également

* class [VectorPathRecord](../vectorpathrecord/)
* espace de noms [Aspose.PSD.FileFormats.Core.VectorPaths](../../aspose.psd.fileformats.core.vectorpaths/)
* Assemblée [Aspose.PSD](../../)


