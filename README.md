# 8-bit-SRAM-physical-layout-design
Physical Layout Design of 8-bit SRAM using Cadence
This repository contains the physical layout design of an 8-bit SRAM using Cadence Virtuoso. It includes key files such as LVS, DRC, and extracted views, allowing for detailed verification and analysis of the design.

Table of Contents
Introduction
Main Project: 8-bit SRAM
Tools Used
Installation and Setup
Layout Verification
License
Introduction
The project focuses on the physical layout and verification of an 8-bit SRAM, including design-rule checking (DRC), layout versus schematic (LVS) checks, and RC extraction. The layout is designed using Cadence Virtuoso, and this repository contains all the necessary files for analyzing the design.

Main Project: 8-bit SRAM
The layout for the 8-bit SRAM is the centerpiece of this repository, showcasing the design’s:

LVS file: Ensuring the layout matches the schematic.
DRC file: Verifying that the layout follows design rules.
Extracted file: Providing the RC parasitic extraction data for post-layout simulation.
Tools Used
Cadence Virtuoso: For physical layout design and verification.
Assura: For DRC and LVS checks.
Calibre (optional): For additional verification steps.
Installation and Setup
Cadence Virtuoso Installation
Download the cracked version of Cadence Virtuoso using the link provided: Download Link.

The file is around 13GB. After downloading, refer to the following YouTube tutorial for installation instructions:

Installation Tutorial
Setting Up the Project
Download the project zip file from this repository.
Copy the zip file to your guest OS (if using a virtual machine) using drag-and-drop.
Untar the file using terminal commands:
bash
Copy code
tar -xvf <zipfile_name>.tar.gz
Navigate to the extracted folder, open the terminal, and launch Cadence Virtuoso.
In Virtuoso, select the SRAM library and open the 8-bit SRAM layout file.
You can now view and run the schematic, layout, and extracted views for the project.
Layout Verification
The project includes verification steps such as:

DRC: To ensure that the layout adheres to the foundry’s design rules.
LVS: To compare the layout with the original schematic, ensuring they match.
RC Extraction: The extracted file provides the parasitic resistances and capacitances for post-layout simulation.
These steps ensure the accuracy of the design and its manufacturability.

License
This project is licensed under the MIT License. See the LICENSE file for details.
