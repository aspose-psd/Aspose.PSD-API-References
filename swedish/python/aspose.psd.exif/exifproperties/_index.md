---
title: "ExifProperties‑enumeration"
type: docs
weight: 160
url: /sv/python-net/aspose.psd.exif/exifproperties/
---

Lista över Exif‑taggar

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.ExifProperties

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Medlemsnamn** | **Beskrivning** |
| :- | :- |
| APERTURE_VALUE | Bländarvärdet för linsen. |
| ARTIST | Denna tagg registrerar namnet på kamerans ägare, fotograf eller bildskapare. Det detaljerade formatet är inte specificerat, men det rekommenderas att informationen skrivs enligt exemplet nedan för att underlätta interoperabilitet. När fältet lämnas tomt behandlas det som okänt. Ex.) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| BITS_PER_SAMPLE | Antalet bitar per bildkomponent. I denna standard är varje komponent i bilden 8 bitar, så värdet för denna tagg är 8. |
| BODY_SERIAL_NUMBER | Innehåller kamerahusets serienummer |
| BRIGHTNESS_VALUE | Ljusstyrkevärdet. |
| CAMERA_OWNER_NAME | Innehåller kamerans ägarnamn |
| CFA_PATTERN | Anger färgfilterarrayens (CFA) geometriska mönster för bildsensorn när en enkelskikts färgområdessensor används. Det gäller inte alla avkänningsmetoder. |
| COLOR_SPACE | Färgrymdsinformationsetiketten (ColorSpace) registreras alltid som färgrymdsspecifikatorn. |
| COMPONENTS_CONFIGURATION | Komponentkonfigurationen. |
| COMPRESSED_BITS_PER_PIXEL | Specifikt för komprimerad data; anger de komprimerade bitarna per bildpunkt. |
| COMPRESSION | Komprimeringsschemat som används för bilddata. När en huvudbild är JPEG-komprimerad är denna beteckning onödig och utelämnas. |
| CONTRAST | Denna etikett anger riktningen för kontrastbehandlingen som kameran tillämpade när bilden togs. |
| COPYRIGHT | Upphovsrättsinformation. I denna standard används etiketten för<br/>                att ange både fotografens och redaktörens upphovsrätt. Det är<br/>                upphovsrättsmeddelandet från den person eller organisation som påstår<br/>                sig ha rättigheter till bilden. Interoperabilitetens upphovsrätts<br/>                uttalande inklusive datum och rättigheter bör skrivas i detta<br/>                fält; t.ex. "Copyright, John Smith, 19xx. All rights<br/>                reserved.". I denna standard registreras både<br/>                fotografens och redaktörens upphovsrätt, där varje registreras i en<br/>                separat del av uttalandet. När det finns en tydlig skillnad<br/>                mellan fotografens och redaktörens upphovsrätt ska dessa<br/>                skrivas i ordning fotograf följt av redaktörens upphovsrätt,<br/>                separerade med NULL (i detta fall, eftersom uttalandet också avslutas med<br/>                en NULL, finns två NULL-koder). När endast fotografens<br/>                upphovsrätt anges, avslutas den med en NULL-kod. När endast<br/>                redaktörens upphovsrätt anges, består fotografens upphovsrättsdelen<br/>                av ett mellanslag följt av en avslutande NULL-kod, sedan<br/>                anges redaktörens upphovsrätt. När fältet lämnas tomt, behandlas det<br/>                som okänt. |
| CUSTOM_RENDERED | Denna etikett indikerar användning av specialbehandling av bilddata, såsom rendering anpassad för utskrift. När specialbehandling utförs förväntas läsaren inaktivera eller minimera ytterligare bearbetning. |
| DATE_TIME | Datum och tid för bildskapande. I Exif-standarden är det datum och tid då filen ändrades. |
| DATE_TIME_DIGITIZED | Datum och tid för digitalisering. |
| DATE_TIME_ORIGINAL | Datum och tid då den ursprungliga bilddatan skapades. |
| DEVICE_SETTING_DESCRIPTION | Denna etikett indikerar information om fotograferingsförhållandena för en specifik kameramodell. Etiketten används endast för att ange fotograferingsförhållandena i läsaren. |
| DIGITAL_ZOOM_RATIO | Denna tagg anger det digitala zoomförhållandet när bilden togs. Om täljaren i det registrerade värdet är 0, indikerar detta att digital zoom inte användes. |
| EXIF_IFD_POINTER | En pekare till Exif IFD. Interoperabilitet, Exif IFD har samma struktur som den IFD som specificeras i TIFF. Vanligtvis innehåller den dock inte bilddata som i fallet med TIFF. |
| EXIF_VERSION | Exif-versionen. |
| EXPOSURE_BIAS_VALUE | Exponeringsbiasvärdet. |
| EXPOSURE_INDEX | Anger exponeringsindexet som valdes på kameran eller inmatningsenheten när bilden fångades. |
| EXPOSURE_MODE | Denna tagg anger exponeringsläget som sattes när bilden togs. I auto‑bracketing‑läge tar kameran en serie bilder av samma scen med olika exponeringsinställningar. |
| EXPOSURE_PROGRAM | Klassen för programmet som kameran använder för att ställa in exponeringen när bilden tas. |
| EXPOSURE_TIME | Exponeringstid, angiven i sekunder. |
| FILE_SOURCE | Filkällan. |
| FLASH | Anger blixtens status när bilden togs. |
| FLASHPIX_VERSION | Flashpix-formatversionen som stöds av en FPXR‑fil. |
| FLASH_ENERGY | Anger stroboljuset vid tidpunkten då bilden fångas, mätt i Beam Candle Power Seconds (BCPS). |
| FOCAL_LENGTH | Den faktiska brännvidden på linsen, i mm. |
| FOCAL_LENGTH_IN_35_MM_FILM | Denna tagg anger den ekvivalenta brännvidden förutsatt en 35 mm filmkamera, i mm. Ett värde på 0 betyder att brännvidden är okänd. Observera att denna tagg skiljer sig från FocalLength‑taggen. |
| FOCAL_PLANE_RESOLUTION_UNIT | Anger enheten för att mäta FocalPlaneXResolution och FocalPlaneYResolution. Detta värde är detsamma som ResolutionUnit. |
| FOCAL_PLANE_X_RESOLUTION | Anger antalet pixlar i bildens bredd (X)-riktning per FocalPlaneResolutionUnit på kamerans fokalplan. |
| FOCAL_PLANE_Y_RESOLUTION | Anger antalet pixlar i bildens höjd (Y)-riktning per FocalPlaneResolutionUnit på kamerans fokalplan. |
| F_NUMBER | F‑numret. |
| GAIN_CONTROL | Denna tagg anger graden av total bildförstärkningsjustering. |
| GAMMA | Gamma‑värde |
| GPSDOP | Anger GPS DOP (dataprecisionsgrad). Ett HDOP‑värde skrivs under tvådimensionell mätning,<br/>                och PDOP under tredimensionell mätning. |
| GPS_ALTITUDE | Anger höjden baserat på referensen i GPSAltitudeRef. Höjden uttrycks som ett RATIONAL‑värde.<br/>                Referensenheten är meter. |
| GPS_ALTITUDE_REF | Anger den höjd som används som referenshöjd. Om referensen är havsnivå och höjden är över havsnivå,<br/>                ges värdet 0. Om höjden är under havsnivå, ges värdet 1 och höjden anges som ett absolut värde i<br/>                GPSAltitude‑taggen. |
| GPS_AREA_INFORMATION | En teckensträng som registrerar namnet på GPS‑området. Den första byten indikerar<br/>                den använda teckenkoden, och därefter följer namnet på GPS‑området. |
| GPS_DATE_STAMP | En teckensträng som registrerar datum- och tidsinformation i förhållande till UTC<br/>                (Coordinated Universal Time). Formatet är YYYY:MM:DD. |
| GPS_DEST_BEARING | Anger riktningen mot destinationspunkten. Intervallet för värden är från 0.00 till 359.99. |
| GPS_DEST_BEARING_REF | Anger referensen som används för att ange kursen till destinationspunkten. 'T' betyder sann riktning och 'M' är
                magnetisk riktning. |
