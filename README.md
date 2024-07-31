**WARNING** This documentation is currently under active development. The content and structure may change as the project evolves. Please check back regularly for updates and improvements.

# MIT RailSim Documentation

Welcome to the MIT RailSim documentation! While the full package isn't open-source right now, this documentation is a great way to learn about the capabilities of the rail simulation tool. Built on decades of research at (MIT Transit Lab)[https://www.transitlab.mit.edu/], RailSim enables you to simulate operations of an urban rapid transit metro line operations under Fixed-block or Moving-block signal system, integrating real-time control strategies, and finally analyzing the performance of the system from operator's or passenger's perspective.

Whether you're a transportation professional, academic researcher, or just a rail enthusiast, this documentation will help you understand how RailSim works and what it can do. Check out the guides, dive into the architecture reference, and start exploring how RailSim could help with your own projects or research.

## Key Documentation Files

The complete documentation is available as a PDF file: [MIT RailSim Documentation](_build/latex/mitrailsim.pdf).

An online version is also available through Github Pages at [myousefi.github.io/mit-rail-sim-docs/](https://myousefi.github.io/mit-rail-sim-docs/).

## Additional Resources

For further information and resources, refer to the appendix. It contains a glossary of terms used throughout the documentation and provides links to additional dissertations, and relevant papers.

If you have any questions or need assistance, please reach out to Mojtaba Yousefi at [m@ysfi.me](mailto:m@ysfi.me).

Happy learning with MIT RailSim!

## Citation

If you use this software in your research, please cite it using the following metadata:

```yaml
cff-version: 1.2.0
message: "If you find this software useful for your work, please cite it as below."
authors:
    - family-names: "Yousefi"
      given-names: "Mojtaba"
      orcid: "https://orcid.org/0000-0002-2671-1295"
    - family-names: "Koutsopoulos"
      given-names: "Haris N."
      orcid: "https://orcid.org/0000-0003-3830-9794"
title: "MIT RailSim: A Modern Rail Transit Simulation Platform"
version: 1.0.0
doi: https://doi.org/10.5281/zenodo.13111727
date-released: 2024-06-01
url: "https://myousefi.github.io/mit-rail-sim-docs/"
repository-code: "https://github.com/myousefi/mit-rail-sim-docs"
keywords:
    - research
    - software
    - transit
    - urban heavy rail
    - MIT Transit Lab
    - performance evaluation
    - signal system
    - microspopic simulation
    - object-oriented design
    - modular
    - fixed-block
    - moving-block
    - design pattern
abstract: >
    MIT RailSim is an urban heavy-rail operations simulation model developed at the MIT Transit Lab, built upon decades of research. This repository contains a comprehensive documentation. While the full package may not be open-sourced soon, the documentation provides valuable insights into the capabilities of the simulation model.
references:
    - type: article
      authors:
          - family-names: "Koutsopoulos"
            given-names: "Haris N."
          - family-names: "Wang"
            given-names: "Zhigao"
      title: "Simulation of Urban Rail Operations"
      year: 2007
      journal: "Transportation Research Record"
      volume: 2006
      pages: "84-91"
      url: "https://api.semanticscholar.org/CorpusID:110620690"

    - type: inproceedings
      authors:
          - family-names: "Wang"
            given-names: "Zhigao"
          - family-names: "Koutsopoulos"
            given-names: "Haris N."
      title: "Calibration of urban rail simulation models: a methodology using SPSA algorithm"
      year: 2011
      booktitle: "Proceedings of the Winter Simulation Conference"
      location: "Phoenix, Arizona"
      publisher: "Winter Simulation Conference"
      series: "Wsc '11"
      pages: "3704–3714"
      abstract: "Rail simulation model calibration is a process of adjusting model parameters while comparing model output with observations from the real rail system. There is a lack of systematic methodology for calibrating urban rail simulation models. Based on a simulator developed for urban rail operations and control, the paper demonstrates a methodology of calibrating model parameters, and specifically, fine-tuning some of the simulation inputs. The calibration process is modeled as a multi-variate optimization problem and solved by the Simultaneous Perturbation Stochastic Approximation (SPSA) algorithm. A case study of the Massachusetts Bay Transportation Authority (MBTA) Red Line shows that the methodology improves the simulation model dramatically in terms of replicating the track block runtimes. At the same time, it upgrades the station specific dwell time parameters and enhances a-priori boarding rates at stations fairly effectively."
      numpages: 11

    - type: article
      authors:
          - family-names: "Zhou"
            given-names: "Jiali"
          - family-names: "Koutsopoulos"
            given-names: "Haris N."
          - family-names: "Saidi"
            given-names: "Saeid"
      title: "Evaluation of Subway Bottleneck Mitigation Strategies using Microscopic, Agent-Based Simulation"
      year: 2020
      journal: "Transportation Research Record"
      volume: 2674
      pages: "649-661"
      url: "https://api.semanticscholar.org/CorpusID:218922083"

    - type: phdthesis
      authors:
          - family-names: "Zhou"
            given-names: "Jiali"
      title: "Urban rail simulation and applications in service planning and operations"
      year: 2022
      school: "Northeastern University"
      publisher: "Northeastern University Library"

    - type: article
      authors:
          - family-names: "Zhou"
            given-names: "Jiali"
          - family-names: "Koutsopoulos"
            given-names: "Haris N."
      title: "Schedule-based Analysis of Transmission Risk in Public Transportation Systems"
      year: 2022
      journal: "ArXiv"
      volume: "abs/2202.08505"
      url: "https://api.semanticscholar.org/CorpusID:246904579"
```
