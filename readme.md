
# NIEM Snippets

NIEM XML follows a regular, well-defined syntax.  Snippets can be used to quickly and consistently fill in the basic syntax, leaving users to fill in the blank or partially-filled in fields.

{:toc}
- TOC

{:.note}
> Snippets may include some commonly-used default values but these may be modified as necessary.  Change default values if needed as the snippet is used, or edit the snippet template itself to fill in better default values for your particular requirements.

## Property Snippets

The following snippets provide template for various kinds of NIEM properties.

<table>
  <thead>
    <th style="width: 20%">Label</th>
    <th style="width: 35%">Description</th>
    <th style="width: 35%">Example pattern</th>
    <th style="width: 10%">Info</th>
  </thead>
  <tr>
    <td>niem-elt</td>
    <td>NIEM element</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/agriculture.xsd#L222-L226">ag:AgricultureProductionPlan</a></td>
    <td><a href="https://niem.github.io/reference/concepts/property/element/">Info</a></td>
  </tr>
  <tr>
    <td>niem-elt-abstract</td>
    <td>NIEM abstract element</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/st.xsd#L1578-L1582">st:RoadwayGradeAbstract</a></td>
    <td><a href="https://niem.github.io/reference/concepts/property/abstract/">Info</a></td>
  </tr>
  <tr>
    <td>niem-elt-augPoint</td>
    <td>NIEM augmentation point element (abstract)</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/infrastructureProtection.xsd#L214-L218">ip:SectorAugmentationPoint</a></td>
    <td><a href="https://niem.github.io/reference/concepts/augmentation/point/">Info</a></td>
  </tr>
  <tr>
    <td>niem-elt-substitution</td>
    <td>NIEM substitutable element</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/st.xsd#L1583-L1587">st:RoadwayGradeCode</a></td>
    <td><a href="https://niem.github.io/reference/concepts/property/substitutable/">Info</a></td>
  </tr>
  <tr>
    <td>niem-attribute</td>
    <td>NIEM attribute</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L2362-L2366">mo:codespaceID</a></td>
    <td><a href="https://niem.github.io/reference/concepts/property/attribute/">Info</a></td>
  </tr>
</table>

## Type Snippets

The following snippets provide templates for various kinds of NIEM types.

<table>
  <thead>
    <th style="width: 20%">Label</th>
    <th style="width: 35%">Description</th>
    <th style="width: 35%">Example pattern</th>
    <th style="width: 10%">Info</th>
  </thead>
  <tr>
    <td>niem-type-object</td>
    <td>NIEM object type <br/>(has sub-properties)</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/infrastructureProtection.xsd#L87-L102">ip:SectorType</a></td>
    <td><a href="https://niem.github.io/reference/concepts/type/ccc/">Info</a></td>
  </tr>
  <tr>
    <td>niem-type-csc</td>
    <td>NIEM complex type with simple content <br/>(has a value and attributes)</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/st.xsd#L622-L631"> st:MedianCategoryCodeType</a></td>
    <td><a href="https://niem.github.io/reference/concepts/type/csc/">Info</a></td>
  </tr>
  <tr>
    <td>niem-type-simple</td>
    <td>NIEM simple type <br/>(has a value)</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L776-L787">mo:MGRSCoordinateStringSimpleType</a></td>
    <td><a href="https://niem.github.io/reference/concepts/type/csc/">Info</a></td>
  </tr>
  <tr>
    <td>niem-type-enum</td>
    <td>NIEM simple type with enumerations (has a value from a given set of codes)</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/st.xsd#L570-L621"> st:MedianCategoryCodeSimpleType</a></td>
    <td><a href="https://niem.github.io/reference/concepts/type/simple/">Info</a></td>
  </tr>
  <tr>
    <td>niem-type-list</td>
    <td>NIEM simple list type <br/>(has a space-separated list of values)</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/niem-core.xsd#L2286-L2291">nc:IntegerListSimpleType</a></td>
    <td><a href="https://niem.github.io/reference/concepts/type/simple/list/">Info</a></td>
  </tr>
  <tr>
    <td>niem-type-union</td>
    <td>NIEM simple union type <br/>(combines codes from multiple types)</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/biom.xsd#L5402:L5407">biom:FrictionRidgePositionCodeSimpleType</a></td>
    <td><a href="https://niem.github.io/reference/concepts/type/simple/union/">Info</a></td>
  </tr>
  <tr>
    <td>niem-type-adapter</td>
    <td>NIEM adapter type <br/>(wraps an element from an external standard)</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L2267-L2282">mo:WGS84EllipseType</a></td>
    <td><a href="https://niem.github.io/reference/concepts/adapter/">Info</a></td>
  </tr>
