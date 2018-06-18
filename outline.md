Prior to Hackathon (After SWC)
###

Instructions will be needed for each of the following:

* Conda installation of Python (if not done from SWC)
* checkout hackathon repo
* Install ZeroMQ
* Install Matlab Python engine (optional)
* `pip install cis_interface`
* Run limited test suite from hackathon instruction materials


1. Introduction & Overview
    1. Location of repo & documentation
    1. Survey operating systems, existing models, and programming languages
1. Debug setup & installation to ensure everyone on same page
1. Worked Example
    1. Converting a model
        1. Introduce fake model in Python without API calls (provide examples in other languages)
        1. Convert model to be function
        1. Write script w/ API calls
            * Review general structure of the calls
            * Touch on existence of complex I/O
    1. Creating a YAML for model information using web form
        1. Supported languages (touch on compilation of C/C++ with gcc/clang/make/nmake/cmake)
        1. Supported input/output types
        1. Units
        1. Download & Placement of YAML
    1. Creating a YAML for model-to-file integration
        1. Creating files
        1. Selecting file types
        1. Selecting paths
        1. Download & Placement of YAML
    1. Running model-to-file integration
        1. `cisrun` overview
        1. Debugging
        1. Checking output
    1. Creating a YAML for model-to-model integration
        1. Introduce other models that are part of the course materials (already have existing yamls)
        1. Making connection on UI
        1. Options for connections between models
        1. Download & Placement of YAML
    1. Running model-to-model integration
1. Existing public models
    1. 5 minutes for each model scientist to discuss their models
        * General purpose of the model
        * Inputs
        * Outputs
1. Break for actual hacking
    * Split groups by language to make debugging easier