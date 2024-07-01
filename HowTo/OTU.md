# Operational Taxonomic Unit (OTU) Node
## Instructions for data entry
PBot uses the concept of an Operational Taxonomic Unit (OTU) for data entry of fossil taxa. The use of OTUs is a practical one, as it provides flexibility for users by allowing the database to accommodate both formally named Linnaean-style fossil taxa (i.e., Latin binomials), informal taxa such as morphotypes, and even working descriptions (see Cleal and Thomas 2010 & 2021 for nice background on “fossil-taxa” and the International Code of Nomenclature). In practice here, an OTU should represent a distinct entity that can be defined and differentiated from other fossil taxa based on a set of descriptive features.  As such, an OTU should be considered as the finest-scale taxonomic rank that is possible given the parts preserved and mode of preservation. Ideally, this is at the level of a fossil-species, however with the understanding that taxonomic resolution can differ among plant fossils so that taxonomic rank for different plant parts of preservation modes are not necessarily equivalent. An OTU should not, therefore, be erected in PBot for a taxonomic rank such as family or order when there are described/named taxa at lower rank. 

## REQUIRED FIELDS:
**Name** – Provide a unique name for the Operational Taxonomic Unit. If it is a validly published taxon, the name would be its full binomial (genus + specific epithet).  Informal or unpublished taxa can use any operational name, provided the name is unique. 

**Authority** – The authority for the OTU, following ICN rules if the OTU is a validly named taxon or if the OTU is an informal taxon then the authority is the person, or groups of persons, describing the taxon.
	
**Parts preserved** – Select the organs or parts of the plant that are described by the OTU diagnosis and description. 

**Diagnosis** – The diagnosis for the taxon. The diagnosis should be a concise statement of the diagnostic features of the taxon that differentiate it from other similar taxa. Note that this field can be used to capture important diagnostic features that may not yet be adequately covered in available character schemas. If the OTU is a published named taxon, paste the verbatim diagnosis from the publication. 
	
**Quality index** – Choose from High, Medium, Low to indicate the author’s confidence level that this OTU represents a valid distinct taxon. For example, based on the specimens and their preservation, how confident are you that this is a distinct OTU? Are there enough diagnostic characters? Importantly, this field is not meant to convey uncertainty in the taxonomic assignment (e.g., what family/genus/etc.); taxonomic uncertainty should be written into the Notes field with explanation. 

We recommend using the Morphotype Quality Index (MQI) of Johnson (1989) and Arens and Allen (2014) to determine the PBot Quality Index as follows:
* High: at least 2 well-preserved and/or whole specimens (MQI of 1 or 2) 
* Medium: one whole or partial well-preserved specimen (MQI of 3)
* Low: specimens are poorly preserved; may be one or more whole or partial specimens (MQI of 4 or 5)

The Exemplar Quality Index (EQI) of Wilson et al. (2021) (modified from the holomorphotype quality index of Ash 1999 and Ellis et al. 2009) may be useful to determine what constitutes a “well-preserved” specimen. This metric was developed for ‘dicot’ leaves, but could be easily expanded and applied to other fossil types. Wilson et al. (2021) chose five features to assess the completeness of each specimen (base, apex, margin, third-order venation, fourth-order venation), and the EQI is simply the number of these features present on a specimen (1-5). Wilson et al. (2021) considered a score above 3 to be “well-preserved.”

It is critical for the quality index to be consistent across fossil sites and formations. The highest quality OTU at a site with moderate preservation may only warrant a Medium score for quality index. 

**Major taxon group** – Choose the group to which this OTU belongs from the dropdown. Although many of these are informal groups, they are useful for searching and sorting data within PBot. 	

**PBDB parent taxon** – Type the most resolved taxon to which this OTU belongs.  This field is used to coordinate taxon records between PBDB and PBot. When you click elsewhere on the page after entering a taxon name, that name will be checked against the taxonomic hierarchy in PBDB; if it does not exist in PBDB you will be notified, at which point you can enter the next higher taxon (or, if you are a registered PBDB data enterer, go add the taxon to PBDB’s taxonomic hierarchy). For example, for a named binomial taxon, if the genus or species names are not in PBDB, then you should type the Family name, if known, or next higher order. For informal taxa, use the most resolved higher order taxon possible. In the absolute worst-case scenario for an incertae sedis morphotype, this entry would be Plantae. The taxonomic levels above your entered parent taxon will be automatically applied according to PBDB’s hierarchy. You can search the PBDB taxonomic hierarchy here:  https://paleobiodb.org/classic/checkTaxonInfo 