</table>

## NIEM Combo Snippets

The following snippets provide templates for two or more related NIEM components that are often built at the same time.

<table>
  <thead>
    <th style="width: 20%">Label</th>
    <th style="width: 35%">Description</th>
    <th style="width: 35%">Example pattern</th>
    <th style="width: 10%">Info</th>
  </thead>
  <tr>
    <td>niem-assn-2</td>
    <td>
      NIEM association type <br/>
      NIEM association element
    </td>
    <td>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L122-L136"> mo:AircraftTargetAssociationType</a> <br/>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L2387-L2391"> mo:AircraftAssignedTargetAssociation</a>
    </td>
    <td><a href="https://niem.github.io/reference/concepts/association/">Info</a></td>
  </tr>
  <tr>
    <td>niem-assn-3</td>
    <td>
      NIEM association type <br/> NIEM association element <br/> NIEM association augmentation point
    </td>
    <td>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L122-L136"> mo:AircraftTargetAssociationType</a> <br/>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L2387-L2391"> mo:AircraftAssignedTargetAssociation</a> <br/>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L2392-L2396"> mo:AircraftTargetAssociationAugmentationPoint</a>
    </td>
    <td><a href="https://niem.github.io/reference/concepts/association/">Info</a></td>
  </tr>
  <tr>
    <td>niem-aug-2</td>
    <td>
      NIEM augmentation type <br/>
      NIEM augmentation element
    </td>
    <td>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/intelligence.xsd#L155-L170"> it:PersonAugmentationType</a> <br/>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/intelligence.xsd#L399-L403"> it:PersonAugmentation</a>
    </td>
    <td><a href="https://niem.github.io/reference/concepts/augmentation/element/xml-container/">Info</a></td>
  </tr>
  <tr>
    <td>niem-code-2</td>
    <td>
      NIEM code simple type <br/>
      NIEM code CSC type
    </td>
    <td>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/st.xsd#L570-L621"> st:MedianCategoryCodeSimpleType</a> <br/>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/st.xsd#L622-L631"> st:MedianCategoryCodeType</a> <br/>
    </td>
    <td><a href="https://niem.github.io/reference/concepts/facet/">Info</a></td>
  </tr>
  <tr>
    <td>niem-code-3</td>
    <td>
      NIEM code simple type <br/>
      NIEM code CSC type <br/>
      NIEM code element
    </td>
    <td>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/st.xsd#L570-L621"> st:MedianCategoryCodeSimpleType</a> <br/>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/st.xsd#L622-L631"> st:MedianCategoryCodeType</a> <br/>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/st.xsd#L1518-L1522"> st:MedianCategoryCode</a> <br/>
    </td>
    <td><a href="https://niem.github.io/reference/concepts/facet/">Info</a></td>
  </tr>
  <tr>
    <td>niem-code-4</td>
    <td>
      NIEM code simple type <br/>
      NIEM code CSC type <br/>
      NIEM abstract element <br/>
      NIEM substitutable code element
    </td>
    <td>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L1418-L1439"> mo:SignalDirectionCodeSimpleType</a> <br/>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L1440-L1449"> mo:SignalDirectionCodeType</a> <br/>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L3457-L3461"> mo:SignalDirectionAbstract</a> <br/>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L3462-L3466"> mo:SignalDirectionCode</a> <br/>
    </td>
    <td><a href="https://niem.github.io/reference/concepts/facet/">Info</a></td>
  </tr>
  <tr>
    <td>niem-metadata-2</td>
    <td>
      NIEM metadata type <br/>
      NIEM metadata element
    </td>
    <td>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/niem-core.xsd#L2902-L2939"> cui:DocumentMarkingMetadataType</a> <br/>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/niem-core.xsd#L10138-L10142"> cui:DocumentMarkingMetadata</a> <br/>
    </td>
    <td><a href="https://niem.github.io/reference/concepts/metadata/">Info</a></td>
  </tr>
