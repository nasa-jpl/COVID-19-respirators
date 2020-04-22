# JPL COVID-19-respirators
JPL designed and tested 3D printed respirators to help with the COVID-19 pandemic response.
The designs and instructions for three different types of respirators and the resulting detailed test data is published here.
In addition, designs and instructions for custom filters are also included.
You can review JPL's test results but these respirators are not certified by NIOSH or any medical institution, so use at your own risk.

These designs, instructions, and test data are released to Open Source with the hope that companies and individuals who have access to 3D printers, and who want to help, can print or create these for those who need them. ​We are purposefully not using materials in the normal medical supply chain as it should be kept free to create commercial and certified respirators. We expect and hope that these designs will be commented on and improved by everyone during and after this pandemic.
Below are three different respirator designs that are intended for different uses: The Performance Respirator, the Comfort Respirator, and the Conforming Respirator.

In addition, as there is a shortage or commercial filters, there is also a section for how to build your own filters that fit these respirators.
To decide which respirator is right for your use, please consider these questions:
 1. How are you planning to use the mask?
 2. What tradeoffs between comfort and sealing are right for you? (See the test results)
 3. What materials do you have available?
 4. Which printers do you have access to?
 5. What’s your face shape?
 6. What’s your face size?

# Design 1: JPL Performance Respirator
## Overview
![Two configurations, custom detachachable filter cartridge and integrated filter cartridge, for version 6 of the performance respirator being worn by the designer.](figs/d1-f1.png)

The performance respirator design attempts to mimic the face seal geometry of commercial half-face respirators, such as those from 3M, to provide the highest level of fit performance. This is achieved through the use of a two piece assembly that consists of both a flexible and rigid element. The rigid element provides effective attachment for external filter cartridges while the flexible element has an internal lip to provide a conformal seal against the user’s face. The design also allows the front rigid section to be exchanged for compatibility with a wide range of different filter configurations while preserving the face seal and mounting straps.

![d1-f2.png](figs/d1-f2.png)

The performance respirator design can be easily configured for use with different filter types by swapping the front rigid element. By swapping the front rigid element, the respirator can currently be arranged in two different configurations; front adapter compatible with COTS/custom filter cartridges or with a compact integrated custom filter.

 * Filter Cartridge Mount - In this configuration the rigid section consists of a cover plate that slots into the flexible face seal and provides a filter cartridge attachment point. Currently, the design is configured to be compatible with 3M filter cartridges but the intent is to provide options based on community input.
 * Integrated Custom Filter - In this configuration the front rigid section consists of two pieces with an integrated pleated filter (total surface area of 98 cm2) and provides the most compact arrangement that can fit under a standard face shield. Intake and exhaust both pass through the filter medium and are routed to the sides of the respirator. Additional information on the custom integrated filter can be found in the “Custom Filters” section.

The following subsections will describe the tools/equipment required, materials used, fabrication process, assembly guide.

## Tools and Equipment:
 * FDM 3D printer
     * Standard 0.4 mm print nozzle
     * Print area must be greater than 15x15 cm.
     * Capable of printing TPU (direct drive extruder recommended)
 * Xacto blade or similar
 * Calipers (optional)

## Materials Required:
 * PLA or PETG Filament - Used for rigid components
     * PETG is recommended for higher temperature and chemical resistance.
 * Shore 95A TPU Filament  - Used for flexible face seal.
     * Ninjaflex Cheetah and Polymaker Flex have been tested.
 * 3/8 “ Elastic Banding (36” Length) - Standard elastic banding for sewing is sufficient.
 * 3/16” Thick Foam or Equivalent - Used for the cartridge attachment point seal.
     * Compliant foam such as a contact shelf liner would work.
 * Filter Medium - An appropriate filter medium for use with the integrated filter.
     * HEPA vacuum bag material (Kenmore brand) currently recommended.
 * Note, currently *not* NIOSH certified for medical use.
     * Additional information in the custom filter section.

## Components and Fabrication
![figs/d1-f3.png](figs/d1-f3.png)
The standard version compatible with stock filter cartridges consists of only 9 components. Below is a short description of each part with fabrication guidelines. Note, the integrated filter cartridge version follows the same process but swaps the filter cartridge adaptor for the integrated filter.

### Printed Parts
 * 1x Flexible Face Seal - The flexible face seal should be printed first from a 95A TPU material in a size appropriate for the user.
     * Material - Shore 95A TPU (NinijaFlex Cheetah and Polymaker Flex have both been verified to work)
     * Print Settings - 0.2 mm layer height, 2 perimeters, 0.45 mm line width
     * Notes - If calipers are available, measure the thickness of the front lip. This value can be used to select the appropriate rigid adaptor size.
 * 1x Rigid Adaptor Plate
     * Material - PLA or PETG
     * Print Settings - 0.2 mm layer height, 3 perimeters, 0.45 mm line width, 10% infill
     * Notes - Multiple files are provided to allow for variation in print tolerances. The end
