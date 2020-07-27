2020-07-07
----------

Change normative reference from 
SMPTE ST 2067-2:2016 
to 
SMPTE ST 2067-2:2020

Remove normative reference 
SMPTE ST 2067-20:2016

Correct annex C table numbering.

Limit Color scheme in table C.2 to COLOR.APP4.2.
Limit Color scheme in table C.3 to COLOR.APP4.1.

2020-06-08
----------
All incomplete namespaces 
http://www.smpte-ra.org/ns/2067-40/20XX
http://www.smpte-ra.org/ns/2067-40/202X

Have been changed to : 

http://www.smpte-ra.org/ns/2067-40/2020

Shim and color-scheme namespaces corrected as proposed : 

https://github.com/SMPTE/st2067-40-2ED/issues/13

Table 7 : http://www.smpte-ra.org/ns/2067-40/2020/shims#image
Table 14 : http://www.smpte-ra.org/ns/2067-40/2020/shims#timed-text
Table C.2 : http://www.smpte-ra.org/ns/2067-40/2020/opl-color-scheme#APP4-XYZ-12
Table C.3 : http://www.smpte-ra.org/ns/2067-40/2020/opl-color-scheme#APP4-XYZ-16


2020-06-03
----------

https://github.com/SMPTE/st2067-40-2ED/issues/9#issuecomment-637446229
WR : Table C.3: For consistency, "R’, G’ and B’ components as specified in Section 5.3.4" should probably read "X_TC, Y_TC and Z_TC components as specified in Section 5.3.4".

Correction as proposed.


2020-06-01
----------

Adjustments concerning OPL annex, thanks to Raymond Yeung.
https://github.com/SMPTE/st2067-40-2ED/issues/9#issuecomment-636390947

The proposed input document requires the following corrections. The publication package will include the associated schema .xsd file as an informative component.

### 1) Add to end of section 3 Normative References
"World Wide Web Consortium (W3C) (2004, October 28). XML Schema Part 2: Datatypes (Second Edition)"
(Note: There should not be a period "." at the end of the final line of the section.)

### 2)
C.1 XML Schema Definition

Replace first sentence:
"XML elements defined by this Annex shall conform to the XML schema definitions (see W3C XML Schema Part 1: Structures as referenced in SMPTE ST 2067-20) found in this specification."
by:
"XML elements defined by this Annex shall conform to the XML schema definitions (see W3C XML Schema Part 1: Structures and W3C XML Schema Part 2: Datatypes) found in this specification."

### 3)
C.2 APP4-XYZ-12

Add these sentences to the first paragraph:
"The mathematical functions "floor(x)" and "clamp(a, b, x)" in Table C.1 shall be as defined in ST 2067-102. The XML datatype Integer4096TripletType shall be as defined in ST 2067-102."

### 4)
C.3 APP4-XYZ-16
(Section number mislabeled as "C.2")

Add this sentence to the first paragraph:
"The mathematical functions "floor(x)" and "clamp(a, b, x)" in Table C.1 shall be as defined in ST 2067-102. The XML datatype Integer65536TripletType shall be as defined in ST 2067-102."

### 5) Style
Annex C section headings are not in the proper style.


### 6) Add this section to Annex C
"
C.4 Consolidated Schema (Informative)
This specification is accompanied by the following element, which is an XML schema document as specified in W3C XML Schema Part 1: Structures.

st2067-40a-202X.xsd

This element collects the XML schema definitions defined in this specification. It is informative and, in case of
conflict, this specification takes precedence.
"

2020-05-29
----------

The following issues correction have been discussed in the 35PM50 DG meeting on 28th, May 2020.

### Delete 428-21:2011 from bibliography
https://github.com/SMPTE/st2067-40-2ED/issues/2

Done

### References in section 7.2 #3

Change reference from 5.3 to (5.2 and 5.3)

Change reference from 5.4.1 to 5.4.3 (5.4.2, if section 5.4.1 is deleted, see SMPTE/st2067-40#20)

Done

### Remove empty section 5.4.1

https://github.com/SMPTE/st2067-40-2ED/issues/4

Done

### New 2020 application indentifiers using old SMPTE namespace convention

https://github.com/SMPTE/st2067-40-2ED/issues/6

Correction from http://www.smpte-ra.org/schemas/ to http://www.smpte-ra.org/ns done on all namespaces.

### Incorrect version byte at Table 21 and 22

https://github.com/SMPTE/st2067-40-2ED/issues/8

https://registry.smpte-ra.org/view/draft/docs/Register%20(ALL)/UL%20version%20bytes/#assigning-version-byte-values

Registry submission :
https://registry.smpte-ra.org/view/development/proposals/89_PL_2020-04-23--ST2067-40-IMF-App4/

Change e to d in 2d an 3d label in the annex.

### Suppress reference to SMPTE ST 2067-20

https://github.com/SMPTE/st2067-40-2ED/issues/11

As SMPTE ST 2067-20 is considered for suppression, remove all references to this specification in document.

For example :

The reference is replaced with 2067-21:2020, which include the necessary prose.

### Add Pixel Color Schemes for OPL processing
https://github.com/SMPTE/st2067-40-2ED/issues/9

Suggested sections and annex included in the document. Thank Raymond Yeung for drafting those sections !

### Creator, Issuer and ContentVersion should not be required

https://github.com/SMPTE/st2067-40-2ED/issues/10

Creator and Issuer remains mandatory, section requiring at least one ContentVersion presence is suppressed.
