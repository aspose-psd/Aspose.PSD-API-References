---
title: "ExifProperties Enumeratie"
type: docs
weight: 160
url: /nl/python-net/aspose.psd.exif/exifproperties/
---

Lijst met Exif-tags

**Module:** [aspose.psd.exif](/psd/python-net/aspose.psd.exif/)

**Full Name:** aspose.psd.exif.ExifProperties

**Aspose.PSD Version:** 24.12.0

## **Members**
| **Lidnaam** | **Beschrijving** |
| :- | :- |
| APERTURE_VALUE | De lensdiafragmawaarde. |
| ARTIST | Deze tag registreert de naam van de camerabezitter, fotograaf of beeldmaker. Het gedetailleerde formaat is niet gespecificeerd, maar het wordt aanbevolen de informatie te schrijven zoals in het onderstaande voorbeeld voor betere interoperabiliteit. Wanneer het veld leeg wordt gelaten, wordt het beschouwd als onbekend. Bijv.) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| BITS_PER_SAMPLE | Het aantal bits per beeldcomponent. In deze standaard is elke component van het beeld 8 bits, dus de waarde voor deze tag is 8. |
| BODY_SERIAL_NUMBER | Bevat het serienummer van de camerabehuizing. |
| BRIGHTNESS_VALUE | De helderheidswaarde. |
| CAMERA_OWNER_NAME | Bevat de naam van de camerabezitter. |
| CFA_PATTERN | Geeft het geometrische patroon van de kleurfilterarray (CFA) van de beeldsensor aan wanneer een één-chip kleurgebiedsensor wordt gebruikt. Het is niet van toepassing op alle sensormethoden. |
| COLOR_SPACE | De kleurruimte-informatietag (ColorSpace) wordt altijd vastgelegd als de kleurruimte-specificatie. |
| COMPONENTS_CONFIGURATION | De componentconfiguratie. |
| COMPRESSED_BITS_PER_PIXEL | Specifiek voor gecomprimeerde data; geeft de gecomprimeerde bits per pixel aan. |
| COMPRESSION | Het compressieschema dat wordt gebruikt voor de beeldgegevens. Wanneer een primaire afbeelding JPEG-gecomprimeerd is, is deze aanduiding niet nodig en wordt weggelaten. |
| CONTRAST | Deze tag geeft de richting van de contrastverwerking aan die door de camera is toegepast toen de foto werd genomen. |
| COPYRIGHT | Copyrightinformatie. In deze standaard wordt de tag gebruikt om<br/>                zowel de copyright van de fotograaf als van de editor aan te geven. Het is<br/>                de copyrightvermelding van de persoon of organisatie die<br/>                rechten op de afbeelding claimt. De interoperabiliteits‑copyright<br/>                verklaring inclusief datum en rechten moet in dit<br/>                veld worden geschreven; bijv., "Copyright, John Smith, 19xx. Alle rechten<br/>                voorbehouden.". In deze standaard registreert het veld zowel de<br/>                copyright van de fotograaf als van de editor, waarbij elk wordt vastgelegd in een<br/>                apart deel van de verklaring. Wanneer er een duidelijk onderscheid is<br/>                tussen de copyright van de fotograaf en de editor, moeten deze<br/>                worden geschreven in de volgorde fotograaf gevolgd door editor‑copyright,<br/>                gescheiden door NULL (in dit geval, aangezien de verklaring ook eindigt met<br/>                een NULL, zijn er twee NULL‑codes). Wanneer alleen de copyright van de fotograaf<br/>                wordt gegeven, wordt deze beëindigd met één NULL‑code. Wanneer alleen<br/>                de editor‑copyright wordt gegeven, bestaat het fotograaf‑copyrightdeel<br/>                uit één spatie gevolgd door een afsluitende NULL‑code, daarna wordt<br/>                de editor‑copyright gegeven. Wanneer het veld leeg wordt gelaten, wordt het<br/>                beschouwd als onbekend. |
| CUSTOM_RENDERED | Deze tag geeft het gebruik van speciale verwerking op beeldgegevens aan, zoals rendering gericht op output. Wanneer speciale verwerking wordt uitgevoerd, wordt van de lezer verwacht dat hij verdere verwerking uitschakelt of minimaliseert. |
| DATE_TIME | De datum en tijd van het maken van de afbeelding. In de Exif-standaard is dit de datum en tijd waarop het bestand werd gewijzigd. |
| DATE_TIME_DIGITIZED | De gedigitaliseerde datum en tijd. |
| DATE_TIME_ORIGINAL | De datum en tijd waarop de oorspronkelijke beeldgegevens werden gegenereerd. |
| DEVICE_SETTING_DESCRIPTION | Deze tag geeft informatie over de opnamecondities van een bepaald cameramodel. De tag wordt alleen gebruikt om de opnamecondities in de lezer aan te geven. |
| DIGITAL_ZOOM_RATIO | Deze tag geeft de digitale zoomverhouding aan toen de afbeelding werd genomen. Als de teller van de geregistreerde waarde 0 is, geeft dit aan dat digitale zoom niet werd gebruikt. |
| EXIF_IFD_POINTER | Een verwijzing naar de Exif IFD. Interoperabiliteit, Exif IFD heeft dezelfde structuur als die van de IFD gespecificeerd in TIFF. Gewoonlijk bevat deze echter geen beeldgegevens, zoals bij TIFF het geval is. |
| EXIF_VERSION | De Exif-versie. |
| EXPOSURE_BIAS_VALUE | De belichtingsbiaswaarde. |
| EXPOSURE_INDEX | Geeft de belichtingsindex aan die op de camera of invoerapparaat is geselecteerd op het moment dat de afbeelding wordt vastgelegd. |
| EXPOSURE_MODE | Deze tag geeft de belichtingsmodus aan die is ingesteld toen de afbeelding werd genomen. In de auto‑bracketing‑modus maakt de camera een reeks beelden van dezelfde scène met verschillende belichtingsinstellingen. |
| EXPOSURE_PROGRAM | De klasse van het programma dat door de camera wordt gebruikt om de belichting in te stellen wanneer de foto wordt genomen. |
| EXPOSURE_TIME | Belichtingstijd, opgegeven in seconden. |
| FILE_SOURCE | De bestandsbron. |
| FLASH | Geeft de status van de flits aan wanneer de foto werd genomen. |
| FLASHPIX_VERSION | De Flashpix-formaatversie die wordt ondersteund door een FPXR-bestand. |
| FLASH_ENERGY | Geeft de strobo-energie op het moment dat de foto wordt vastgelegd, gemeten in Beam Candle Power Seconds (BCPS). |
| FOCAL_LENGTH | De werkelijke brandpuntsafstand van de lens, in mm. |
| FOCAL_LENGTH_IN_35_MM_FILM | Deze tag geeft de equivalente brandpuntsafstand aan, uitgaande van een 35mm filmcamera, in mm. Een waarde van 0 betekent dat de brandpuntsafstand onbekend is. Merk op dat deze tag verschilt van de FocalLength-tag. |
| FOCAL_PLANE_RESOLUTION_UNIT | Geeft de eenheid aan voor het meten van FocalPlaneXResolution en FocalPlaneYResolution. Deze waarde is dezelfde als de ResolutionUnit. |
| FOCAL_PLANE_X_RESOLUTION | Geeft het aantal pixels in de breedte (X) van de afbeelding per FocalPlaneResolutionUnit op het brandpuntsvlak van de camera aan. |
| FOCAL_PLANE_Y_RESOLUTION | Geeft het aantal pixels in de hoogte (Y) van de afbeelding per FocalPlaneResolutionUnit op het brandpuntsvlak van de camera aan. |
| F_NUMBER | Het F-getal. |
| GAIN_CONTROL | Deze tag geeft de mate van algemene beeldversterkingsaanpassing aan. |
| GAMMA | Gamma-waarde |
| GPSDOP | Geeft de GPS DOP (data degree of precision) aan. Een HDOP-waarde wordt geschreven tijdens een tweedimensionale meting,<br/>                en PDOP tijdens een driedimensionale meting. |
| GPS_ALTITUDE | Geeft de hoogte aan op basis van de referentie in GPSAltitudeRef. Hoogte wordt uitgedrukt als één RATIONAL-waarde.<br/>                De referentie-eenheid is meters. |
| GPS_ALTITUDE_REF | Geeft de hoogte aan die wordt gebruikt als referentiehoogte. Als de referentie zeeniveau is en de hoogte boven zeeniveau ligt,<br/>                wordt 0 gegeven. Als de hoogte onder zeeniveau ligt, wordt een waarde van 1 gegeven en wordt de hoogte aangegeven als een absolute waarde in<br/>                de GPSAltitude-tag. |
| GPS_AREA_INFORMATION | Een tekenreeks die de naam van het GPS-gebied vastlegt. Het eerste byte geeft<br/>                de gebruikte tekencode aan, gevolgd door de naam van het GPS-gebied. |
| GPS_DATE_STAMP | Een tekenreeks die datum- en tijdinformatie vastlegt ten opzichte van UTC<br/>                (Coordinated Universal Time). Het formaat is JJJJ:MM:DD. |
| GPS_DEST_BEARING | Geeft de koers naar het bestemmingspunt aan. Het bereik van waarden is van 0,00 tot 359,99. |
| GPS_DEST_BEARING_REF | Geeft de referentie aan die wordt gebruikt voor het aangeven van de koers naar het bestemmingspunt. 'T' duidt de ware richting aan en 'M' is<br/>                magnetische richting. |
| GPS_DEST_DISTANCE | Geeft de afstand naar het bestemmingspunt aan. |
| GPS_DEST_DISTANCE_REF | Geeft de eenheid aan die wordt gebruikt om de afstand naar het bestemmingspunt uit te drukken. 'K', 'M' en 'N' staan voor kilometers, mijlen<br/>                en knopen. |
| GPS_DEST_LATITUDE | Geeft de breedtegraad van het bestemmingspunt aan. De breedtegraad wordt uitgedrukt als drie RATIONAL-waarden die respectievelijk de<br/>                graden, minuten en seconden geven. Als de breedtegraad wordt uitgedrukt in graden, minuten en seconden, is een typisch<br/>                formaat dd/1,mm/1,ss/1. Wanneer graden en minuten worden gebruikt en bijvoorbeeld fracties van minuten<br/>                tot twee decimalen worden gegeven, is het formaat dd/1,mmmm/100,0/1. |
| GPS_DEST_LATITUDE_REF | Geeft aan of de breedtegraad van het bestemmingspunt noordelijk of zuidelijk is. De ASCII-waarde 'N' duidt noordelijke<br/>                breedtegraad aan, en 'S' duidt zuidelijke breedtegraad aan. |
| GPS_DEST_LONGITUDE | Geeft de lengtegraad van het bestemmingspunt aan. De lengtegraad wordt uitgedrukt als drie RATIONAL-waarden die respectievelijk de<br/>                graden, minuten en seconden geven. Als de lengtegraad wordt uitgedrukt in graden, minuten en seconden, is een typisch<br/>                formaat ddd/1,mm/1,ss/1. Wanneer graden en minuten worden gebruikt en bijvoorbeeld fracties van minuten<br/>                tot twee decimalen worden gegeven, is het formaat ddd/1,mmmm/100,0/1. |
| GPS_DEST_LONGITUDE_REF | Geeft aan of de lengtegraad van het bestemmingspunt oostelijk of westelijk is. ASCII 'E' duidt oostelijke lengtegraad aan,<br/>                en 'W' duidt westelijke lengtegraad aan. |
| GPS_DIFFERENTIAL | Geeft aan of differentiële correctie wordt toegepast op de GPS-ontvanger. |
| GPS_IFD_POINTER | De gps ifd-pointer. |
| GPS_IMG_DIRECTION | Geeft de richting van de afbeelding aan op het moment van vastleggen. Het bereik van waarden is van 0,00 tot 359,99. |
| GPS_IMG_DIRECTION_REF | Geeft de referentie aan voor het aangeven van de richting van de afbeelding bij vastlegging. 'T' duidt de ware richting aan en 'M' is<br/>                magnetische richting. |
| GPS_LATITUDE | Geeft de breedtegraad aan. De breedtegraad wordt uitgedrukt als drie RATIONAL-waarden die respectievelijk de graden, minuten en<br/>                seconden aangeven. Als de breedtegraad wordt uitgedrukt in graden, minuten en seconden, zou een typisch formaat zijn<br/>                dd/1,mm/1,ss/1. Wanneer graden en minuten worden gebruikt en bijvoorbeeld fracties van minuten tot twee<br/>                decimalen worden gegeven, zou het formaat dd/1,mmmm/100,0/1 zijn. |
| GPS_LATITUDE_REF | Geeft aan of de breedtegraad noordelijk of zuidelijk is. |
| GPS_LONGITUDE | Geeft de lengtegraad aan. De lengtegraad wordt uitgedrukt als drie RATIONAL-waarden die respectievelijk de graden, minuten en<br/>                seconden aangeven. Als de lengtegraad wordt uitgedrukt in graden, minuten en seconden, zou een typisch formaat zijn<br/>                ddd/1,mm/1,ss/1. Wanneer graden en minuten worden gebruikt en bijvoorbeeld fracties van minuten tot twee<br/>                decimalen worden gegeven, zou het formaat ddd/1,mmmm/100,0/1 zijn. |
| GPS_LONGITUDE_REF | Geeft aan of de lengtegraad oostelijk of westelijk is. |
| GPS_MAP_DATUM | Geeft de geodetische surveydataset aan die door de GPS-ontvanger wordt gebruikt. |
| GPS_MEASURE_MODE | Geeft de GPS-meetmodus aan. - 2- of 3-dimensionaal. |
| GPS_PROCESSING_METHOD | Een tekenreeks die de naam van de gebruikte methode voor locatiebepaling vastlegt.<br/>                Het eerste byte geeft de gebruikte tekencode aan, en dit wordt gevolgd door de naam<br/>                van de methode. |
| GPS_SATELLITES | Geeft de GPS-satellieten aan die voor metingen worden gebruikt. Deze tag kan worden gebruikt om het aantal satellieten,<br/>                hun ID-nummer, elevatiehoek, azimut, SNR en andere informatie in ASCII-notatie te beschrijven. Het formaat is niet<br/>                gespecificeerd. Als de GPS-ontvanger niet in staat is metingen uit te voeren, moet de waarde van de tag op NULL worden gezet. |
| GPS_SPEED | Geeft de snelheid van de GPS-ontvangerbeweging aan. |
| GPS_SPEED_REF | Geeft de eenheid aan die wordt gebruikt om de snelheid van de GPS-ontvangerbeweging uit te drukken. 'K', 'M' en 'N' staan voor kilometers per<br/>                uur, mijlen per uur en knopen. |
| GPS_STATUS | Geeft de status van de GPS-ontvanger weer wanneer de afbeelding wordt vastgelegd. |
| GPS_TIMESTAMP | Geeft de tijd weer als UTC (Coordinated Universal Time). TimeStamp wordt uitgedrukt als drie RATIONAL-waarden<br/>                die het uur, de minuut en de seconde geven. |
| GPS_TRACK | Geeft de richting van de GPS-ontvangerbeweging aan. Het bereik van waarden is van 0.00 tot 359.99. |
| GPS_TRACK_REF | Geeft de referentie aan voor het bepalen van de richting van de GPS-ontvangerbeweging. 'T' staat voor ware richting en 'M' is<br/>                magnetische richting. |
| GPS_VERSION_ID | Geeft de versie van GPSInfoIFD aan. |
| IMAGE_DESCRIPTION | Een tekenreeks die de titel van de afbeelding geeft. Het kan een opmerking zijn, zoals "1988 company picnic" of iets dergelijks. |
| IMAGE_LENGTH | Het aantal rijen van afbeeldingsgegevens. |
| IMAGE_UNIQUE_ID | De unieke ID van de afbeelding. |
| IMAGE_WIDTH | Het aantal kolommen van afbeeldingsgegevens, gelijk aan het aantal pixels per rij. |
| ISO_SPEED | Informatie over de ISO-snelheidswaarde zoals gedefinieerd in ISO 12232. |
| ISO_SPEED_LATITUDE_YYY | Deze tag geeft de ISO-snelheidsbreedtegraad yyy-waarde aan zoals gedefinieerd in ISO 12232. |
| ISO_SPEED_LATITUDE_ZZZ | Deze tag geeft de ISO-snelheidsbreedtegraad zzz-waarde aan zoals gedefinieerd in ISO 12232. |
| JPEG_INTERCHANGE_FORMAT | De offset naar het startbyte (SOI) van JPEG-gecomprimeerde miniatuurgegevens. Dit wordt niet gebruikt voor de primaire JPEG-beeldgegevens. |
| JPEG_INTERCHANGE_FORMAT_LENGTH | Het aantal bytes van JPEG-gecomprimeerde miniatuurgegevens. Dit wordt niet gebruikt voor de primaire JPEG-beeldgegevens. JPEG-miniaturen worden niet opgesplitst maar worden vastgelegd als een doorlopende JPEG-bitstream van SOI tot EOI. Appn- en COM-markeringen mogen niet worden vastgelegd. Gecomprimeerde miniaturen moeten worden vastgelegd in niet meer dan 64 Kbytes, inclusief alle andere gegevens die in APP1 moeten worden vastgelegd. |
| LENS_MAKE | Dit label registreert de lensfabrikant |
| LENS_MODEL | Dit label registreert de modelnaam en het modelnummer van de lens |
| LENS_SERIAL_NUMBER | Dit label registreert het serienummer van verwisselbare lenzen |
| LENS_SPECIFICATION | Dit label noteert de minimale brandpuntsafstand, maximale brandpuntsafstand, het minimale f-getal bij de minimale brandpuntsafstand en het minimale f-getal bij de maximale brandpuntsafstand |
| LIGHT_SOURCE | Het type lichtbron. |
| MAKE | De fabrikant van de opnameapparatuur. Dit is de fabrikant van de DSC, scanner, video-digitaliser of andere apparatuur die de afbeelding heeft gegenereerd. Wanneer het veld leeg wordt gelaten, wordt het beschouwd als onbekend. |
| MAKER_NOTE | Een label voor fabrikanten van Exif-schrijvers om gewenste informatie vast te leggen. De inhoud is aan de fabrikant, maar dit label mag niet voor andere doeleinden dan het beoogde worden gebruikt. |
| MAX_APERTURE_VALUE | De maximale diafragmawaarde. |
| METERING_MODE | De meetmodus. |
| MODEL | De modelnaam of het modelnummer van de apparatuur. Dit is de modelnaam of het modelnummer van de DSC, scanner, video-digitaliser of andere apparatuur die de afbeelding heeft gegenereerd. Wanneer het veld leeg wordt gelaten, wordt het beschouwd als onbekend. |
| OECF | Geeft de Opto-Electrische Conversiefunctie (OECF) aan zoals gespecificeerd in ISO 14524. |
| ORIENTATION | De beeldoriëntatie bekeken in termen van rijen en kolommen. |
| PHOTOGRAPHIC_SENSITIVITY | Geeft de ISO-snelheid en ISO-latitude van de camera of invoerapparaat aan zoals gespecificeerd in ISO 12232. |
| PHOTOMETRIC_INTERPRETATION | De pixelcompositie. |
| PIXEL_X_DIMENSION | Informatie specifiek voor gecomprimeerde gegevens. Wanneer een gecomprimeerd bestand wordt vastgelegd, moet de geldige breedte van de betekenisvolle afbeelding in deze tag worden vastgelegd, ongeacht of er opvulgegevens of een herstartmarker aanwezig is. |
| PIXEL_Y_DIMENSION | Informatie specifiek voor gecomprimeerde gegevens. Wanneer een gecomprimeerd bestand wordt vastgelegd, moet de geldige hoogte van de betekenisvolle afbeelding in deze tag worden vastgelegd. |
| PLANAR_CONFIGURATION | Geeft aan of pixelcomponenten worden vastgelegd in een chunky- of planarformaat. Als dit veld niet bestaat, wordt de TIFF-standaardwaarde van 1 (chunky) aangenomen. |
| PRIMARY_CHROMATICITIES | De chromaticiteit van de drie primaire kleuren van de afbeelding. Normaal is deze tag niet nodig, aangezien de kleurenruimte wordt gespecificeerd in de kleurenruimte-informatietag ColorSpace. |
| RECOMMENDED_EXPOSURE_INDEX | Geeft de aanbevolen belichtingsindex aan |
| REFERENCE_BLACK_WHITE | De referentie zwartpuntwaarde en referentie witpuntwaarde<br/>                waarde. Er worden geen standaardwaarden gegeven in TIFF, maar de onderstaande waarden worden hier als standaard opgegeven.<br/>                De kleurenruimte wordt gedeclareerd<br/>                in een kleurenruimte-informatietag, met de standaard<br/>                die de waarde is die de optimale afbeeldingskenmerken geeft<br/>                Interoperabiliteit onder deze voorwaarden |
| RELATED_SOUND_FILE | Het gerelateerde geluidsbestand. |
| RESOLUTION_UNIT | De eenheid voor het meten van XResolution en YResolution. Dezelfde eenheid wordt gebruikt voor zowel XResolution als YResolution. Als de afbeeldingsresolutie onbekend is, wordt 2 (inches) aangewezen. |
| ROWS_PER_STRIP | Het aantal rijen per strip. Dit is het aantal rijen in de afbeelding van één strip wanneer een afbeelding in strips wordt verdeeld. |
| SAMPLES_PER_PIXEL | Het aantal componenten per pixel. Aangezien deze standaard van toepassing is op RGB- en YCbCr-afbeeldingen, is de voor deze tag ingestelde waarde 3. |
| SATURATION | Deze tag geeft de richting van de verzadigingsverwerking aan die door de camera is toegepast toen de afbeelding werd gemaakt. |
| SCENE_CAPTURE_TYPE | Deze tag geeft het type scène aan dat is gefotografeerd. Het kan ook worden gebruikt om de modus waarin de afbeelding is gemaakt vast te leggen. |
| SCENE_TYPE | Geeft het type scène aan. Als een DSC de afbeelding heeft vastgelegd, moet deze tagwaarde altijd op 1 worden gezet, wat aangeeft dat de afbeelding direct is gefotografeerd. |
| SENSING_METHOD | Geeft het type beeldsensor op de camera of invoerapparaat aan. |
| SENSITIVITY_TYPE | Type van fotografische gevoeligheid |
| SHARPNESS | Deze tag geeft de richting aan van de scherpteverwerking die door de camera is toegepast toen de foto werd genomen |
| SHUTTER_SPEED_VALUE | De sluitertijdwaarde. |
| SOFTWARE | Deze tag registreert de naam en versie van de software of firmware van de camera of het beeldinvoerapparaat dat is gebruikt om de afbeelding te genereren. Het gedetailleerde formaat is niet gespecificeerd, maar het wordt aanbevolen het onderstaande voorbeeld te volgen. Wanneer het veld leeg wordt gelaten, wordt het beschouwd als onbekend. |
| SPATIAL_FREQUENCY_RESPONSE | Deze tag registreert de ruimtelijke frequentietabel van de camera of het invoerapparaat en SFR-waarden in de richting van de beeldbreedte, beeldhoogte en diagonale richting, zoals gespecificeerd in ISO 12233. |
| SPECTRAL_SENSITIVITY | Geeft de spectrale gevoeligheid van elk kanaal van de gebruikte camera aan |
| STANDARD_OUTPUT_SENSITIVITY | Geeft de standaard uitgangsgevoeligheid van de camera aan |
| STRIP_BYTE_COUNTS | Het totale aantal bytes in elke strip. |
| STRIP_OFFSETS | Voor elke strip de byte-offset van die strip. Het wordt aanbevolen dit zo te kiezen dat het aantal stripbytes niet hoger is dan 64 Kbytes.<br/>                Aux tag. |
| SUBJECT_AREA | Deze tag geeft de locatie en het gebied van het hoofdonderwerp in de algehele scène aan |
| SUBJECT_DISTANCE | De afstand tot het onderwerp, opgegeven in meters. |
| SUBJECT_DISTANCE_RANGE | Deze tag geeft de afstand tot het onderwerp aan |
| SUBJECT_LOCATION | Geeft de locatie van het hoofdonderwerp in de scène aan. De waarde van deze tag vertegenwoordigt de pixel in het midden van het hoofdonderwerp ten opzichte van de linkerrand, vóór rotatieverwerking volgens de Rotation-tag. |
| SUBSEC_TIME | Een tag die wordt gebruikt om fracties van seconden vast te leggen voor de DateTime-tag. |
| SUBSEC_TIME_DIGITIZED | Een tag die wordt gebruikt om fracties van seconden vast te leggen voor de DateTimeDigitized-tag. |
| SUBSEC_TIME_ORIGINAL | Een tag die wordt gebruikt om fracties van seconden vast te leggen voor de DateTimeOriginal-tag. |
| TRANSFER_FUNCTION | Een overdrachtsfunctie voor de afbeelding, beschreven in tabelvorm. Normaal is deze tag niet nodig, aangezien de kleurenruimte wordt gespecificeerd in de kleurruimte‑informatie ColorSpace tag. |
| USER_COMMENT | Een tag voor Exif‑gebruikers om trefwoorden of opmerkingen bij de afbeelding te schrijven, naast die in ImageDescription, en zonder de tekencode‑beperkingen van de ImageDescription-tag. |
| WHITE_BALANCE | Deze tag geeft de witbalansmodus aan die is ingesteld toen de afbeelding werd genomen. |
| WHITE_POINT | De chromaticiteit van het witpunt van de afbeelding. Normaal is deze tag niet nodig, aangezien de kleurenruimte wordt gespecificeerd in de kleurenruimte‑informatie ColorSpace tag. |
| X_RESOLUTION | Het aantal pixels per ResolutionUnit in de ImageWidth-richting. Wanneer de afbeeldingsresolutie onbekend is, wordt 72 [dpi] aangewezen. |
| Y_CB_CR_COEFFICIENTS | De matrixcoëfficiënten voor de transformatie van RGB naar YCbCr-beeldgegevens. |
| Y_CB_CR_POSITIONING | De positie van chrominantie‑componenten ten opzichte van de<br/>                luminantie‑component. Dit veld is alleen bedoeld voor<br/>                JPEG‑gecomprimeerde gegevens of ongecomprimeerde YCbCr‑gegevens. De TIFF<br/>                standaard is 1 (gecentreerd); maar wanneer Y:Cb:Cr = 4:2:2 is het<br/>                volgens deze norm aanbevolen om 2 (naast elkaar) te gebruiken om<br/>                gegevens vast te leggen, om de beeldkwaliteit te verbeteren bij weergave<br/>                op tv‑systemen. Wanneer dit veld niet bestaat, moet de lezer<br/>                de TIFF‑standaard aannemen. In het geval van Y:Cb:Cr = 4:2:0, wordt de<br/>                TIFF‑standaard (gecentreerd) aanbevolen. Als de lezer<br/>                niet de mogelijkheid heeft om beide soorten<br/>                YCbCrPositioning te ondersteunen, moet hij de TIFF‑standaard volgen ongeacht<br/>                de waarde in dit veld. Het is wenselijk dat lezers "<br/>                zowel gecentreerde als naast‑elkaar positionering kunnen ondersteunen. |
| Y_CB_CR_SUB_SAMPLING | De bemonsteringsratio van chrominantie‑componenten ten opzichte van de luminantie‑component. |
| Y_RESOLUTION | Het aantal pixels per ResolutionUnit in de ImageLength-richting. Dezelfde waarde als XResolution wordt aangewezen. |
