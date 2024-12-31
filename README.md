# Talons

This is a collection of cybersecurity tools built by the Blugold Group, the cybersecurity club of University of Wisconsin - Eau Claire for use in Capture The Flag competitors and network security engagements. Together they are  called TALONS (Tactical Arsenal for Lateral Operations in Network Security)

It consists of three separate tools.

**Note:**: The lists below contain **plans** for tools, not all of them are completed at the time of writing

### Bletchley

A cryptanalysis suite. Includes

* Encryption/Decryption with dozens of ciphers
* Automatic detection and decryption of ciphertext
* Automatic detection and decoding of encodings
* Classification of hash type, provides commands for use by hashcat  

Named after Bletchley Park, where the Allies broke German ciphers during the second world war and created the basis for modern computing in the process.

### Uhura

A set of tools to convert language into different forms, including

* Written language to written language
* [OCR](https://en.wikipedia.org/wiki/Optical_character_recognition)
* Convert written symbolic based languages (morse code, braille)
* Converting never-before-seen written shapes to language representations for cryptanalysis using on-the-fly machine learning model building


The tools are meant to work together, passing inputs and outputs between each other to extend the capabilities of each one

Named after Nyota Uhura, a communications officer in Star Trek

### Water Bottle

A set of scripts which run basic file forensics tasks, including

* Detection of metadata
* Detection of embedded strings/files
* Stenography
* Pixel Value Differencing

Named after the water bottle Ben Gates uses the uncover the seal of the Charlotte in the film National Treasure

## Experimental Tools

These are tools which have been proposed, but have not been built due to a lack of willing and available developers and/or technical infeasibility

* Cosine - A tool which read the electrical signals between wires to read information flowing through a computer (IE cryptographic keys from a TPM chip). The original idea has been done already (https://www.pcgamer.com/microsofts-bitlocker-and-tpm-encryption-combo-defeated-with-a-dollar10-raspberry-pi-and-a-bit-of-braininess/)

* Garak - A tool which can classify keypresses using only the audio of a user typing on a keyboard, has been done already (https://arstechnica.com/gadgets/2023/08/type-softly-researchers-can-guess-keystrokes-by-sound-with-93-accuracy/), (https://ieeexplore.ieee.org/abstract/document/10190721)

* Bashir - A tool which can use lasers and the vibrations of objects like glass or lightbulbs to eavesdrop on audio from a room a long distance away (https://www.wired.com/story/lamphone-light-bulb-vibration-spying/), (https://www.wired.com/story/infrared-laser-microphone-keystroke-surveillance/)

* Rock - A tool which automates lock picking (https://www.youtube.com/watch?v=QE9MT1LG-PU)

## Installation

### Linux

Setup instructions to come

### MacOS

Setup instructions to come

### Windows

Switch to Linux

## Development

Because this repo uses git submodules to track uhura, blethley, and waterbottle, development gets a little more complicated.

To manage requirments.txt files, the setup.sh script creates a overall requirments.txt which provides the tools for all of the tools' requirments files. This doesn't happen on the repo level for various merge conflict issues. 

