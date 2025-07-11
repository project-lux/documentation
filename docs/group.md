# Group

All activities are carried out by some actor, either a person (Person) or a group of people (Group) such as an organization or company. The identity and description of these actors are very important to record in order to provide the human context for the activities, and their related places and objects. The creators, finders, owners, sellers and curators of objects are all relevant to understanding our cultural heritage.

See more at:
[Linked.art's Group Model Documentation](https://linked.art/model/actor/)


### Representative Data Examples

- [Yale University](https://lux.collections.yale.edu/data/group/44126da0-a6bd-4248-aff3-a3804201a21c)
- [Entomology Collection, Yale Peabody Museum](https://lux.collections.yale.edu/data/group/0345b832-2c37-447a-a28c-4436493d918e)
- [Fleetwood Mac](https://lux.collections.yale.edu/data/group/4946f182-6982-4e3f-939b-3609bc8089ce)
- [Mystic Seaport](https://lux.collections.yale.edu/data/group/9ac63238-bd4e-4c3e-b4f2-121fbba6870b)
- [Marx Brothers](https://lux.collections.yale.edu/data/group/68443df8-c8ae-4989-983d-1dc863dcca98)

### LUX Modeling Documentation

- [Names & Identifiers](#names-and-identifiers)
- [Classification](#classification)
- [Contact Point](#contact-point)
- [Residence](#residence)
- [Formation](#formation)
- [Dissolution](#dissolution)
- [Professional Activity](#professional-activity)
- [Statement](#statement)
- [Member Of](#member-of)
- [Digital Reference](#digital-reference)



### Names and Identifiers

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Name | Name of Group | identified_by > Name > content |

**JSON Example**
![Name Content](assets/Group/name-content.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Name Type | The classification of the name, e.g. "primary". | identified_by > Name > classified_as |

**JSON Example**
![Name Classification](assets/Group/name-classification.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Name Language | The language of the name, e.g. "English". | identified_by > Name > language |

**JSON Example**
![Name Language](assets/Group/name-language.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Exact Match | Holds internal URI or reconciled URI.  | equivalent |

**JSON Example**
![Equivalent](assets/Group/equivalent.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Internal Label | Human-readable label for Group. | _label |

**JSON Example**
![Label](assets/Group/label.png)


### Classification

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Type | Classification of the Group, e.g. "corporation". | classified_as |

**JSON Example**
![Classification](assets/Group/classified_as.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Nationality | A type of classification of the Group, but specifically to record the Group's nationality. | classified_as >  |

**JSON Example**
![Nationality](assets/Group/classified-as-nationality.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Occupation | A type of classification of the Group, but specifically to record the Group's occupation or role. | classified_as >  |

**JSON Example**
![Occupation](assets/Group/classified-as-occupation.png)


### Contact Point

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Contact Point | If a source provides us with an address or email for the Group, it will be recorded here.  | contact_point |

**JSON Example**
![Contact Point](assets/Group/contact-point.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Contact Point Classification | Classification of contact point, e.g. "email". | contact_point > classified_as |

**JSON Example**
![Contact Point Classification](assets/Group/contact-point-classification.png)

### Residence

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Residence | Location of Group. | residence|

**JSON Example**
![Residence](assets/Group/residence.png)

### Formation

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Formation Actor | Person or Persons who formed the Group. | formed_by > carried_out_by|

**JSON Example**
![Formed By Carried Out By](assets/Group/formation-actor.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Formation Location | Location where Group was formed. | formed_by > took_place_at|

**JSON Example**
example pending

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Formation Timespan | Timespan for formation of Group. | formed_by > timespan|

**JSON Example**
![Formed By Timespan](assets/Group/formation-timespan.png)


### Dissolution

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Dissolution Location | Location where Group was dissolved. | dissolved_by > took_place_at|

**JSON Example**
example pending

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Dissolution Timespan | Timespan for dissolution of Group. | dissolved_by > timespan|

**JSON Example**
![Dissolution Timespan](assets/Group/dissolution-timespan.png)

### Professional Activity


| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Professional Activity Location | Location where Group was professionally active. | carried_out > took_place_at|

**JSON Example**
![Professional Activity Took Place At](assets/Group/professional-activity-location.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Professional Activity Timespan | Timespan for professional activity of Group. | carried_out > timespan|

**JSON Example**
![Professional Activity Timespan](assets/Group/professional-activity-timespan.png)


### Statement

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Statement | Biographical or other statements about the Group. | referred_to_by > content |

**JSON Example**
![Statement Content](assets/Group/statement-content.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Statement Type | Classification of the statement, e.g. "biographical". | referred_to_by > classified_as |

**JSON Example**
![Statement Classification](assets/Group/statement-classification.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Statement Language | Language of the statement, e.g. "english". | referred_to_by > language |

**JSON Example**
![Statement Language](assets/Group/statement-language.png)


### Member Of

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Member Of | Used to denote membership of this Group to a specified Group. | member_of |

**JSON Example**
![Member Of](assets/Group/member-of.png)


### Digital Reference

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Depicting Image | Used to store data for images. Images for People come from Wikimedia. | representation |

**JSON Example**
![Representation](assets/Group/representation.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Digital Reference | Webpages and IIIF manifests. | subject_of > digitally_carried_by |

**JSON Example**
![Digital Reference](assets/Group/digitalreference.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Digital Reference Type | Classification of digital reference. | subject_of > digitally_carried_by > classified_as |

**JSON Example**
![Digital Reference Classification](assets/Group/digitalreference-classification.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Name for Digital Reference | Label for the digital reference. | subject_of > digitally_carried_by > identified_by |

**JSON Example**
example pending

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Digital Reference Format | Media type of digital object (e.g. "text/html"). | subject_of > digitally_carried_by > format |

**JSON Example**
example pending

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Digital Reference Access Point | Website URL or URI of digital object. | subject_of > digitally_carried_by > access_point |

**JSON Example**
![Digital Reference Access Point](assets/Group/digitalreference-accesspoint.png)



