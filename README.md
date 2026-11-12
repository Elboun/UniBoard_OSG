# UniBoard OSG: Project Description

* OSG stands for Open Synthesis Gateway.

## The core Problem

Heavy HDL tools like Vivado lack native macOS ARM support, forcing students onto VMs that throttle local hardware limits.

## The solution

Open-Synthesis Gateway web portal (& REST API) where students write HDL locally and submit archives/ single files to a high-performance university node that handles synthesis, implementation, and bitstream generation.

## LLM-based diagnostics

Parses verbose Vivado synthesis log files and outputs concise, actionable code fixes directly in the web dashboard (or IDE extension).

## Missing Elements

* Enforce .gitignore-style exclusion filters so only .v/ .vhd/ .xdc files are uploaded.

* Implement strict hard timeouts with automatic container termination.

# User Stories

* As a student, I want to write FPGA Code in a browser environment like VS Code in browser so that I can get the status of the code as working or not.

* As a student, I want to write FPGA Code in a browser environment like VS Code in browser so that I can get the suggestion to fix code if it is not correct.
* As a student, I want to write FPGA Code in a browser environment like VS Code in browser and get back the binaries to upload to an FPGA board.
* As a student, I want to see a live indicator of my synthesis job so I know how long I still need to wait.
* As a student, I want to write FPGA Code in a browser environment like VS Code in browser and get back the chip design.
* As a student I want to be able to upload Verilog/ VHD files or zip.
* As a student I want to see my last Synthesis Jobs so I can go back into an older job.
* As a professor I want to observe which student has submitted which work and be able to give notes/ comments.
* As a professor I want to view the system-wide resource usage or active jobs so that I can ensure the server isn’t overloaded.

