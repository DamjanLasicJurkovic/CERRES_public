<p align="center">
  <img src="https://raw.githubusercontent.com/DamjanLasicJurkovic/CERRES_public/master/CERRES_logo_webpage.png" alt="CERRES logo image">
</p>

<link rel="shortcut icon" type="image/ico" href="favicon.ico">

## About
CERRES (Chemical Reaction and Reactor Engineering Simulations) is a program designed for the simulation of various types of chemical reactors under different operating conditions with user-supplied chemistry, allowing for complex bulk and surface reaction (micro)kinetics. Furthermore, it provides additional modes of operation such as the comparison of the model results to experimentally measured values and reaction rate parameter optimization (fitting). The main goals of the software are computing efficiency, ease of use and wide functionality. CERRES is being developed by Damjan Lašič Jurković at the Department of Catalysis and Chemical Reaction Engineering at the National Institute of Chemistry in Ljubljana, Slovenia. The software is written in a combination of Python, C++ and C.

## Features
#### Simulation of different types of chemical reactors
The user can choose between a multitude of different reactor types, including simple batch reactors, CSTR reactors, plug flow reactors, 2D channel reactors and membrane reactors, some of which are supporting three-phase systems (gas, liquid and catalyst). Furthermore, there is a vast amount of different available mass transport phenomena to model in these reactor types, such as convective and diffusive/dispersive mass transport, intra- and extra-particle mass transfer limitations, phase transfer mass transfer limitations and permeation through a membrane.
#### Complex user-defined chemistry
The chemical reaction systems in CERRES are highly customizable, allowing for complex networks of hundreds of surface and bulk reactions between different species. In addition, users can supply user-defined reaction rate expressions for each of the reactions.
#### Model-experiment compare, parameter optimization, sensitivity analysis
CERRES includes various additional modes of operation besides plain reactor simulations. Using measured experimental data, the model results can be easily compared to experiments, and parameter optimization can be performed to improve the model predictive power. Additionally, sensitivity analysis can identify the most important reactions in the model network.
#### Efficient computation
Efficient computation is one of the main focuses of the software, which allows fast simulations even for large systems with highly stiff numerical characteristics. This is achieved through a powerful backend written in C, which includes robust BDF solvers, multi-threading, automatic generation of Jacobian matrices for the differential equations and on-the-fly dynamic generation and compilation of critical code segments.
#### Ease of use
The program is used exclusively through a user-friendly GUI, which requires no coding/scripting skills whatsoever. Furthermore, chemistry and experimental data editors are provided for easy preparation and handling of input files.
#### Relevant examples from literature
Multiple relevant examples from literature references are included, which can also be used as a baseline for other models. We encourage users to submit their input files from publications, so we can include them in the examples for future releases, promoting the research, allowing for easy result reproduction and improving the example database.

## Installation
CERRES is supported for Microsoft Windows (7, 8.1 and 10) for x64 compatible architectures. Please note that currently a beta version is available, so some bugs may still be present. The installation procedure is as follows:
- Download the installer (above)
- Run the installer and complete all the steps
- CERRES should now be ready to use
- To test whether everything works correctly, run the program, then select 'Run CERRES test' from the 'Help' menu

NOTE: The installer simultaneously installs the GNU GCC compiler (from the MinGW-w64 distribution), which is called by CERRES during execution. It is installed in the same folder and removed during CERRES uninstallation.

## License
The usage of the program is free of charge for any academic, educational or personal use, we only require the users to cite this webpage and later the main CERRES paper (not yet released) in any scientific publications containing results obtained by the program. For commercial/for-profit use, please contact the developers. Please see the [CERRES license](https://www.cerres.org/LICENSE_CERRES.txt) for more information.

Bundled in the installer is also a pre-built GNU GCC compiler (MingGW-w64 distribution), which is covered under its own GNU GPL-type [license](https://www.cerres.org/LICENSE_MinGW-w64.txt). Its source code is available in the public CERRES repository on [GitHub](https://github.com/DamjanLasicJurkovic/CERRES_public) (mingw-w64-v7.0.0.zip).

## Acknowledgments
We are thankful to the developers of [open-source projects used by CERRES](https://www.cerres.org/libs.html).

## Contact
We are always happy to receive any feedback, comments, bug reports or suggestions for additional features!

While CERRES is still maintained by Damjan Lašič Jurković, he is no longer employed at National Institute of Chemistry. You can contact him via damjan.lasic@gmail.com. It is preferred to send any feedback, suggestions, discussion or bug reports to this e-mail.

For more official enquiries, such as commercial use, please contact the department head:

prof. dr. Blaž Likozar<br>
[Department of Catalysis and Chemical Reaction Engineering](https://www.ki.si/en/departments/d13-department-of-catalysis-and-chemical-reaction-engineering/)<br>
[National Institute of Chemistry](https://www.ki.si/en/)<br>
Hajdrihova 19<br>
1000 Ljubljana<br>
Slovenia<br>
e-mail: blaz.likozar@ki.si<br>
![KI logo](https://raw.githubusercontent.com/DamjanLasicJurkovic/CERRES_public/master/KI_logo_small.png)
