# Set

Sets are conceptual groupings, rather than physical ones. The set of objects in a virtual exhibition or simply the set of a person's favorite objects never change their physical state by being part of the Set or not. One might have a set of destroyed objects which would be extremely strange if the Set was a physical aggregation of things which no longer existed. Sets are, thus, created by a Creation, not by a Production, and cannot be destroyed. A set may have zero members at any given point in time without going out of existence.

See more at:
[Linked.art's Set Model Documentation](https://linked.art/model/collection/)

### Representative Data Examples

- []()
- []()

 

### LUX Modeling Documentation

- [Names & Identifiers](#names-and-identifiers)
- [Classification](#classification)
- [Creation](#creation)
- [Statement](#statement)
- [Digital Reference](#digital-reference)



### Names and Identifiers

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Name | Name of Set | identified_by > Name > content |

**JSON Example**
![Name Content](assets/Set/name-content.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Name Type | The classification of the name, e.g. "primary". | identified_by > Name > classified_as |

**JSON Example**
![Name Classification](assets/Set/name-classification.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Name Language | The language of the name, e.g. "English". | identified_by > Name > language |

**JSON Example**
![Name Language](assets/Set/name-language.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Exact Match | On Sets, the equivalent property usually only holds the record of internal unit's URI that contributes to the LUX record. | equivalent |

**JSON Example**
![Equivalent](assets/Set/equivalent.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Internal Label | Human-readable label for Set. | _label |

**JSON Example**
![Label](assets/Set/label.png)


### Classification

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Type | Classification of the Set. | classified_as |

**JSON Example**
![Classification](assets/Set/classified-as.png)

### Creation

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Creator in Creation Event | Creator of Set. | created_by > carried_out_by |

**JSON Example**
![Creation Carried Out By](assets/Set/creation-carriedoutby.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Location of Creation Event | Location of creation. | created_by > took_place_at |

**JSON Example**
example pending

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Creation Event Type | Classification of the creation. | created_by > classified_as |

**JSON Example**
![Creation Classification](assets/Set/creation-classification.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| TimeSpan of Creation Event | Timespan of creation. | created_by > timespan |

**JSON Example**
example pending

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Statement about Creation Event | Statements about the Creation. | created_by > referred_to_by |

**JSON Example**
example pending

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Cause of Creation Event | If an Activity with a separate record and URI is the cause of a Work's creation, this is where you can document that relationship. | created_by > caused_by |


**JSON Example**
![Creation Caused By](assets/Set/creation-causedby.png)


### Statement

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Statement | Statement about the Set. | referred_to_by > content |

**JSON Example**
![Statement Content](assets/Set/statement-content.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Statement Type | Classification of the statement about the Set. | referred_to_by > classified_as |

**JSON Example**
example pending

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Statement Language | Language of the statement about the Set.| referred_to_by > language |

**JSON Example**
example pending

### Digital Reference

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Depicting Image |  | representation |

**JSON Example**
example pending

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Digital Reference | Webpages and IIIF manifests. | subject_of > digitally_carried_by |

**JSON Example**
![Digital Reference](assets/Place/digitalreference.png)

---

| LUX Field Name | LUX Description | LUX Path |
| -------------- | --------------- | -------- |
| Digital Reference Type | Classification of digital reference. | subject_of > digitally_carried_by > classified_as |

**JSON Example**
![Digital Reference Classification](assets/Place/digitalreference-classification.png)

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
| Digital Reference Access Point | The ID field in this array is used to store the website URL. | subject_of > digitally_carried_by > access_point |

**JSON Example**
![Digital Reference Access Point](assets/Place/digitalreference-accesspoint.png)


