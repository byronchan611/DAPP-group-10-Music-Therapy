# DAPP-group-10-Music-Therapy

## Description
We are a group of 10 second year Biomedical Engineering students from Imperial College London.
The project our group undertook sought to create and provide stroke survivors with a different, 
more affordable method of rehabilitation, using music as a tool to practice rhythm-led movements 
alongside a supervising physiotherapist. 
For full description, please visit www.bme10.co.uk. Product Specification and User Manual is 
embedded as a pdf document, by clicking the link the user will be directed to the respective 
document.

## Installation
In this repository, we have all the codes that we did on Arduino and Python. For demonstration 
purposes, a simpler version is created. The demonstration version has only one octave with a range 
of notes from C4 to C5, which are labelled as note 1 to 8 in _Demo Day V2_. For the complete 
functionality of the device, download _Two octaves_ which plays notes for two octaves from C3 to C5.
To get the code to work, upload these codes to an Arduino Nano 33 BLE board, which is connected to
a buzzer at pin number 10.
The user interface was coded using Python and could be found in _Interface.zip_. The score displays 
the numbers of the notes to ensure that it can be understood by any individual, even those who are 
unable to read music. Once the patient matches the angle on the second row, the angle updates to show 
the next angle they must match.
