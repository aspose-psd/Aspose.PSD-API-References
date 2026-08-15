---
title: "aspose.psd.fileformats.psd.layers"
type: docs
weight: 260
url: /nl/python-net/aspose.psd.fileformats.psd.layers/
---




## **Classes**
| **Klasse** | **Beschrijving** |
| :- | :- |
| [ArtboardLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/artboardlayer/) | De artboard‑lagenklasse. |
| [BlendRange](/psd/python-net/aspose.psd.fileformats.psd.layers/blendrange/) | Het mengbereik. |
| [ChannelInformation](/psd/python-net/aspose.psd.fileformats.psd.layers/channelinformation/) | De kanaalinformatie. |
| [GlobalLayerMaskInfo](/psd/python-net/aspose.psd.fileformats.psd.layers/globallayermaskinfo/) | De globale laagmaskersectie. |
| [IGradientColorPoint](/psd/python-net/aspose.psd.fileformats.psd.layers/igradientcolorpoint/) | Basisinterface voor vul-instellingen |
| [ILayerResourceLoader](/psd/python-net/aspose.psd.fileformats.psd.layers/ilayerresourceloader/) | De laaggeresourcelader. |
| [IShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/ishapelayer/) | Beschrijft de eigenschappen van de Shape-laag. |
| [Layer](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) | De PSD-laag. |
| [LayerBlendingRangesData](/psd/python-net/aspose.psd.fileformats.psd.layers/layerblendingrangesdata/) | De laagmengselbereiken-gegevens. |
| [LayerGroup](/psd/python-net/aspose.psd.fileformats.psd.layers/layergroup/) | Groeplaagklasse |
| [LayerHashCalculator](/psd/python-net/aspose.psd.fileformats.psd.layers/layerhashcalculator/) | Hashcalculator voor PSD-lagen. Het kan worden gebruikt om gelijke of verschillende lagen in verschillende PSD-bestanden te vinden. |
| [LayerMaskData](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) | Definieert de basis LayerMaskData-klasse die informatie bevat over de laagmaskergegevens in het PSD‑bestand.<br/>            Het kan helpen om Adobe® Photoshop®‑bestanden programmatisch te wijzigen en het bewerken van PSD‑formaten te automatiseren.<br/>            Als de laag alleen een rastermasker heeft, bevat ImageData de bytes van de rastermaskergegevens.<br/>            Als de laag alleen een vectormasker heeft, bevat ImageData de gerasterde (gecachede) bytes van het vectormasker.<br/>            Als de laag zowel laag- als vectormaskers heeft, bevat ImageData de rastermasker‑ en de gerasterde vectormasker‑gegevens gecombineerd.<br/>            De [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) byte‑lengte moet gelijk zijn aan Breedte * Hoogte van de eigenschappen van [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/).<br/>            Merk op dat alleen het verwijderen / toevoegen / bijwerken van LayerMaskData niet voldoende is voor een correcte opslag<br/>            omdat kanalen niet worden bijgewerkt; hoewel het een correcte weergave kan opleveren.<br/>            De [Layer.add_layer_mask(layer_mask)](/psd/python-net/aspose.psd.fileformats.psd.layers/layer/) methode moet daarvoor worden gebruikt. |
| [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) | Definieert de LayerMaskDataFull‑klasse die informatie bevat over de maskergegevens in de PSD‑laagraag<br/>            wanneer de laag zowel laag‑ als vectormaskers heeft. Anders wordt een [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) gebruikt.<br/>            De ImageData bevat het rastermasker en het gerasterde vectormasker gecombineerd.<br/>            De byte‑lengte van ImageData moet gelijk zijn aan de eigenschappen MaskRectangle.Width * MaskRectangle.Height. |
| [LayerMaskDataShort](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatashort/) | Definieert de LayerMaskDataShort‑klasse die informatie bevat over de maskergegevens in de PSD‑laagraag<br/>            wanneer de laag alleen een raster‑ of vectormasker heeft, maar niet beide. Anders wordt een [LayerMaskDataFull](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdatafull/) gebruikt.<br/>            Als de laag alleen een rastermasker heeft, bevat ImageData de bytes van de rastermaskergegevens.<br/>            Als de laag alleen een vectormasker heeft, bevat ImageData de gerasterde (gecachede) bytes van het vectormasker.<br/>            De [LayerMaskData.image_data](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/) byte‑lengte moet gelijk zijn aan Breedte * Hoogte van de eigenschappen van [LayerMaskData.mask_rectangle](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskdata/). |
| [LayerResource](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresource/) | Stelt laaginfo voor. |
| [LayerResourcesRegistry](/psd/python-net/aspose.psd.fileformats.psd.layers/layerresourcesregistry/) | Definieer het register van laaggeresources voor het laden van PSD‑bestanden. |
| [LinkedLayersManager](/psd/python-net/aspose.psd.fileformats.psd.layers/linkedlayersmanager/) | Klasse voor beheer van gekoppelde lagen. |
| [SectionDividerLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/sectiondividerlayer/) | De sectiescheidingslaag om de grenzen van de map (laaggroep) te markeren. |
| [ShapeLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/shapelayer/) | Shape-laag. Omvat de logica voor het werken met Shape‑lagen en gerelateerde bronnen. |
| [TextLayer](/psd/python-net/aspose.psd.fileformats.psd.layers/textlayer/) | De tekstlaagklasse |
## **Enumerations**
| **Enumeratie** | **Beschrijving** |
| :- | :- |
| [LayerFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layerflags/) | De laagvlaggen |
| [LayerMaskFlags](/psd/python-net/aspose.psd.fileformats.psd.layers/layermaskflags/) | De laagmaskervlaggen |
