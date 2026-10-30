# UniBoard OSG: Project Description
* OSG stands for Open Synthesis Gateway.
## The core Problem:
Heavy HDL tools like Vivado lack native macOS ARM support, forcing students onto VMs that throttle local hardware limits.
## The solution:
Open-Synthesis Gateway web portal (& REST API) where students write HDL locally and submit archives/ single files to a high-performance university node that handles synthesis, implementation, and bitstream generation.
## LLM-based diagnostics:
Parses verbose Vivado synthesis log files and outputs concise, actionable code fixes directly in the web dashboard (or IDE extension).
## Missing Elements:
- Enforce .gitignore-style exclusion filters so only .v/ .vhd/ .xdc files are uploaded.
- Implement strict hard timeouts with automatic container termination.


