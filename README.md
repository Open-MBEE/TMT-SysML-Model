# TMT-SysML-Model
### Welcome to the Thirty Meter Telescope SysML model
The Thirty Meter Telescope ([https://www.tmt.org](TMT)) system that is currently being
developed by the TMT Observatory Corporation. The main objective for the TMT related
analysis is to provide state-dependent power roll-ups
for different operational scenarios and demonstrate that requirements are satisfied by the design as well as mass roll-ups and duration analysis of the operational use cases.

The core of the system is a wide-field,altitude-azimuth
Ritchey-Chretien telescope with a 492 segment, 30 meter diameter primary mirror, a fully active secondary mirror and an
articulated tertiary mirror. The Alignment and Phasing System is a Shack-Hartmann
(SH) wavefront sensor responsible for the overall pre-adaptive optics wavefront quality of the
TMT.

The model is built with an approach to model-based
systems analysis with SysML that is both rigorous and automated. The approach supports the kind of system analysis we mentioned
earlier, i.e., requirements verification. The approach’s rigor is established with a modeling
method that is an extension of INCOSE’s Object Oriented Systems Engineering
Method (OOSEM). The extension, dubbed Executable System
Engineering Method (ESEM), proposes a set of analysis design patterns that are specified with
various SysML structural, behavioral and parametric diagrams. The purpose of the patterns spans
the formalization of requirements, traceability between requirements and design artifacts,
expression of complex parametric equations, and specification of operational scenarios for
testing requirements including design configurations and scenario drivers. Furthermore, the
approach is automated in the sense that the analysis models can be executed. The execution of
the parametric diagrams is done with a parametric solver, where the execution of the behavioral
diagrams is done with a simulation engine based on standard execution semantics.

The model was presented at:
- [SPIE June 2016, Edinburgh](https://www.youtube.com/watch?v=VcXLUf-cfLY)
- [NoMagic World Conference](https://vimeopro.com/user28256466/no-magic-world-symposium-2016/video/171045570)

Further information on telescope modeling and other telescope projects applying MBSE techniques can be found on
[INCOSE's MBSE Wiki](http://www.omgwiki.org/MBSE/doku.php?id=start)

You need MagicDraw 18.0 and CST 18.5 to run the simulations.
In order to load the model you require also to intall the Model Development Kit ([MDK](https://github.com/Open-MBEE/MDK))


