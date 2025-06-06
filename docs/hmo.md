# Human Made Object

The class for physical objects that have some value in human society is HumanMadeObject. Even if the object is a shell (and thus natural) without any significant modifications, this class is still used as the modification is the instilling of value by society. 

[Linked.art's HMO Model Documentation](https://linked.art/model/object/)



## Table of Contents

- [Names & Identifiers](#names-and-identifiers)
- [Classification](#classification)
- [Physicality](#physicality)
- [Production](#production)
- [Encounter](#encounter)
- [Statement](#statement)
- [Part Of](#part-of)
- [Referenced Works](#referenced-works)
- [Digital Images](#digital-images)
- [Current Status](#current-status)



### Names and Identifiers

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Name                             | The name for the Human Made Object. This field is often synonymous with title.                                   | identified\_by > Name > content                                  |  ![Name Content](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/name-content.png)  |
| Name Type                        | The classification of the name, e.g. "primary" or "sort".                                                        | identified\_by > Name > classified\_as     | ![Name Classification](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/name-classification.png)  |
| Name Language                    | The language of the name, e.g. "English".                                                                        | identified\_by > Name > language                                 |  ![Name Language](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/name-language.png)           |
| Identifier                       | Numerical identifiers for Human Made Object.                                                                     | identified\_by > Identifier > content                            |   ![Identifier Content](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/ident-content.png)           |
| Identifier Type                  | Classification of identifiers.                                                                                   | identified\_ by > Identifier > classified\_as                    |   ![Identifier Classification](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/ident-classification.png)         |
| Identifier Data Assignment       | Used to denote the assigner of the identifier, e.g. Yale Center for British Art assigned their accession number. | identified\_by > Identifier > assigned\_by > AttributeAssignment |  ![Identifier Assigned By](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/ident-assignedby.png)    |
| Exact Match                      | On Human Made Objects, the equivalent property usually holds the record of internal unit's URI that contributes to the LUX record. It may also include a Wikidata URI, if this Object was reconciled to Wikidata.               | equivalent                                                       |   ![Equivalent](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/equivalent.png)           |
| Internal Label                   | Human-readable label for object.                                                                                 | \_label                                                          |  ![Label](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/label.png)            |


### Classification

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Type                             | Classification of the Human Made Object, e.g. "painting" or "fossil".                                            | classified\_as              |  ![Classification](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/classified-as.png) |

### Physicality

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Dimension Value                  | Numerical value of the dimension.                                                                                | dimension > value                                                | ![Dimension Value](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/dimension-value.png)             |
| Dimension Unit                   | Unit for the dimension, e.g. centimeters.                                                                        | dimension > unit                                                 | ![Dimension Unit](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/dimension-unit.png)           |
| Dimension Type                   | Classification for the dimension, e.g. height.                                                                   | dimension > classified\_as                                       | ![Dimension Classification](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/dimension-classification.png)           |
| Material                         | Material of the object.                                                                                          | made\_of                                                         |  ![Material](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/made-of.png)          |

### Production

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Creator in Production Event      | Producer of the object, e.g. artist, maker.                                                                      | produced\_by > carried\_out\_by                                  |  ![Production Carried Out By](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/production-carriedoutby.png)          |
| Location of Production Event     | Location of production.                                                                                          | produced\_by > took\_place\_at                                   |  ![Production Location](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/production-location.png)          |
| Production Event Technique       | Technique of production.                                                                                         | produced\_by > technique                                         |     |
| Influence on Production Event    | Entity influencing the production.                                                                               | produced\_by > influenced\_by                                    |   ![Production Influence](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/production-influence.png)         |
| Production Event Type            | Classification of the production.                                                                                | produced\_by > classified\_as                                    |   ![Production Classification](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/production-classification.png)   |
| Production Event Part            | Break production into parts.                                                                                     | produced\_by > part                                              |  ![Production Part](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/production-part.png)           |
| TimeSpan of Production Event     | Timespan of production.                                                                                          | produced\_by > timespan                                          | ![Production TimeSpan](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/production-timespan.png)     |
| Statement about Production Event | Statements about the Production.                                                                                 | produced\_by > referred\_to\_by                                  | ![Production Statement](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/production-statement.png)          |

### Encounter

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Agent in Encounter Event       | Person or Group who encountered the object.                                                                      | encountered\_by > carried\_out\_by                               |  ![Encounter Carried Out By](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/encounter-carriedoutby.png)          |
| Location of Encounter Event      | Location of encounter.                                                                                           | encountered\_by > took\_place\_at                                |  ![Encounter Location](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/encounter-location.png)          |
| Encounter Event Type             | Classification of encounter.                                                                                     | encountered\_by > classified\_as                                 |           |
| TimeSpan of Encounter Event      | Timespan of encounter.                                                                                           | encountered\_by > timespan                                       |  ![Encounter Timespan](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/encounter-timespan.png)           |
| Statement about Encounter Event  | Statements about the Encounter.                                                                                  | encountered\_by > referred\_to\_by                               |          |


### Statement

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Statement                        | Statements about the Human Made Object.                                                                          | referred\_to\_by > content                                       | ![Statement Content](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/statement-content.png) 
| Statement Type                   | Classification of the statement about the Human Made Object, e.g. "provenance statement".                        | referred\_to\_by > classified\_as                                |  ![Statement Classification](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/statement-classification.png)         |
| Statement Type Metatype          | Note classification metatype.                                                                                    | referred\_to\_by > classified\_as > classified\_as               |   ![Statement Classification Metatype](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/statement-classificationmetatype.png)         |
| Statement Language               | Language of statement.                                                                                           | referred\_to\_by > language                                      |            |
| Name for Statement               | Label override for statements in UI.                                                                             | referred\_to\_by > identified\_by                                |  ![Statement Name](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/statement-name.png)            |


### Part Of

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Part of Object                   | Another, possibly larger object, that this object forms part of.                                                                      | part\_of                                                         |            |
| Part of Set                      | Set this object is a member of.                                                                                  | member\_of                                                       | ![Member Of](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/member-of.png)           |

### Referenced Works

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Visual Image Shown               | Visual item the object shows. Objects from the Peabody will not have this property.                                                                                 | shows                                                            | ![Shows](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/shows.png)            |
| Text Carried                     | Textual Work the object carries. Objects from the Peabody will not have this property.                                                                                | carries                                                          |  ![Carries](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/carries.png)           |

### Digital Images

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Depicting Image                  | Thumbnail representation of the image.                                                                           | representation                                                   |   ![Representation](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/representation.png)        |
| Digital Reference                | Webpages and IIIF manifests.                                                                                     | subject\_of > digitally\_carried\_by                             |  ![Digital Reference](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/digitalreference.png)         |
| Digital Reference Type           | Classification of digital reference.                                                                             | subject\_of > digitally\_carried\_by > classified\_as            |  ![Digital Reference Classification](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/digitalreference-classification.png)           |
| Name for Digital Reference       | Label for the digital reference.                                                                                 | subject\_of > digitally\_carried\_by > identified\_by            |  ![Digital Reference Name](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/digitalreference-name.png)           |
| Digital Reference Format         | Media type of digital object (e.g. "text/html").                                                                 | subject\_of > digitally\_carried\_by > format                    |  ![Digital Reference Format](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/digitalreference-format.png)           |
| Digital Reference Access Point   | Website URL or URI of digital object.                                                                            | subject\_of > digitally\_carried\_by > access\_point             | ![Digital Reference Access Point](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/digitalreference-accesspoint.png)            |

### Current Status

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Current Location                 | Current physical location.                                                                                       | current\_location                                                | ![Current Location](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/current-location.png)         |
| Current Owner                    | Current owner of the object.                                                                                     | current\_owner                                                   |  ![Current Owner](https://raw.githubusercontent.com/project-lux/documentation/main/screenshots/HMO/current-owner.png)        |
