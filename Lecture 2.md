# Definition

## IMEI - International Mobile Equipment Identifier
---
- A 15 digital number (last number is the check digit)
- “Serial number” of the handset, Analagous to chassis number of a car
- Intended to be unique
- Can be re-programmed with specialist equipment (illegal)
- IMEI can reveal: Make, model, date and country of origin


# Questions from Lab 2 - Lab/NFI Lab 02 - Mobile Devices and Digital Forensic Investigation

- Can you identify pictures shared between the two extractions?  How many shared pictures are there?   
    > 8
- How can you identify where the pictures were saved (on the phone or memory card)?  
    > Look at the path of the file
- Can you notice any differences between pictures extracted from memory of the phone and pictures extracted from the memory card present on the phone? 
    > MAC timestamp is presented on all pictures saved on the memory card.
- In both extracted files look at the audio files extracted.  How many shared audio files are there?  
	> 17 
- In Sony Ericsson W800i with memory card, how can you identify which audio is extracted from the memory card?  
    > Audio extracted from the memory card has MAC timestamp and the path is different.
- What is the video format(s)? 
    > .3gp,  .avi
- Can you play videos? 
    > Yes
- What artefacts can you identify on the memory card?  
    > Pictures
- How many pictures are available?  
    > 146
- Can you identify the pictures that were taken by a mobile camera?  What is the model of the camera?
    > Under MetaData, Equipment Model: BlackBerry 9500
- Can you identify what hash algorithm is used?  
    > SHA1
- Can you identify what sort of files some of them might be?  
    > Music files but the extension cannot be identified by XRY
