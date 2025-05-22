
### Names and Identifiers

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Name                             | The name for the Human Made Object. This field is often synonymous with title.                                   | identified\_by > Name > content                                  |  ![Name Content](screenshots/hmo/name-content)          |
| Name Type                        | The classification of the name, e.g. "primary" or "sort".                                                        | identified\_by > Name > classified\_as     | ![Name Classification](screenshots/hmo/name-classification)  |
| Name Language                    | The language of the name, e.g. "English".                                                                        | identified\_by > Name > language                                 |  ![Name Language](screenshots/hmo/name-language)          |
| Identifier                       | Numerical identifiers for Human Made Object.                                                                     | identified\_by > Identifier > content                            |   ![Identifier Content](screenshots/hmo/ident-content)          |
| Identifier Type                  | Classification of identifiers.                                                                                   | identified\_ by > Identifier > classified\_as                    |   ![Identifier Classification](screenshots/hmo/ident-classification)          |
| Identifier Data Assignment       | Used to denote the assigner of the identifier, e.g. Yale Center for British Art assigned their accession number. | identified\_by > Identifier > assigned\_by > AttributeAssignment |  ![Identifier Assigned By](screenshots/hmo/ident-assignedby)    |
| Exact Match                      | On Human Made Objects, the equivalent property usually holds the record of internal unit's URI that contributes to the LUX record. It may also include a Wikidata URI, if this Object was reconciled to Wikidata.               | equivalent                                                       |   ![Equivalent](screenshots/hmo/equivalent)          |


### Classification

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Type                             | Classification of the Human Made Object, e.g. "painting" or "fossil".                                            | classified\_as              |  ![Classification](screenshots/hmo/classified-as)|

### Physicality (dimensions and materials)

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Dimension Value                  | Numerical value of the dimension.                                                                                | dimension > value                                                | ![Dimension Value](screenshots/hmo/dimension-value)            |
| Dimension Unit                   | Unit for the dimension, e.g. centimeters.                                                                        | dimension > unit                                                 | ![Dimension Unit](screenshots/hmo/dimension-unit)           |
| Dimension Type                   | Classification for the dimension, e.g. height.                                                                   | dimension > classified\_as                                       | ![Dimension Classification](screenshots/hmo/dimension-classification)           |
| Material                         | Material of the object.                                                                                          | made\_of                                                         |  ![Material](screenshots/hmo/made-of)          |

### Production

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Creator in Production Event      | Producer of the object, e.g. artist, maker.                                                                      | produced\_by > carried\_out\_by                                  |  ![Production Carried Out By](screenshots/hmo/production-carriedoutby)          |
| Location of Production Event     | Location of production.                                                                                          | produced\_by > took\_place\_at                                   |  ![Production Location](screenshots/hmo/production-location)          |
| Production Event Technique       | Technique of production.                                                                                         | produced\_by > technique                                         |     |
| Influence on Production Event    | Entity influencing the production.                                                                               | produced\_by > influenced\_by                                    |   ![Production Influence](screenshots/hmo/production-influence)          |
| Production Event Type            | Classification of the production.                                                                                | produced\_by > classified\_as                                    |   ![Production Classification](screenshots/hmo/production-classification)  |
| Production Event Part            | Break production into parts.                                                                                     | produced\_by > part                                              |  ![Production Part](screenshots/hmo/production-part)          |
| TimeSpan of Production Event     | Timespan of production.                                                                                          | produced\_by > timespan                                          | ![Production TimeSpan](screenshots/hmo/production-timespan)           |
| Statement about Production Event | Statements about the Production.                                                                                 | produced\_by > referred\_to\_by                                  | ![Production Statement](screenshots/hmo/production-statement)           |

