# Specimen Node
## Instructions for data entry
Specimen nodes track data about individual specimens and can be linked to the Operational Taxonomic Unit to which they are identified. The geographical, geological, and sampling information about specimens are recorded in the Collection to which a Specimen belongs. Please be sure the relevant Collection has been entered or imported in PBot before entering a Specimen (see Collection instructions). Specimens will “inherit” the privacy status (i.e., whether they are public or in a private access group) from the status of the collection to which they belong. Any Descriptions or Images attributed to a Specimen can be private, regardless of whether the Specimen is public.  

PBot does check internally for duplicates when you submit a new Specimen Node, but the Specimen Name must exactly match the current PBot entry, including capitalization. The best practices to prevent duplicates are follow best practices for Specimen Names (see below) and to check existing Specimens before entering new data.

## REQUIRED FIELDS: 
**Name** – Provide a unique name for the Specimen. In most cases, this should be the specimen’s catalog number at its permanent repository. A good practice is to include the repository code at the beginning of the catalog number if it is not already included in the specimen number (e.g., USNM PAL777113). Institutional/repository codes registered with the Global Registry of Scientific Collections (GRSciColl) can be found at www.gbif.org/grscicoll/institution/search. If a catalog number has not been assigned, a field number or other tracking may be used until the specimen is cataloged. Names can be edited at a later time; it is recommended to record any prior or temporary numbers in the Notes field. 

**Collection** – Choose the Collection to which the specimen belongs. If the Collection for the specimen does not exist yet in PBot, open a new browser and enter a new Collection; after submitting the new collection, use the search tool to find the collection and select it. See Collection instructions for more information. 
Parts preserved – Select the organ(s) or part(s) of the plant that are represented by the preserved specimen. 

**Preservation mode** – Select the modes of preservation that are present in the fossil specimen. You may select more than one if needed. 	

**Repository** – Enter the full name of the institution at which the Specimen is housed. If the Specimen is under study at a different institution than its intended permanent repository, you may enter the intended repository if known, or temporarily the institution where the specimen is under study. This should be updated if the Specimen is later transferred.

## OPTIONAL FIELDS: OTHER
**Notable features preserved** – Choose from the list any notable aspects of the specimen that are known to be preserved.

**References** – Choose an existing Reference, or References, for the Specimen if it has been included in any publications. You may choose a personal ‘working reference’ (see [Reference Instruction sheet](https://github.com/paleobot/pbot-static/blob/d2d0d69162fc1324b29cf01c143cc63b3c844d37/How%20To/Reference.md)) if the specimen has not been published but is part of an in-progress project. Enter the order number for the Reference to indicate its priority in the reference list, with the most relevant publication as order 1. 
	
**Identified by** – Choose names of people (Person nodes) that are responsible for identifying the specimen as a particular OTU. Note that Specimens are assigned to OTUs through the OTU page. Should you realize mid-entry that a Person node does not exist for one of the identifiers, it is possible to edit the specimen later to add an identifier after creating their Person node.

**Other repository link** – Type or paste a url to an existing record for this specimen on any other online database, such as a museum’s online catalog. Multiple entries can be separated by a comma.

**Notes** – Enter notes about the specimen that the enterer deems necessary to record. This is the appropriate place to discuss the history of the Specimen Name, such as providing a field number or previous repository number if a Specimen has been moved. It is particularly important to do this if a publication refers to that Specimen using a different number than the Specimen name. This field can be used for research notes or memos to your collaborators, and you may edit or delete such notes at any time. 

## OPTIONAL FIELDS: IDIGBIO
*This tab provides a lookup function and link to records in iDigBio. Type the Institution code and Catalog number, or the UUID, then click the search icon to find and select the iDigBio record for the specimen.*

**Institution code** – type the institution code of the repository.

**Catalog number** – type the catalog number of the specimen at the repository. Click anywhere outside of the field and then click the green magnifying glass icon to search for specimen record in iDigBio. 

**UUID** – type the Universal Unique Identifier (UUID). Click anywhere outside of the field and then click the green magnifying glass icon to search for specimen record in iDigBio.