| GPS_DEST_DISTANCE | Anger avståndet till destinationspunkten. |
| GPS_DEST_DISTANCE_REF | Anger enheten som används för att uttrycka avståndet till destinationspunkten. 'K', 'M' och 'N' representerar kilometer, miles
                och knop. |
| GPS_DEST_LATITUDE | Anger latituden för destinationspunkten. Latituden uttrycks som tre RATIONAL-värden som ger
                grader, minuter och sekunder, respektive. Om latituden uttrycks i grader, minuter och sekunder, är ett typiskt
                format dd/1,mm/1,ss/1. När grader och minuter används och till exempel bråktal av minuter anges upp till två decimaler, blir formatet dd/1,mmmm/100,0/1. |
| GPS_DEST_LATITUDE_REF | Anger om latituden för destinationspunkten är nordlig eller sydlig. ASCII-värdet 'N' indikerar nordlig
                latitud, och 'S' är sydlig latitud. |
| GPS_DEST_LONGITUDE | Anger longituden för destinationspunkten. Longituden uttrycks som tre RATIONAL-värden som ger
                grader, minuter och sekunder, respektive. Om longituden uttrycks i grader, minuter och sekunder, är ett typiskt
                format ddd/1,mm/1,ss/1. När grader och minuter används och till exempel bråktal av minuter anges upp till två decimaler, blir formatet ddd/1,mmmm/100,0/1. |
