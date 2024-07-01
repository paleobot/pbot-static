# Collection Node
## Instructions for data entry
PBot uses the concept of Collections, as implemented and required by the Paleobiology Database (PBDB), in order for our databases to exchange information. Collections are how PBot records the geographical, geological, and sampling data for specimens (and by extension, taxa). We can think of a “Collection” as a sample of fossils from a distinct location and stratum that was collected in a known time-frame using a particular method.  Each specimen in PBot must be linked to one Collection. See the general comments below for important information on delineating collections. 

**General comments on Collections:** *This section is very important. Please read all of it very carefully. We follow the policies and guidelines established by the PBDB, who provided much of the text below. For more information about collections in PBDB, see https://paleobiodb.org/public/tips/tips.html.*
* A geographic locality or stratigraphic level may include many Collections. For example, if fossils were collected from multiple quarry holes at a locality, whether that be from multiple stratigraphic horizons or from laterally sampling one fossiliferous bed, each quarry hole should be a unique Collection. Likewise, if two papers describe material clearly, entirely collected at completely different times from the same place, make two Collection records. We can always lump such records later when we do analyses; we cannot separate out such collections if they have been lumped during data entry. Lumping collections destroys data.
* However, don't split every paper as a new Collection record. A "Collection" is any set of fossils whose exact geographic and stratigraphic position and date of collection cannot be distinguished, regardless of when they were described, and by whom. So, if five people describe five new, unrelated species/morphotypes in five different papers, don't make five Collection records unless different physical collections from different places and/or strata are involved. 
* **Never** make a new Collection record just because you (or your research team) did not create the existing record for the same actual hole in the ground. Instead, add specimens to the existing Collection record.
* The Collection record represents our best current knowledge about the Collection. So, if the original paper said "Eocene" but a later paper narrowed the age to "Middle Eocene," enter "Middle Eocene" as the time interval. Both references need to be associated with the collection, which you do by adding the new Reference to the collection.

**Prior to creating a new Collection, please determine whether the Collection already exists in the Paleobiology Database.** From the PBot Collections Form, enter the latitude and longitude of the Collection, and then click the magnifying glass next to the PBDB ID field. If the Collection exists in PBDB, first select “Populate all fields,” and then click on the Collection to autopopulate the data into the PBot Collections Form. Enter any additional collection information in the PBot Collection Form and then submit.

## REQUIRED FIELDS:
**Name** – A unique identification that may also aid in recognizing close links among Collections. 80 character limit. For example, if you are entering a series of consecutive beds, you could provide a location name and meter level (e.g., “Saddle Mountain 1.5 meter bed” and “Saddle Mountain 2.0 meter bed”). Keep it short: do not include the stratigraphic age, location details, or the name of the formation, country, state, etc.

**Collection type** – Characterize the intent or subject area of the part of the original publication from which the Collection was compiled. Be careful because different parts of one paper might have different purposes. When in doubt, use the category that best describes the whole paper.
* **Archaeologic** means collected for archaeologically focused research.
* **Biostratigraphic** means described for the purpose of temporal correlation, or in the course of a geological study (e.g., lists given within descriptions of measured sections). 
* **Paleoecologic** means described for the purpose of paleoecological analysis, including taxonomic lists that are given without descriptions of fossils and without discussions of temporal correlation. 
* **Taphonomic** means described for the purpose of a taphonomic analysis. 
* **Taxonomic** means a systematic paleontology treatment, including simple descriptions of fossils. Use this if all the taxa are included in a systematic paleontology section, or if the taxonomic list is given only in support of an otherwise taxonomic account of one or a few taxa. 
* **General faunal/floral** means there is no detailed discussion of the age, environment, ecology, preservation, or morphology of the fossils, but a taxonomic list is given. Use this category only if the other ones are too specific.

**Latitude and Longitude** – The present-day latitude and longitude (as opposed to paleolatitude or paleolongitude) in decimal degrees. **All coordinates must use the WGS84 coordinate system.** Latitude values range from -90 to 90, inclusive, with positive values north of the Equator and negative values south of it. Longitude values range from -180 to 180, inclusive, with positive values east of the Greenwich Meridian and negative values west of it. 

