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
### Files
Here is how to format a part folder
 - DIR: <PartName>_<Specs>_<Info> 
   - <PartName>.STEP
   - <PartName>.STL
   - Description.md
   - Icon.png

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
