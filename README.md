# windbird-electronics

This repository contains the electronic parts of the Windbird wind sensor.

![carte-wb-0 2](https://user-images.githubusercontent.com/1681443/199285619-ba5c6d7a-b398-466e-abd2-0d190b02ab8b.jpg)

- main/            : contains the main PCB 
- front/           : contains the PCB for the rotation sensor
- tail/            : contains the PCB for the tail and antenna
- datasheets/      : components datasheets
- Parts.ods        : parts list, refs, suppliers and price
- kicad_libraries/ : Kicad libraries

The development branch is named **'main'**

Releases : https://github.com/windbird-sensor/windbird-fox-electronics/releases

## Reminders about versioning with git

- To collaborate, initiate the project with:

  git clone https://github.com/windbird-sensor/windbird-electronics
    
- To share changes:

  git pull --rebase origin main  
  git push origin main  

- If you added tags (git tag TAG COMMIT) do the push with: 

  git push origin main --tags


## License

Copyright (c) 2015 Bac Plus Zéro SAS

Copyright (c) 2016 Altostratus SA

Copyright (c) 2021-2023 OpenWindMap SCIC SA and contributors

**Permission is granted to anyone to use this Material for any purpose, including commercial applications, and to alter it and redistribute it freely, subject to the following restrictions:**

**ATTRIBUTION:** You must give appropriate credit, provide a link to the license, and indicate if changes were made. You may do so in any reasonable manner, but not in any way that suggests the licensor endorses you or your use.

**SHARE-ALIKE:** If you remix, transform, or build upon the Material, you must distribute your contributions under the same license as the original. You must include a copy of this License with every copy of this Material or modified version of this Material You distribute or otherwise make available.

**OBLIGATION TO SHARE WITHIN THE OPENWINDMAP NETWORK:** If you use this Material or a modified version of this Material to build a product that collects environmental data, this data must be published within the OpenWindMap network. You must not intentionally degrade the quality of the data, reduce the accuracy of its geolocation or delay its dissemination.

**OPEN-DATA:** If you use this Material or a modified version of this Material to build a product that collects environmental data, this data should be published under an Open-Data license. The chosen license must allow free reuse and redistribution, including from commercial entities and for commercial use. The choosen license must either be compliant with the [Open Definition](https://opendefinition.org/od/2.1/en/) or receive approval from OpenWindMap's board. You are allowed to offer a version of this data under any other license of your choice (including non-free licenses), as long as you also provide an identical version of this data under an Open-Data license as defined in this paragraph.

**DISCLAIMER OF WARRANTY/LIMITATION OF REMEDIES:** OpenWindMap and its contributors have no obligation to support this Material. OpenWindMap and its contributors are providing this Material "AS IS", with no express or implied warranties of any kind, including, but not limited to, any implied warranties of merchantability or fitness for any particular purpose or warranties against infringement of any proprietary rights of a third party.

**OpenWindMap and its contributors will not be liable for any consequential, incidental, or special damages, or any other relief, or for any claim by any third party, arising from your use of this Material.**

For the avoidance of doubt, OpenWindMap may offer this Material under separate terms or conditions or stop distributing this Material at any time; however, doing so will not terminate this License.
