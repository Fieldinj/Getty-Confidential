<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Getty Confindential"
       author="Isabelle Woodward and Jacquelyn Fielding"
       banner="https://pbs.twimg.com/media/FkcID2GXwAAfRgM?format=jpg&name=medium" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param ve-entity eid="Q185372"> <!-- Girl with a Pearl Earring painting -->
<param ve-entity eid="Q41264"> <!-- Johannes Vermeer -->
<param ve-entity eid="Q221092"> <!-- Mauritshuis -->
<param ve-entity eid="Q36600"> <!-- The Hague -->

# Sample visual essay

This is a sample visual essay demonstrating a few key features of a Visual Essay. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-image 
       manifest="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Statue_of_a_kouros_%28c._530_BCE_or_modern%2C_Getty_Villa_Collection%29.jpg/640px-Statue_of_a_kouros_%28c._530_BCE_or_modern%2C_Getty_Villa_Collection%29.jpg">

# Basic usage

## Image

 A statue of a kouros, that is, an Archaic Greek representation of a nude young man. Known as the "Getty kouros", its authenticity has not been completely resolved because it evidences a mixture of earlier and later stylistic traits and uses marble from Thasos island at an unexpected date. The website of the Getty Villa states: "The anomalies of the Getty kouros may be due more to our limited knowledge of Greek sculpture in this period rather than to mistakes on the part of a forger."[^1]
<param ve-image 
       label="Statue of Kouros " 
       description="Photo of Getty Museum's Statue of Kouros" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a5/Statue_of_a_kouros_%28c._530_BCE_or_modern%2C_Getty_Villa_Collection%29.jpg/640px-Statue_of_a_kouros_%28c._530_BCE_or_modern%2C_Getty_Villa_Collection%29.jpg">

## Map

The work has been in the collection of the Mauritshuis in The Hague since 1902 and has been the subject of various 
literary treatments. In 2006, the Dutch public selected it as the most beautiful painting in the Netherlands.
<param ve-map center="Q36600" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [WikiMedia: Statue of a kouros](https://commons.wikimedia.org/wiki/File:Statue_of_a_kouros_(c._530_BCE_or_modern,_Getty_Villa_Collection).jpg#metadata)