</table>

## Schema Snippets

The following snippets can be used to initialize a NIEM XML schema and includes a general template for the schema header, definition, local terminology section, and import statements.

<table>
  <thead>
    <th style="width: 20%">Label</th>
    <th style="width: 35%">Description</th>
    <th style="width: 35%">Example pattern</th>
    <th style="width: 10%">Info</th>
  </thead>
  <tr>
    <td>niem-schema-4-ref</td>
    <td>NIEM 4.0-style reference schema template (for a release schema)</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-4.0/niem/domains/intelligence/4.0/intelligence.xsd#L1-L23">Schema header for the NIEM 4.0 Intelligence domain schema</a></td>
    <td><a href="https://niem.github.io/reference/concepts/namespace/">Info</a></td>
  </tr>
  <tr>
    <td>niem-schema-4-ext</td>
    <td>NIEM 4.0-style extension schema template (for an IEPD schema)</td>
    <td><a href=""></a></td>
    <td><a href="https://niem.github.io/reference/concepts/namespace/">Info</a></td>
  </tr>
  <tr>
    <td>niem-schema-5-ref</td>
    <td>NIEM 5.0-style reference schema template (for a release schema)</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/intelligence.xsd#L1-L39">Schema header for the NIEM 5.0 Intelligence domain schema</a></td>
    <td><a href="https://niem.github.io/reference/concepts/namespace/">Info</a></td>
  </tr>
  <tr>
    <td>niem-schema-5-ext</td>
    <td>NIEM 5.0-style extension schema template (for an IEPD schema)</td>
    <td><a href=""></a></td>
    <td><a href="https://niem.github.io/reference/concepts/namespace/">Info</a></td>
  </tr>
</table>

## Other Snippets

The following snippets provide additional NIEM templates.

<table>
  <thead>
    <th style="width: 20%">Label</th>
    <th style="width: 35%">Description</th>
    <th style="width: 35%">Example pattern</th>
    <th style="width: 10%">Info</th>
  </thead>
  <tr>
    <td>niem-enum</td>
    <td>NIEM enumeration</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L199-L203">Code "APPROVED"</a></td>
    <td><a href="https://niem.github.io/reference/concepts/facet/">Info</a></td>
  </tr>
  <tr>
    <td>niem-import</td>
    <td>NIEM import statement for a conformant namespace</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L60">Import NIEM Core</a></td>
    <td><a href="https://niem.github.io/reference/concepts/namespace/">Info</a></td>
  </tr>
  <tr>
    <td>niem-import-external</td>
    <td>NIEM import statement for an external standard</td>
    <td>
      <a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L55-L59">Import GML</a>
      <br/>(not a NIEM-conformant namespace)
    </td>
    <td><a href="https://niem.github.io/reference/concepts/namespace/">Info</a></td>
  </tr>
  <tr>
    <td>niem-term-literal</td>
    <td>NIEM local terminology described by a literal string</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L45">Local term "UTM" with literal</a></td>
    <td><a href="https://niem.github.io/reference/concepts/local-term/">Info</a></td>
  </tr>
  <tr>
    <td>niem-term-def</td>
    <td>NIEM local terminology described by a definition</td>
    <td><a href="https://github.com/NIEM/NIEM-Releases/blob/niem-5.0/xsd/domains/mo.xsd#L47">Local term "Waypoint" with definition</a></td>
    <td><a href="https://niem.github.io/reference/concepts/local-term/">Info</a></td>
  </tr>
</table>