designator indicates the size fihte slot used to mount
 * 4x Strap Adjustment Clips
     * Material - PLA or PETG
     * Print Settings - Normal print settings.
     * Notes - None.

### Other:
 * 1x Filter Cartridge Seal - Reference designs respirator designs 2 &3 for instructions on
cutting the foam ring seals.
 *  2x Straps - Cut two strips to a length of 46 cm (18”). This can be increased or decreased
based on user preference.
 * 1x Integrated Filter (Option) - Instructions for the filter assembly are provided in the “Custom
Filters” section.

General fabrication notes and tips will be provided here and periodically updated based on user comments and questions.

 * *PLA is very easy to print but has a low softening temperature and is susceptible to warping at elevated temperatures (such as in the hot interior of a parked vehicle during the summer). If you expect that respirator may be stored in a location where the temperature can exceed 100 oF, the use of PETG is recommended.*

## Respirator Assembly
![figs/d1-f4.png](figs/d1-f4.png)
Once the required parts are printed, this is the basic assembly process (refer to pictures below):

 1. Prepare the flexible face seal section. Pull away any stringers and left from the printing process.
 2. Slot the top lip of the flexible face seal into the matching groove on the rigid filter cartridge adaptor plate or integrated filter cartridge. This connection is meant to be tight, and should not be loose as it seals the rigid element against the flex face seal.
     a. If the connection is either too loose or tight reprint the rigid element with the corresponding smaller or larger slot size version respectively. Groove sizes of 0.8, 0.85, and 0.9 mm will be provided (0.85 mm is default). Different printers will vary in dimensional tolerance so this will have to be checked on a case by case basis.
 3. Place the filter cartridge seal ring over the cartridge attachment point on the rigid front plate.
 4. Attached straps through the mount points on the flexible face seal using the strap clips to allow for length adjustment. Alternately the straps can simply be tied off.
 5. Attach filter cartridge if required.
 6. Test fit and adjust strap tension as required.

![figs/d1-f5.png](figs/d1-f5.png)

## Reference Images:
![figs/d1-f6.png](figs/d1-f6.png)
![figs/d1-f7.png](figs/d1-f7.png)

# Design2: JPL Comfort Respirator
## Overview
![figs/d2-f1.png](figs/d2-f1.png)
Designed to be manufactured and assembled with little expertise and non-specialized equipment. Printable in two configurations rigid and flexible. All manufacturing materials are easily found at hardware or hobby shops. The chosen 3D printable materials include PLA, PETG and Ninjatek’s Cheetah (TPU) ; these are all common and easily printable filaments with most 3D printers. All assembly parts can be made of either but there are advantages for choosing the most recommended.

![figs/d2-f2.png](figs/d2-f2.png)

## Respirator Overview
![figs/d2-f3.png](figs/d2-f3.png)
The rigid configuration requires an added peel back weatherseal EDPM rubber (*not shown*) that ensures a positive seal and wearer comfort. The flexible configuration can be configured with or without added seal edge for greater comfort and seal assurance during jaw movement.

### Tools Required
 * FDM 3D Printer (direct drive preferred)
 * Scissors / Small cutters
 * Pliers
 * PliersRuler / Measuring tape (optional)
 
### Materials Required
 * 3D printer filament (PLA, PETG, Ninjatek Cheetah TPU) “Housing & Accessories”
 * 3⁄8”-1⁄2” Elastic Bands “Headbands”
 * Contact solid grip shelf liner. “Component seals”
 * EPDM D-profile weather-seal 5/16” wide 1⁄4” thick (required for rigid housing, optional for flexible housing) “Face
seal”

### Bill of Materials
| Component|Qty|Manufacturing method|
|---|---|---|
|Housing |1|3D printed|
|Cartridge Adapter|2|3D printed|
|Adapter Nut|3|3D printed|
|Port Seal|1|3D printed|
|Component Seal|4|Hand-cut|
|Headbands|2|Hand-cut|
|Face Seal (optional for flexible housing)|1|Hand-cut|

### Build Steps
 1. *Measure mendon-sellion length*
    Mendon-sellion length (face length): The vertical distance from the tip of the chin to the deepest point of the nasal root depression between the eyes.
    ![figs/d2-f4.png](figs/d2-f4.png)
 2. *Choose the right housing STL according to size and mask configuration*
    ![figs/d2-f5.png](figs/d2-f5.png)
 3. *3D Print the respirator housing*
    The recommended material for the housing is Cheetah TPU, as this will allow housing to flex and form to the face maintaining a positive seal during face movements. To avoid layer gaps and stringing, it is recommended that you print a single housing with no other parts on the printer bed. Recommended print settings; 5 perimeters, 5 top and 5 bottom layers @ 0.20mm layer height with a .040mm nozzle to ensure proper body seal. If available, use “Extra perimeters if needed”,”Cross perimeter avoidance”, and “Thin wall detection” on slicer application. Then follow filament manufacturer guidelines for material print settings. Faster print times may be achieved with a larger nozzle but this design and settings are intended for most common 3D printer configuration.
  4. *3D Print cartridge adapter and accessories*
