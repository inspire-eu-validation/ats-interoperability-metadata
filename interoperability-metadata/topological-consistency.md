# Topological Consistency

**Purpose**: Verify whether metadata about the topological consistency of the data set has been created and published in the metadata for the data set, if the spatial data set includes types from the Generic Network Model and does not assure centreline topology (connectivity of centrelines) for the network.

**Prerequisites**

**Test method**

Inspect the spatial data set to determine whether it includes instances of types from the Generic Network Model and does not assure centreline topology (connectivity of centrelines) for the network.

If this is the case, inspect the data set metadata whether metadata describing the topological consistency has been created and published in [TopologicalConsistency](#topo) for the data quality measures specified for the theme(s) in the section "Logical Consistency – Topological consistency" in clause 7 of the Technical Guidance.

**Reference(s)**	 

* [TG_DS_TMPL](http://inspire.ec.europa.eu/id/ats/data/3.0rc3/interoperability-metadata/README#ref_TG_DS_TMPL), TG requirements 4 and 5 

**Test type**: Manual

**Notes**

## Contextual XPath references

The namespace prefixes used as described in [README.md](http://inspire.ec.europa.eu/id/ats/data/3.0rc3/interoperability-metadata/README#namespaces).

Abbreviation                                   |  XPath expression (relative to gmd:MD_Metadata)
-----------------------------------------------| -------------------------------------------------------------------------
TopologicalConsistency <a name="distributionFormat"></a>   | gmd:dataQualityInfo/gmd:DQ_DataQuality/gmd:report/DQ_TopologicalConsistency/result/DQ_QuantitativeResult/value