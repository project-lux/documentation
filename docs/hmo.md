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

| LUX Field Name           | LUX Description                                                                                   | LUX Path                                     |
|--------------------------|---------------------------------------------------------------------------------------------------|----------------------------------------------|
| Name                     | The name for the Human Made Object. This field is often synonymous with title.                   | identified_by > Name > content               |

![Name Content](assets/HMO/name-content.png)

| Name Type                | The classification of the name, e.g. "primary" or "sort".                                          | identified_by > Name > classified_as         |

![Name Classification](assets/HMO/name-classification.png)

| Name Language            | The language of the name, e.g. "English".                                                          | identified_by > Name > language              |

![Name Language](assets/HMO/name-language.png)

| Identifier               | Numerical identifiers for Human Made Object.                                                       | identified_by > Identifier > content         |

![Identifier Content](assets/HMO/ident-content.png)

| Identifier Type          | Classification of identifiers.                                                                     | identified_by > Identifier > classified_as   |

![Identifier Classification](assets/HMO/ident-classification.png)

| Identifier Data Assignment | Used to denote the assigner of the identifier.                                                   | identified_by > Identifier > assigned_by > AttributeAssignment |

![Identifier Assigned By](assets/HMO/ident-assignedby.png)

| Exact Match              | Holds internal URI or reconciled Wikidata URI.                                                     | equivalent                                   |

![Equivalent](assets/HMO/equivalent.png)

| Internal Label           | Human-readable label for object.                                                                   | _label                                       |

![Label](assets/HMO/label.png)



### Classification

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Type | Classification of the Human Made Object, e.g. "painting" or "fossil". | classified_as |

![Classification](assets/HMO/classified-as.png)


### Physicality

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Dimension Value | Numerical value of the dimension. | dimension > value |

![Dimension Value](assets/HMO/dimension-value.png)

| Dimension Unit | Unit for the dimension, e.g. centimeters. | dimension > unit |

![Dimension Unit](assets/HMO/dimension-unit.png)

| Dimension Type | Classification for the dimension, e.g. height. | dimension > classified_as |

![Dimension Classification](assets/HMO/dimension-classification.png)

| Material | Material of the object. | made_of |

![Material](assets/HMO/made-of.png)


### Production

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Creator in Production Event | Producer of the object, e.g. artist, maker. | produced_by > carried_out_by |

![Production Carried Out By](assets/HMO/production-carriedoutby.png)

| Location of Production Event | Location of production. | produced_by > took_place_at |

![Production Location](assets/HMO/production-location.png)

| Production Event Technique | Technique of production. | produced_by > technique |

| Influence on Production Event | Entity influencing the production. | produced_by > influenced_by |

![Production Influence](assets/HMO/production-influence.png)

| Production Event Type | Classification of the production. | produced_by > classified_as |

![Production Classification](assets/HMO/production-classification.png)

| Production Event Part | Break production into parts. | produced_by > part |

![Production Part](assets/HMO/production-part.png)

| TimeSpan of Production Event | Timespan of production. | produced_by > timespan |

![Production TimeSpan](assets/HMO/production-timespan.png)

| Statement about Production Event | Statements about the Production. | produced_by > referred_to_by |

![Production Statement](assets/HMO/production-statement.png)

### Encounter

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Agent in Encounter Event | Person or Group who encountered the object. | encountered_by > carried_out_by |

![Encounter Carried Out By](assets/HMO/encounter-carriedoutby.png)

| Location of Encounter Event | Location of encounter. | encountered_by > took_place_at |

![Encounter Location](assets/HMO/encounter-location.png)

| Encounter Event Type | Classification of encounter. | encountered_by > classified_as |

| TimeSpan of Encounter Event | Timespan of encounter. | encountered_by > timespan |

![Encounter Timespan](assets/HMO/encounter-timespan.png)

| Statement about Encounter Event | Statements about the Encounter. | encountered_by > referred_to_by |


### Statement

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Statement | Statements about the Human Made Object. | referred_to_by > content |

![Statement Content](assets/HMO/statement-content.png)

| Statement Type | Classification of the statement about the Human Made Object, e.g. "provenance statement". | referred_to_by > classified_as |

![Statement Classification](assets/HMO/statement-classification.png)

| Statement Type Metatype | Note classification metatype. | referred_to_by > classified_as > classified_as |

![Statement Classification Metatype](assets/HMO/statement-classificationmetatype.png)

| Statement Language | Language of statement. | referred_to_by > language |

| Name for Statement | Label override for statements in UI. | referred_to_by > identified_by |

![Statement Name](assets/HMO/statement-name.png)


### Part Of

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Part of Object | Another, possibly larger object, that this object forms part of. | part_of |

| Part of Set | Set this object is a member of. | member_of |

![Member Of](assets/HMO/member-of.png)


### Referenced Works

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Visual Image Shown | Visual item the object shows. Objects from the Peabody will not have this property. | shows |

![Shows](assets/HMO/shows.png)

| Text Carried | Textual Work the object carries. Objects from the Peabody will not have this property. | carries |

![Carries](assets/HMO/carries.png)


### Digital Images

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Depicting Image | Thumbnail representation of the image. | representation |

![Representation](assets/HMO/representation.png)

| Digital Reference | Webpages and IIIF manifests. | subject_of > digitally_carried_by |

![Digital Reference](assets/HMO/digitalreference.png)

| Digital Reference Type | Classification of digital reference. | subject_of > digitally_carried_by > classified_as |

![Digital Reference Classification](assets/HMO/digitalreference-classification.png)

| Name for Digital Reference | Label for the digital reference. | subject_of > digitally_carried_by > identified_by |

![Digital Reference Name](assets/HMO/digitalreference-name.png)

| Digital Reference Format | Media type of digital object (e.g. "text/html"). | subject_of > digitally_carried_by > format |

![Digital Reference Format](assets/HMO/digitalreference-format.png)

| Digital Reference Access Point | Website URL or URI of digital object. | subject_of > digitally_carried_by > access_point |

![Digital Reference Access Point](assets/HMO/digitalreference-accesspoint.png)


### Current Status

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Current Location | Current physical location. | current_location |

![Current Location](assets/HMO/current-location.png)

| Current Owner | Current owner of the object. | current_owner |

![Current Owner](assets/HMO/current-owner.png)