The most recommended material for respirators accessories is PETG, this will give you the best mechanical advantages.
   ![figs/d2-f6.png](figs/d2-f6.png) 
  6. *Cut seals and headbands*
Use the 3D printed seal template to trace and cut the seals, you can fold the seal in half to cut the inner circle.
   ![figs/d2-f7.png](figs/d2-f7.png) 
  Wrap elastic around the wearer's head without stretching it at nose level and cut two elastics of same length, alternatively you can measure out and cut one piece to approx. length of 22” and a second one to 18”, you can trim excess after a fit test if necessary.
   ![figs/d2-f8.png](figs/d2-f8.png) 
  7. *Respirator Assembly*
      * Gather all pieces
      * Install seals on both sides of the cartridge adapters
  ![figs/d2-f9.png](figs/d2-f9.png)
      * Insert cartridge adapters to side ports and port seal to front port.
  ![figs/d2-f10.png](figs/d2-f10.png) 
      * Install adapter nuts, do not tighten.
  ![figs/d2-f11.png](figs/d2-f11.png)
      * Orient the smaller cartridge key to the center of the housing.
  ![figs/d2-f12.png](figs/d2-f12.png)
      * While holding both sides tighten adapter nuts with pliers or 3D printed tool, do not overtighten.
  ![figs/d2-f13.png](figs/d2-f13.png)
      * Install headbands by inserting the long end from the back of the strap mount thru the closest to to center slot.
  ![figs/d2-f14.png](figs/d2-f14.png)
      * Continue to zig-zag the strap thru all the slots of the strap mount
  ![figs/d2-f15.png](figs/d2-f15.png)
      * Repeat this for all four strap mounts.
  ![figs/d2-f16.png](figs/d2-f16.png)


# Doing your own Fit Check (aka seal test):
Please ensure the respirator user performs a fit check before using these in a potentially hazardous setting.
We recommend the published CDC NIOSH positive and negative seal check procedure​ before using the respirator to make sure that it is of proper size and to ensure there weren't any faults during manufacturing/assembling. Do this without filter cartridges installed, ports should be easily blocked with the palms of your hands.
How to do a positive pressure user seal check

Once the particulate respirator is properly donned, place your hands over the facepiece, covering as much surface area as possible. Exhale gently into the facepiece. The face fit is considered satisfactory if a slight positive pressure is being built up inside the facepiece without any evidence of outward leakage of air at the seal. Examples of such evidence would be the feeling of air movement on your face along the seal of the facepiece, fogging of your glasses, or a lack of pressure being built up inside the facepiece. If the particulate respirator has an exhalation valve, then performing a positive pressure check may be impossible. In such cases, a negative pressure check should be performed.

## How to do a negative pressure user seal check
Negative pressure seal checks are typically conducted on particulate respirators that have exhalation valves. To conduct a negative pressure user seal check, cover the filter surface with your hands as much as possible and then inhale. The facepiece should collapse on your face and you should not feel air passing between your face and the facepiece. In the case of either type of seal check, if air leaks around the nose, use both hands to readjust the nosepiece by placing your fingertips at the top of the metal nose clip. Slide your fingertips down both sides of the metal strip to more efficiently mold the nose area to the shape of your nose. Readjust the straps along the sides of your head until a proper seal is achieved.2 If you cannot achieve a proper seal due to air leakage, you may need to be fit tested for a different respirator model or size.”

 1. [CDC NIOSH](https://www.cdc.gov/niosh/docs/2018-130/pdfs/2018-130.pdf)
 
# Resources
There are many resources for learning how to properly fit and test your respirator. See the following links for instructions:

 * https://www.youtube.com/watch?v=yBg2B2BP9nA
 * https://www.youtube.com/watch?v=DzIDhYGnDIM
 * https://www.worksitemed.com/niosh-explains-respirator-seal-checks/
 
# Disclaimer
The designs herein have not been reviewed, cleared, or approved by FDA or other regulatory authority, nor have they received Coronavirus Disease 2019 (COVID-19) Emergency Use Authorizations for Medical Devices. Neither California Institute of Technology (including the Jet Propulsion Laboratory)(“Caltech”) nor its employees or agents provide any representation or warranty, express or implied, for fitness for a particular purpose, safety, efficacy, or non-infringement of any third party intellectual property rights. Caltech offers these device designs in good faith to help healthcare providers and others prevent the spread of and treat patients with COVID-19. Physicians and other healthcare providers bear full responsibility to convey warnings and obtain patients’ informed consent.

# Acknowledgement
The research was carried out at the Jet Propulsion Laboratory, California Institute of Technology, under a contract with the National Aeronautics and Space Administration​.