| GPS_DEST_LONGITUDE_REF | Anger om longituden för destinationspunkten är östlig eller västlig. ASCII 'E' indikerar östlig longitud,
                och 'W' är västlig longitud. |
| GPS_DIFFERENTIAL | Anger om differentialkorrigering tillämpas på GPS-mottagaren. |
| GPS_IFD_POINTER | GPS IFD-pekaren. |
| GPS_IMG_DIRECTION | Anger bildens riktning när den togs. Värdeintervallet är från 0.00 till 359.99. |
| GPS_IMG_DIRECTION_REF | Anger referensen för att ange bildens riktning när den tas. 'T' betyder sann riktning och 'M' är
                magnetisk riktning. |
| GPS_LATITUDE | Anger latituden. Latituden uttrycks som tre RATIONAL-värden som ger grader, minuter och
                sekunder, respektive. Om latituden uttrycks i grader, minuter och sekunder, är ett typiskt format
                dd/1,mm/1,ss/1. När grader och minuter används och till exempel bråktal av minuter anges upp till två
                decimaler, blir formatet dd/1,mmmm/100,0/1. |
| GPS_LATITUDE_REF | Anger om latituden är nordlig eller sydlig. |
| GPS_LONGITUDE | Anger longituden. Longituden uttrycks som tre RATIONAL‑värden som ger grader, minuter och<br/>                sekunder, i den ordningen. Om longituden uttrycks som grader, minuter och sekunder, skulle ett typiskt format vara<br/>                ddd/1,mm/1,ss/1. När grader och minuter används och exempelvis bråkdelar av minuter anges med upp till två<br/>                decimaler, skulle formatet vara ddd/1,mmmm/100,0/1. |
| GPS_LONGITUDE_REF | Anger om longituden är östlig eller västlig longitud. |
| GPS_MAP_DATUM | Anger de geodetiska kartdata som används av GPS‑mottagaren. |
| GPS_MEASURE_MODE | Anger GPS‑mätningsläget. - 2‑ eller 3‑dimensionellt. |
| GPS_PROCESSING_METHOD | En teckensträng som registrerar namnet på metoden som används för positionsbestämning.<br/>                Den första byten indikerar den använda teckenkoden, och detta följs av namnet<br/>                på metoden. |
| GPS_SATELLITES | Anger de GPS‑satelliter som används för mätningar. Denna tagg kan användas för att beskriva antalet satelliter,<br/>                deras ID‑nummer, höjdvinkel, azimut, SNR och annan information i ASCII‑notation. Formatet är inte<br/>                specificerat. Om GPS‑mottagaren inte kan utföra mätningar ska taggens värde sättas till NULL. |
| GPS_SPEED | Anger hastigheten för GPS‑mottagarens rörelse. |
| GPS_SPEED_REF | Anger enheten som används för att uttrycka GPS‑mottagarens rörelsehastighet. 'K', 'M' och 'N' representerar kilometer per<br/>                timme, miles per timme och knop. |
| GPS_STATUS | Anger GPS‑mottagarens status när bilden tas. |
| GPS_TIMESTAMP | Anger tiden som UTC (Coordinated Universal Time). Tidsstämpeln uttrycks som tre RATIONAL‑värden<br/>                som ger timme, minut och sekund. |
| GPS_TRACK | Anger riktningen för GPS‑mottagarens rörelse. Värdespannet är från 0,00 till 359,99. |
| GPS_TRACK_REF | Anger referensen för att ange riktningen för GPS‑mottagarens rörelse. 'T' betecknar sann riktning och 'M' är<br/>                magnetisk riktning. |
| GPS_VERSION_ID | Anger versionen av GPSInfoIFD. |
| IMAGE_DESCRIPTION | En teckensträng som ger bildens titel. Det kan vara en kommentar såsom "1988 company picnic" eller liknande. |
| IMAGE_LENGTH | Antalet rader av bilddata. |
| IMAGE_UNIQUE_ID | Bildens unika ID. |
| IMAGE_WIDTH | Antalet kolumner av bilddata, lika med antalet pixlar per rad. |
| ISO_SPEED | Information om ISO-hastighetsvärdet enligt ISO 12232. |
| ISO_SPEED_LATITUDE_YYY | Denna tagg anger ISO-hastighetslatitud yyy-värdet enligt ISO 12232. |
| ISO_SPEED_LATITUDE_ZZZ | Denna tagg anger ISO-hastighetslatitud zzz-värdet enligt ISO 12232. |
| JPEG_INTERCHANGE_FORMAT | Förskjutningen till startbyten (SOI) för JPEG-komprimerad miniatyrbildsdata. Detta används inte för primär bild JPEG-data. |
| JPEG_INTERCHANGE_FORMAT_LENGTH | Antalet byte av JPEG-komprimerad miniatyrbildsdata. Detta används inte för primär bild JPEG-data. JPEG-miniatyrbilder är inte delade utan registreras som en kontinuerlig JPEG-bitström från SOI till EOI. Appn- och COM-markörer bör inte registreras. Komprimerade miniatyrbilder måste registreras på högst 64 Kbyte, inklusive all annan data som ska registreras i APP1. |
| LENS_MAKE | Denna tagg registrerar objektivets tillverkare. |
| LENS_MODEL | Denna tagg registrerar objektivets modellnamn och modellnummer. |
| LENS_SERIAL_NUMBER | Denna tagg registrerar serienumret för utbytbart objektiv. |
| LENS_SPECIFICATION | Denna tagg noterar minsta brännvidd, största brännvidd, minsta bländartal vid minsta brännvidd och minsta bländartal vid största brännvidd. |
| LIGHT_SOURCE | Typ av ljuskälla. |
| MAKE | Tillverkaren av inspelningsutrustningen. Detta är tillverkaren av DSC, skanner, videodigitaliserare eller annan utrustning som skapade bilden. När fältet lämnas tomt behandlas det som okänt. |
| MAKER_NOTE | En tagg för tillverkare av Exif‑skrivare för att lagra önskad information. Innehållet bestäms av tillverkaren, men denna tagg bör inte användas för annat än dess avsedda syfte. |
| MAX_APERTURE_VALUE | Det maximala bländarvärdet. |
| METERING_MODE | Mätarläget. |
| MODEL | Modellnamnet eller modellnumret på utrustningen. Detta är modellnamnet eller -numret för DSC, skanner, videodigitaliserare eller annan utrustning som skapade bilden. När fältet lämnas tomt behandlas det som okänt. |
| OECF | Anger den opto‑elektriska konverteringsfunktionen (OECF) enligt ISO 14524. |
| ORIENTATION | Bildens orientering visas i rader och kolumner. |
| PHOTOGRAPHIC_SENSITIVITY | Anger ISO‑hastigheten och ISO‑latituden för kameran eller inmatningsenheten enligt ISO 12232. |
| PHOTOMETRIC_INTERPRETATION | Pixelns sammansättning. |
| PIXEL_X_DIMENSION | Information som är specifik för komprimerad data. När en komprimerad fil registreras ska den giltiga bredden på den meningsfulla bilden lagras i denna tagg, oavsett om det finns utfyllnadsdata eller en omstartsmarkör. |
| PIXEL_Y_DIMENSION | Information som är specifik för komprimerad data. När en komprimerad fil registreras ska den giltiga höjden på den meningsfulla bilden lagras i denna tagg. |
| PLANAR_CONFIGURATION | Anger om pixelkomponenter lagras i ett chunky‑ eller planarformat. Om detta fält inte finns antas TIFF‑standardvärdet 1 (chunky). |
| PRIMARY_CHROMATICITIES | Färgåtergivningen för bildens tre primära färger. Normalt är denna tagg inte nödvändig, eftersom färgrymden specificeras i färgrymdsinformationen i ColorSpace‑taggen. |
| RECOMMENDED_EXPOSURE_INDEX | Anger rekommenderat exponeringsindex |
| REFERENCE_BLACK_WHITE | Referensvärdet för svartpunkt och referensvärdet för vitpunkt<br/>                värde. Inga standardvärden anges i TIFF, men värdena nedan ges som standard här.<br/>                Färgrymden deklareras<br/>                i en färgrymdsinformations‑tagg, med standardvärdet<br/>                som ger de optimala bildegenskaperna<br/>                Interoperabilitet under dessa förhållanden |
| RELATED_SOUND_FILE | Den relaterade ljudfilen. |
| RESOLUTION_UNIT | Enheten för att mäta XResolution och YResolution. Samma enhet används för både XResolution och YResolution. Om bildens upplösning är okänd, anges 2 (tum). |
| ROWS_PER_STRIP | Antalet rader per remsa. Detta är antalet rader i bilden för en remsa när en bild delas in i remsor. |
| SAMPLES_PER_PIXEL | Antalet komponenter per pixel. Eftersom denna standard gäller för RGB- och YCbCr-bilder, är värdet som sätts för denna tagg 3. |
| SATURATION | Denna tagg anger riktningen för mättnadsbehandling som kameran tillämpade när bilden togs. |
| SCENE_CAPTURE_TYPE | Denna tagg anger typen av scen som fotograferades. Den kan också användas för att registrera läget som bilden togs i. |
| SCENE_TYPE | Anger scenens typ. Om en DSC spelade in bilden ska detta taggvärde alltid vara 1, vilket indikerar att bilden fotograferades direkt. |
| SENSING_METHOD | Anger bildsensortypen på kameran eller inmatningsenheten. |
| SENSITIVITY_TYPE | Typ av fotografisk känslighet |
| SHARPNESS | Denna tagg anger riktningen för skärpebehandling som kameran tillämpade när bilden togs |
| SHUTTER_SPEED_VALUE | Värdet för slutartiden. |
| PROGRAMVARA | Denna tagg registrerar namn och version av mjukvaran eller firmware för kameran eller bildinmatningsenheten som användes för att skapa bilden. Det detaljerade formatet är inte specificerat, men det rekommenderas att följa exemplet nedan. När fältet lämnas tomt behandlas det som okänt. |
| SPATIAL_FREQUENCY_RESPONSE | Denna tagg registrerar kamera- eller inmatningsenhetens spatialfrekvenstabell och SFR-värden i bildens bredd-, höjd- och diagonalriktning, enligt ISO 12233. |
| SPECTRAL_SENSITIVITY | Anger den spektrala känsligheten för varje kanal i den använda kameran. |
| STANDARD_OUTPUT_SENSITIVITY | Anger standardutgångskänsligheten för kameran |
| STRIP_BYTE_COUNTS | Det totala antalet byte i varje remsa. |
| STRIP_OFFSETS | För varje remsa, byteoffseten för den remsan. Det rekommenderas att detta väljs så att antalet byte per remsa inte överstiger 64 Kbyte.<br/>                Aux tag. |
| SUBJECT_AREA | Denna tagg anger platsen och området för huvudobjektet i hela scenen. |
| SUBJECT_DISTANCE | Avståndet till objektet, angivet i meter. |
| SUBJECT_DISTANCE_RANGE | Denna tagg anger avståndet till objektet. |
| SUBJECT_LOCATION | Anger platsen för huvudobjektet i scenen. Värdet för denna tagg representerar pixeln i centrum av huvudobjektet i förhållande till vänster kant, före rotationsbearbetning enligt Rotation tag. |
| SUBSEC_TIME | En tagg som används för att registrera bråkdelar av sekunder för DateTime‑taggen. |
| SUBSEC_TIME_DIGITIZED | En tagg som används för att registrera bråkdelar av sekunder för DateTimeDigitized‑taggen. |
| SUBSEC_TIME_ORIGINAL | En tagg som används för att registrera bråkdelar av sekunder för DateTimeOriginal‑taggen. |
| TRANSFER_FUNCTION | En överföringsfunktion för bilden, beskriven i tabellformat. Vanligtvis är denna tagg inte nödvändig, eftersom färgrymden specificeras i färgrymdsinformationen i ColorSpace‑taggen. |
| USER_COMMENT | En tagg för Exif‑användare att skriva nyckelord eller kommentarer på bilden utöver de i ImageDescription, och utan teckenkodningsbegränsningarna i ImageDescription‑taggen. |
| WHITE_BALANCE | Denna tagg anger vitbalansläget som sattes när bilden togs. |
| WHITE_POINT | Kromaticiteten för bildens vita punkt. Vanligtvis är denna tagg inte nödvändig, eftersom färgrymden specificeras i färgrymdsinformationen i ColorSpace‑taggen. |
| X_RESOLUTION | Antalet pixlar per ResolutionUnit i ImageWidth‑riktningen. När bildens upplösning är okänd anges 72 [dpi]. |
| Y_CB_CR_COEFFICIENTS | Matriskoefficienterna för transformation från RGB till YCbCr bilddata. |
| Y_CB_CR_POSITIONING | Positionen för krominanskomponenterna i förhållande till<br/>                luminanskomponenten. Detta fält är avsett endast för<br/>                JPEG-komprimerad data eller okomprimerad YCbCr-data. TIFF‑standardens<br/>                standardvärde är 1 (centrerad); men när Y:Cb:Cr = 4:2:2 rekommenderas i detta standard att 2 (sido‑placerad) används för<br/>                att lagra data, för att förbättra bildkvaliteten vid visning<br/>                på TV‑system. När detta fält saknas ska läsaren<br/>                anta TIFF‑standardvärdet. I fallet Y:Cb:Cr = 4:2:0 är<br/>                TIFF‑standardvärdet (centrerat) rekommenderat. Om läsaren<br/>                inte har möjlighet att stödja båda typerna av<br/>                YCbCrPositioning, ska den följa TIFF‑standardvärdet oavsett<br/>                värdet i detta fält. Det är önskvärt att läsare "<br/>                kan stödja både centrerad och sido‑placerad positionering. |
| Y_CB_CR_SUB_SAMPLING | Samplingsförhållandet för krominanskomponenterna i förhållande till luminanskomponenten. |
| Y_RESOLUTION | Antalet pixlar per ResolutionUnit i ImageLength‑riktningen. Samma värde som XResolution anges. |
