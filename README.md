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
