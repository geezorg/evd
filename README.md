# Ethiopic Variation Database (EVD)

The Ethiopian Variation Database is a subject of the EMUFI initiative that has as its objective the cataloging
and publication of simple database of the variant glyphs within the Ethiopic inventory. The variation database
is developed to help organize, review, and manage variant collections for EMFUI project. The project artifacts
will be consumed directly by EMUFI as its primary resource for variants.


The Ethiopic Variation Database is loosely modeled after the Unicode Consortium's [Ideographic Variant Database](https://www.unicode.org/reports/tr37/).

Target work products of the EVD:

* Identification of the "Primary Variants".
* A data file in the format of the [`StandardizedVariants.txt`](https://www.unicode.org/Public/UCD/latest/ucd/StandardizedVariants.txt)
  file from the [Unicode Character Database (UCD)](https://www.unicode.org/ucd/).
* A Unicode Variation Selectors file compaitible with applications like High-Logic's FontCreator.
* A companion attestations file to the above resources applying the [JSON CSL](https://github.com/citation-style-language/schema) schema
  (Zotero compatible) that extends the database with references.
* A tabular presentation of the catalog in both web and PDF formats (docment generation will utilize the database in JSON).


## See Also

* EMUFI - the Ethiopic Manuscript Unicode Font Initiative (the parent project of this proejct)
* Ethiopic Ligation Database - a companion project for cataloging Ethiopic ligatures.
