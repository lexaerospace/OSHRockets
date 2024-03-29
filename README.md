# OSHRockets 🚀
An open-source part CAD library for model rocketry. All parts are welcome, just follow the standards.
If you have CAD files and are willing to write some documentation, please make a pull request and add your parts to the library. 

## Contribution Guide:
1. Parts must be flight-proven, and their usage made explicity clear
2. STEP or STL only, no proprietary formats
3. Each part file must have an accompanying .txt with identical filename
- Short description of the part
- Required fabrication techniques, Ex: FDM print, Resin print, Purchase online (provide link)
- Recommended print settings and weight (if applicable)
- Recommended usage, Ex: "Flew on ~500g 1m length rocket with Aerotech F26-6FJ"  

### OSHRockets Standards
Adhere to these standards or your pull request won't be merged.

#### File Organization
Here is how to format a part folder:

`PartName` is the type of part, for example: Nosecone, Transition, FinCan, etc.
 
`Specs` are added using tags, D:diameter\_L:length\_M:mass, order doesn't matter
 
`Info` is other info, describing the part in under 30 characters
 
 - DIR: `PartName`\_`Specs`\_`Info` 
   - `PartName`\_`component`.step (If multiple .step, specify the `component` tag)
   - `PartName`\_`component`.stl
   - Description.md
   - Icon.png

For example, a BT-80 diameter, 5cm tall, 60g ogive nosecone that stores clay: 

 - NoseconeOgive_D:BT-80\_L:5cm\_M:60g_ClayPayload
   - NoseconeOgive_Top.step
   - NoseconeOgive_Bottom.step
   - NoseconeOgive_Top.stl
   - NoseconeOgive_Bottom.stl
   - Description.md
   - Icon.png

#### Writing Part Descriptions
To be written
 
#### Body Tube Sizes
 - Body Tube 80 (BT-80)
   - Inner diameter : 65.0mm
   - Outer diameter : 66.0mm
   - Inner Print Diameter : 64.8mm
 - Body Tube 70 (BT-70)
   - Inner diameter : 55.4mm
   - Outer diameter : 56.3mm
   - Inner Print Diameter : 55.2mm or 55.0mm test
 - Body Tube 60 (BT-60)
   - Inner diameter : 40.5mm
   - Outer diameter : 41.6mm
   - Inner Print Diameter : ???
 - 29mm Engine Tube
   - Inner diameter : 29.0mm
   - Outer diameter : 29.9mm or 30.7mm
   - Inner Print Diameter : ???
   - Outer Print Diameter : ???
 - 24mm Engine Tube (BT-50)
   - Inner diameter : 24.1mm
   - Outer diameter : 24.8mm or 30.7mm
   - Inner Print Diameter : ???
   - Outer Print Diameter : ???  

#### Part Strength/Weight

 - For a part to be considered high strength/weight walls must be solid and at least 5mm thick. Walls cannot be skeletonized.
 - Low strength/weight parts should stay generally stay above 2mm thick and below 5mm thick. Walls can be skeletonized.
 - All separator Bulkheads should be at least 4mm thick

#### Other Dimensions
 - Fins designed for an internal fin aligner should have a 40mm long fin tab
 - All Fin tab widths should equal (in mm) (body tube outer diameter - engine tube outer diameter)/2+.2
 - Internal fin aligner slots should be 40mm tall and 3.2mm wide