Please enter coordinates to the highest degree of precision possible, in accordance with rules, regulations, and courtesies regarding fossil locality data. It is your responsibility to determine the sensitivity of your data and enter coordinates accordingly. The Society of Vertebrate Paleontology recommends reporting to 0.1 degrees for high sensitivity, 0.01 degrees for medium sensitivity, 0.001 degrees for low sensitivity, and as many decimal points as possible for non-sensitive data (see full SVP recommendations [here](https://vertpaleo.org/wp-content/uploads/2021/01/SVP-Paleo-Best-Practice-Guidlines-2nd-Ed.pdf)).

**GPS coordinate uncertainty** – The radius of uncertainty, in meters, for the GPS coordinates entered. Coordinates may be uncertain due to accuracy-level of a handheld GPS (5 m uncertainty), inability to precisely locate a historic collection (e.g., only a county or township, range, and section are given), or the need to report lower resolution coordinates by law or request of a property owner. For reference, if you are reporting coordinates to 0.1 degree resolution, your radius of uncertainty would be 5550 m.

We have included additional resources for latitude, longitude, and coordinate uncertainty at the end of this cheat sheet.

**Country** – Select the present-day country in which the Collection occurs from the dropdown menu. 

**Protected site** – Check this box to indicate that the site location and access to it is restricted. Remember, it is your responsibility to enter GPS coordinates at the appropriate resolution.  

**Timescale, maximum, and minimum interval** – The zone, age/stage, epoch, or period from which your Collection is drawn. First, select the most precise timescale you can from the “Timescale” dropdown menu (e.g., international epochs rather than international periods). Your choice will populate a drop-down menu for the “Maximum interval” field. After you make a selection, that value will automatically populate the “Minimum interval” field. If a collection is known to span, or could span, multiple intervals, change the “Minimum interval” entry to the correct minimum.

**Lithology** – The lithology that makes up most of the exposure (for an outcrop) or part of the core that was studied (for a sample from a core). If it is not clear which lithology dominates, choose the first one listed in the publication. See the Paleobiology Database lithology [tip sheet](https://paleobiodb.org/public/tips/lithtips.html) for explanations of lithologic terms.

**Preservation modes** – The kind(s) of fossils that are present. Select as many as apply to any of the fossils in the Collection. We define the fossil types as follows:
* **Adpression/Compression:** 2D fossil in which original organic material remains, although often in a * geochemically altered state. This category includes carbonization fossils.
* **Body:** remains of the body itself
* **Cast:** none of the original biomineralized or organic tissue preserved; 3D fossil that is a positive image of the original
* **Charcoalification:** near-perfect, often cellular-level, preservation of plant organs (most commonly wood, leaves, or reproductive organs) as charcoal.
* **Coalified:** vegetative material has been converted to coal.
* **Concretion:** Mazon Creek nodules are examples of concretions.
* **Mold/impression:** none of the original biomineralized or organic tissue preserved; Impressions are 2D fossils, and molds are 3D fossils that are the negative image of the original.
* **Permineralization:** 3D infilling of intracellular spaces with carbonates, iron compounds, pyrite, silicates, etc. Coal balls and petrified wood are examples of permineralized fossils.
* **Recrystallized:** 3D fossil in which the original tissue is replaced by a mineral.
* **Trace:** evidence of behavior, such as feeding damage, coprolites, or trackways

**Size classes** – PBDB requires that Collections include which size classes of fossils have been recovered. Your options are > 10 mm, 1-10 mm, or < 1 mm, and multiple options can be selected.

**Paleobiology Database ID** – From the PBot Collections Form, search the Paleobiology Database to determine if your Collection has been entered there. You must do this search in order to submit the Collections Form. The Paleobiology Database ID is PBDB’s Collection ID number, and it will be automatically filled in if you click on a PBDB Collection in the PBot search results. If the Collection does not exist already in PBDB, this field may be left blank.

**References** – Select one or more References that describe the Collection. References must already exist in PBot and can include unpublished references (temporary placeholders for personal workbenches and unpublished collections). Multiple References can be associated with a Collection by clicking “ADD REFERENCE”. Enter the order number for the Reference to indicate its priority in the reference list, with the most relevant publication as order 1.

**Public or Group** – The default is for a Collection to be Public, as published collections should always be part of the “Public” access group. If you would like to restrict access to an unpublished site, uncheck “Public”  and select which one or more of your private groups can access this collection. Once a record has been made public, it cannot be returned to a private group. Note that protecting the geographic location of a published locality should be done by making your gps coordinates “fuzzy” and checking the “Protected site” box, not by making the whole collection record private.

## OPTIONAL FIELDS: GEOGRAPHIC
**State/province** – A required field if the country is the USA. Elsewhere, its use is also encouraged (e. g., England is a "state" of the United Kingdom, Ontario is a province of Canada).

**Scale of geographic resolution** – From the drop-down menu, select the resolution that best characterizes your Collection. Err on the side of conservatism: if you know the Collection is from a particular roadcut but don't know if it does or doesn't come from a small excavation within the roadcut, enter "outcrop" instead of "small collection." If no information is given, do not make a selection. Terms are defined as follows: 
* **small collection:** from an area < 10 x 10 m, e.g., a single fossil, an individual bulk sample, or a small quarry 
* **outcrop:** from an area < 1 x 1 km, e.g., a large quarry, road cut, or wash 
* **local area:** from an area < 100 x 100 km, e.g., approximately a one-by-one degree lat/long rectangle or the size of most individual counties in the USA 
* **basin:** from any area > 100 x 100 km

**Notes on geographic information** – Provide any additional information that you think is important with respect to the geographic location of the Collection.

## OPTIONAL FIELDS: AGE
**Direct date, Numeric maximum age, Numeric minimum age** – Use these fields for numerical age estimates based on actual measurements of rocks and fossils in the actual horizons only (i.e., Collection is associated with a specific geochron measurement). Do not enter guesstimates or values derived from time scales (e.g., a range derived from the Gradstein et al. boundaries for a global stage). These fields should not be filled in if a collection can only be assigned to a Period, Epoch, Age, or Series. Do not enter values that the author does not believe to be reliable (say, because the sample might be contaminated). There are three kinds of dates:
* Direct date means a date for the exact horizon yielding the Collection. If one single direct date is given you should enter it instead of any maximum and/or minimum dates. Also, if there is a minimum but no maximum or vice versa, it would be better to enter a direct date.
* Numeric maximum age could mean one of two things: (1) the oldest of several direct dates (enter the youngest in the minimum field), or (2) the oldest date for the highest underlying stratigraphic horizon. For example, if the fossils are from unit 7 and there are dates for units 4 and 5, enter the youngest date for unit 5.
* Numeric minimum age means the youngest direct date or youngest date for the lowest overlying horizon.

**Notes on age information** – Provide any additional information that you think is important with respect to the age of the Collection.

## OPTIONAL FIELDS: GEOLOGIC
**Additional description of lithology** – Quote the entire description of the lithology if it includes any information you can't record in the other fields of this section or in the required “Lithology” field. Even if there is just a word difference like "carbonate" vs. "lime," the description should be quoted in full.

**Stratigraphy: Geologic group, formation, member, bed, notes on stratigraphy** – Names of stratigraphic units yielding fossils. Always enter the formation name if it is available. Important: Only provide the name of the stratigraphic unit- do not put the terms “group”, “formation”, “fm.”, “member”, or “mbr.” In these fields. Provide any additional information that you think is important with respect to the stratigraphic delineation of the collection in the “Notes on stratigraphy” field.

**Environment** – The depositional environment (or paleoenvironment). Select the most exact environmental category you can figure out. Each section of the pulldown includes some generalized “indet.” terms that you should use only if a more precise determination is not possible. For more information and full definitions of each environmental setting, see the Paleobiology Database [Environmental Tips](https://paleobiodb.org/public/tips/environtips.html).

**Notes on environment** – Provide any additional information, including extensive quotes from the paper, that you used to figure out these values. Don't leave this field blank unless the paper very specifically assigned the Collection to an environmental category that exactly corresponds to the ones we use.

## OPTIONAL FIELDS: COLLECTING
**Collectors** – The names of the people who collected the fossils, including the Reference’s authors if appropriate. Separate names by commas and do not write out "and." Example: J. Doe, J. Smith, J. Brown

**Collection methods** – The methods used to make the Collection. Multi-select is allowed, and you should check both "bulk" and "sieve" for wet or dry screen-washed collections.
* **bulk:** the fossils in a set volume of rock, or on an all surfaces of slabs of rock, were identified. This is the appropriate selection for comprehensive census surveys of fossils.
* **sieve:** the fossils were put through a screen or sieve either in the field or in the lab.
* **core:** the fossils came from a core, regardless of whether all material was identified.
* **quarrying:** a trench, pit, or quarry was dug to collect the fossils, but not everything was necessarily identified (if it was, then call it a bulk collection).
* **surface (float):** loose fossils were picked up at the surface.
surface (in situ): fossils were found embedded in the rock but no extensive quarrying or coring was done to collect them.
* **salvage:** some fossils, but not all, were collected during an excavation intended for some other purpose (e.g., construction).
* **anthill:** fossils were picked from the debris on the tops of anthills.

**Notes on collection methods** – Provide as much additional information as possible. Examples: only dicot leaves were identified; specimens were collected from a spoil pile; the quarry was discovered by Doe and excavated by Smith and Brown; the USNM museum collection was made in 1940 and the AMNH museum collection in 1941.

## EXTENDED INSTRUCTIONS FOR ENTERING LATITUDE & LONGITUDE:
Decimal degree digits – What digits mean in latitude and longitude decimal degrees using WGS84. The decimal degree explanations below were adapted from StackExchange on 08-15-2023. Please note the phrase “up to” in these explanations refers to variations in decimal degree distances around the globe. The explanations here refer to the maximum distance represented by a decimal degree digit. To correct for variation and obtain high precision in decimal degree distance, see latitude and longitude at the end of this document. 
* The **tens digit** gives a position up to about 1,000 kilometers. It gives us useful information about what continent or ocean we are on.
* The **units digit** (one decimal degree) gives a position up to 111 kilometers (60 nautical miles, about 69 miles). It can tell us roughly what large state or country we are in.
* The **first decimal place** gives a position up to 11.1 km: it can distinguish the position of one large city from a neighboring large city.
* The **second decimal place** gives a position up to 1.1 km: it can separate one town from the next.
* The **third decimal place** gives a position up to 110 m: it can identify a large agricultural field or institutional campus.
* The **fourth decimal place** gives a position up to 11 m: it can identify a parcel of land. It is comparable to the typical accuracy of an uncorrected GPS unit with no interference.
*The **fifth decimal place** gives a position up to 1.1 m: it distinguishes trees from each other. Accuracy to this level with commercial GPS units can only be achieved with differential correction. 
* The **sixth decimal place** gives a position up to 0.11 m: you can use this for laying out structures in detail, for designing landscapes, building roads. It should be more than good enough for tracking movements of glaciers and rivers. This can be achieved by taking painstaking measures with GPS, such as differentially corrected GPS.

Degrees, minutes, and seconds (DMS) digits – What digits mean in DMS versus decimal degrees using WGS84. The DMS explanations below were adapted from USGS.gov on 10-10-2023. The guide provided can be used to conserve the precision of latitude and longitude reported using DMS to the same level of precision using decimal degrees. Consider all contextual information when estimating radius of uncertainty.
* One degree of latitude equals approximately 110,947 m, one minute equals approximately 1850 m, and one second equals approximately 31 m. 
* One degree of longitude equals approximately 87,843 m, one minute equals approximately 1463 m, and one second equals approximately 24 m. 
* To convert latitude and longitude precision from DMS to decimal degrees, consider the following guide. Use the DMS column on the left to determine how many decimals to report using decimal degrees.<br>

| DMS        | decimal degrees          |
| :-------------: |:-------------:|
| 0°0’      | 0.0 |
|0°0’0”|0.01|
|0°0’0.0”|0.001|
|0°0’0.00”|0.0001|
|0°0’0.000”|0.00001|
|0°0’0.0000”|0.000001|

**Latitude** – Latitude distances are fairly consistent around the globe. The distance of one degree of latitude varies from 111.964 km at the poles to 110.574 km at the equator, a difference of 1,120 m. A calculator to constrain the exact distance of one degree of latitude or longitude at any latitude is provided by the U.S. Government's National Geospatial-Intelligence Agency (NGA).

**Longitude** – Longitude distances vary more substantially. One degree of longitude varies from 0.00 km at the poles to 111.320 km at the equator, a difference of 111,320 m. A calculator to constrain the exact distance of one degree of latitude or longitude at any latitude is provided by the U.S. Government's National Geospatial-Intelligence Agency (NGA).