**References** – Choose an existing Reference, or References, for the OTU. For a published taxon, this should be the publication(s) that describe and, if applicable, revise a taxon.  For an unpublished taxon, use a personal ‘working reference’ (see Reference instruction sheet). Enter the order number for the Reference to indicate its priority in the reference list, with the most recent descriptive publication on which the taxon is based as order 1. 

**Identified specimens** – Add one or more Specimens that have been identified as belonging to the OTU. This can include the specimens that were used to originally describe the OTU, as well as specimens later identified as the OTU. Add the first Specimen by selecting from the drop-down list or by using the search tool. Additional Specimens are added by clicking “ADD IDENTIFIED SPECIMEN”. 

**Type specimens** – Choose the subset of specimens from the ‘Identified specimens’ that are considered the type specimens of any sort (holotype, paratypes, syntypes, etc.). For unpublished taxa, these are the exemplar specimens equivalent to type specimens. Note that you can designate which of these is the holotype in the Optional Fields below. 

**Public or Group** – For public data, check the box. For private data, uncheck the box, then from the Groups dropdown select the private data access groups to which this data record belongs. Note that a public OTU must have a public holotype/exemplar specimen. Once a record has been made public, it cannot be returned to a private group.

## OPTIONAL FIELDS:
**Holotype specimen** – Choose the Holotype or “Holo-Exemplar” specimen from the list of type specimens. 

**Family** – Type the family to which the OTU belongs, if known. This is particularly important if the family was not available in the PBDB list and will help with updating the PBDB later. 

**Genus** – Type the genus, if known. 

**Plant Fossil Names genus link** – If available, add the direct link to the genus record in the Plant Fossil Names Registry (https://www.plantfossilnames.org).

**Specific epithet** – Type the specific epithet, if known. 

**Plant Fossil Names species link** – If available, add the direct link to the species record in the Plant Fossil Names Registry (https://www.plantfossilnames.org).

**Additional Clades** – Type any additional clades or groups (formal or informal) that you would like to record for the OTU. This field allows the database to capture taxonomic information that is not in PBDB. Separate names with a comma. 

**Notable features preserved** – Choose from the list any notable aspects of the OTU that are known to be preserved.

**Notes** – Enter notes about the OTU that the describer or enterer deems necessary to record. This can include uncertainties about the taxonomy or description, notes on the validity of the taxon or needed revisions that have not been published, etc. In your private access groups, this field can be used for research notes and memos to your collaborators; you may edit or delete such notes before making the OTU record public. 

## Works Cited
Arens, N.C., and Allen, S.E. 2014. A florule from the base of the Hell Creek Formation in the type area of eastern Montana: Implications for vegetation and climate. Geol. Soc. Am. Spec. Pap. 503: 173–207. doi:10.1130/2014.2503(06).

Ash, A.W., Ellis, B., Hickey, L.J., Johnson, K.R., Wilf, P., and Wing, S.L. 1999. Manual of Leaf Architecture: Morphological Description and Categorization of Dicotyledonous and Net-Veined Monocotyledonous Angiosperms. Smithsonian Institution, Washington, D.C.

Cleal, C.J., and Thomas, B.A. 2010. Botanical nomenclature and plant fossils. Taxon 59(1): 261–268. doi:10.1002/tax.591024.

Cleal, C.J., and Thomas, B.A. 2021. Naming of parts: the use of fossil-taxa in palaeobotany. Fossil Imprint 77(1): 166–186.

Ellis, B., Daly, D., Hickey, L.J., Johnson, K.R., Mitchell, J., Wilf, P., and Wing, S.L. 2009. Manual of Leaf Architecture. Cornell University Press, Ithica, New York, USA.

Johnson, K.R. 1989. High-resolution megafloral biostratigraphy spanning the Cretaceous–Tertiary boundary in the northern Great Plains. Yale University.
