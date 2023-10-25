# Polymers-Kinetic-Mechanisms

Condensed-phase polymer degradation kinetic Mechanisms. Evaluation of gas-phase
pyrolytic and gasification reactivity are underway at CRECK modelling POLIMI.
The kinetic mechanisms are reported also on the [creckmodelling website](https://creckmodeling.chem.polimi.it/)

The folders are organized by polymer type.
The kinetic mechanism proposed are of the semi-detailed kind employing a
functional group approach:
- Long polymer chains are described with functional groups characteristic of
    the polymer moieties (mid- and end-chain groups) recognized by the "P-" in
    their name
- Short chains, i.e. compounds of interest, are described with real species as
    C2H4, C15H30, etc

For polyethylene several mechanisms of different complexity are available.
Thermochemistry has been validated for PE, while for PS it has been implemented
but without quantitative validation yet.
Transport parameters are evaluated with a simplified approach based on critical
temperatures and pressures (see [Holley et al. 2009](http://dx.doi.org/10.1016/j.proci.2008.05.067)).
PP has a significantly expensive mechanism which will be simplified in line with
PE.

Further work will address development of:
- PET, PA, PU, and PMMA semi-detailed condensed-phase kinetic mechanism
- PE secondary gas-phase reactions
- Interactions in PET-PVC-PA mixtures
- Fully lumped model (<10 species) for CFD applications

To cite the Kinetic Mechanism refer to the following publications:
- PE, PP  [10.1016/j.wasman.2022.11.028](https://www.sciencedirect.com/science/article/pii/S0956053X22005633)
- PS      [10.1016/j.jaap.2023.105960](https://www.sciencedirect.com/science/article/pii/S0165237023001043)
- PVC     [10.1016/S0165-2370(03)00024-X](https://www.sciencedirect.com/science/article/pii/S016523700300024X)
