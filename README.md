## Miniaturized plate reader designs
This repository provides all the materials needed to assemble a miniaturized plate reader for measuring optical density in 96-well plates. 

Code is available at: https://github.com/csbl/PlateReaderCode

-- 
### File Descriptions
* Assembly Instructions.docx -- Instructions for assembling PCBs, loading code onto Arduinos, and running experiments.
* Parts List.xlsx -- Quantity, pricing, and availability information for all electrical and structural components.
* schematics
    + Frame_Drawings -- SolidWorks technical drawings for machining the aluminum frames.
    + PCBs -- Layout files for three printed circuit boards:  the emitter/detector layout boards (EmitterDetector), the controller shield for an Arduino Mega (MegaShield), and a breakout board for the XBee wireless chip (XBeeBreakoutBoard).
        - .pcb files for ExpressPCB software (http://expresspcb.com/).  We ordered our boards directly from this vendor using their free software.
        - To order boards from other vendors, we have included folders with Gerber files.  These files were provided by ExpressPCB.  Unfortunately, we have not ordered boards using the drawings, so we cannot guarantee their validity.  The file descriptions are:
            * .SLK = top silkscreen layer
            * .SMT = top solder mask layer
            * .TOP = top copper layer
            * .BOT = bottom copper layer
            * .SMB = bottom solder mask layer
            * .DRI = drill file
            * .OLN = board outline
        

