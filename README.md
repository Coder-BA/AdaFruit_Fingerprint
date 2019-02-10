# AdaFruit_Fingerprint
Includes the Library with the added functionality (MaxPageNumber and Up To 1000 FingerPrints)
The Default Library can only handle the fingerprints up to 255 due to the defined variable type as "uint8_t". 
However, if the type is updated as "Word" (uint16_t), the code can process more than this (up to 0xFFFF 
depending on the sensor capability).

Additionally, to be able to get the maximum Page Number that the sensor can store, 
the code has a procedure called as "getMaxPageNumber()".

To reflect the changes into your files:
1. Check the references section of Arduino Program and find out the location of AdaFruit_Fingerprint Library files you have already copied before.
2. Replace the files covered in this project with the files in your computer or copy the attached files to your computer after renaming the previous files. 