### Encounter

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Agent in Encounter Event       | Person or Group who encountered the object.                                                                      | encountered\_by > carried\_out\_by                               |  ![Encounter Carried Out By](screenshots/hmo/encounter-carriedoutby)           |
| Location of Encounter Event      | Location of encounter.                                                                                           | encountered\_by > took\_place\_at                                |  ![Encounter Location](screenshots/hmo/encounter-location)           |
| Encounter Event Type             | Classification of encounter.                                                                                     | encountered\_by > classified\_as                                 |           |
| TimeSpan of Encounter Event      | Timespan of encounter.                                                                                           | encountered\_by > timespan                                       |  ![Encounter Timespan](screenshots/hmo/encounter-timespan)           |
| Statement about Encounter Event  | Statements about the Encounter.                                                                                  | encountered\_by > referred\_to\_by                               |  ![Encounter Timespan](screenshots/hmo/encounter-timespan)           |


### Statement

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Statement                        | Statements about the Human Made Object.                                                                          | referred\_to\_by > content                                       | ![Statement Content](screenshots/hmo/statement-content)             |
| Statement Type                   | Classification of the statement about the Human Made Object, e.g. "provenance statement".                        | referred\_to\_by > classified\_as                                |  ![Statement Classification](screenshots/hmo/statement-classification)           |
| Statement Type Metatype          | Note classification metatype.                                                                                    | referred\_to\_by > classified\_as > classified\_as               |   ![Statement Classification Metatype](screenshots/hmo/statement-classificationmetatype)          |
| Statement Language               | Language of statement.                                                                                           | referred\_to\_by > language                                      |            |
| Name for Statement               | Label override for statements in UI.                                                                             | referred\_to\_by > identified\_by                                |  ![Statement Name](screenshots/hmo/statement-name)           |


### Part Of

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Part of Object                   | The object this is physically a part of.                                                                         | part\_of                                                         |            |
| Part of Set                      | Set this object is a member of.                                                                                  | member\_of                                                       | ![Member Of](screenshots/hmo/member-of)            |

### Works and Images Carried

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Visual Image Shown               | Visual item the object shows. Objects from the Peabody will not have this property.                                                                                 | shows                                                            | ![Shows](screenshots/hmo/shows)            |
| Text Carried                     | Textual Work the Object carries. Objects from the Peabody will not have this property.                                                                                | carries                                                          |  ![Carries](screenshots/hmo/carries)           |

### Digital Images

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Depicting Image                  | Thumbnail representation of the image.                                                                           | representation                                                   |   ![Representation](screenshots/hmo/representation)       |
| Digital Reference                | Webpages and IIIF manifests.                                                                                     | subject\_of > digitally\_carried\_by                             |  ![Digital Reference](screenshots/hmo/digitalreference)           |
| Digital Reference Type           | Classification of digital reference.                                                                             | subject\_of > digitally\_carried\_by > classified\_as            |  ![Digital Reference Classification](screenshots/hmo/digitalreference-classification)           |
| Name for Digital Reference       | Label for the digital reference.                                                                                 | subject\_of > digitally\_carried\_by > identified\_by            |  ![Digital Reference Name](screenshots/hmo/digitalreference-name)           |
| Digital Reference Format         | Media type of digital object (e.g. "text/html").                                                                 | subject\_of > digitally\_carried\_by > format                    |  ![Digital Reference Format](screenshots/hmo/digitalreference-format)           |
| Digital Reference Access Point   | Website URL or URI of digital object.                                                                            | subject\_of > digitally\_carried\_by > access\_point             | ![Digital Reference Access Point](screenshots/hmo/digitalreference-accesspoint)            |

### Current Location & Ownership Information

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Current Location                 | Current physical location.                                                                                       | current\_location                                                | ![Current Location](screenshots/hmo/current-location)        |
| Current Owner                    | Current owner of the object.                                                                                     | current\_owner                                                   |  ![Current Owner](screenshots/hmo/current-owner)        |

### Label

| LUX Field Name     | LUX Description                                                                                       | LUX Path                                                        | JSON Example |
| -------------------------------- | ---------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------- | ---------- |
| Internal Label                   | Human-readable label for object.                                                                                 | \_label                                                          |  ![Label](screenshots/hmo/label)           |
