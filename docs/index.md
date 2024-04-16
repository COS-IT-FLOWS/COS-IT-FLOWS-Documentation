# CoS-IT-FloWS

| CoS-iT-FloWS Links & Badges              |                                                                             |
|------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| CoS-it-FloWS Documentation      | [![Documentation Status](https://readthedocs.org/projects/cos-it-flows-documentation/badge/?version=latest)](https://cos-it-flows-documentation.readthedocs.io/en/latest/?badge=latest)        |
| License                | [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://raw.githubusercontent.com/UW-Hydro/VIC/master/LICENSE.txt)                                                              |
<!-- | Current Release DOI    | [![DOI](https://zenodo.org/badge/7766/UW-Hydro/VIC.svg)](https://zenodo.org/badge/latestdoi/7766/UW-Hydro/VIC) | -->

----------

## Table of Contents

+ [About](#about)
+ [Overview](#overview)
+ [Key Features](#key-features)
+ [Tech Stack](#tech-stack)
+ [Usage](#usage)
+ [License](#license)
+ [Help and Support](#help-and-support)

## About

This repository serves as the public source code repository of the **Community Sourced Impact Based Flood Forecast and Early Warning System**, termed **CoS-IT-FloWS**.

CoS-IT-FloWS is being developed at EQUINOCT CoSMoS under the UNICEF Office of Innovation's Venture Capital Fund, that supports and guides their inaugural climate cohort of 8 startups from around the world to build Open Source tech solutions for sustainable climate action.
All development activity is coordinated through the CoS-IT-FloWS github page, where you can also find all archived, current, beta, and development versions of the system.

## Overview

CoS-IT-FloWS is a Decision Support System Dashboard that uses real time monitoring to provide hyper local flood forecasting and to issue multi-hazard warnings on a local self government level. It aims at leveraging metereological and infrastructural data such as rainfall, groundwater and reservoir levels to accurately predict region-wise flood probability, utilising both hydrological and machine learning approaches.

## Open Source

We encourage any users who have modified (or would like to modify) CoS-IT-FloWS, either to fix bugs or develop new features, to contact us and coordinate development work with us. The CoS-IT-FloWS system source code is archived in Git and is publicly available through GitHub. To access the source code, visit GitHub, create an account, and visit [github.com/COS-IT-FLOWS/COS-IT-FLOWS_app](https://github.com/COS-IT-FLOWS/COS-IT-FLOWS-Documentation).

CoS-IT-FloWS is an open source development model and is released under the terms of the [MIT License](./License.md).

Instructions for using Git and GitHub to access the CoS-IT-FloWS code and contribute changes are here:

[Working with GIT and GitHub](./UserGuide.md)

## Key Features

1. Hyper local Flood Inundation Mapping using bi-directional LSTM-CNN model.
2. GATHER: community data collection app made using Flutter framework.
3. River basin impact based level flood forecasting system.
4. Multi-hazard warnings.
5. Customizable dashboard depending on use-case.
6. Flood prediction leveraging Variable Infilteration Capacity Model <!-- link -->.

## Tech Stack

![diagram](./cos-it-flows.png)

**Frontend:** React.JS + Maplibre

**Backend:** Django

**Database:** PostgreSQL

## Usage

Each new implementation addresses new problems and conditions that the system may not currently be able to handle, and as such the system is always under development. CoS-IT-FloWS is an open source development project, which means that contributions are welcome, including to the CoS-IT-FloWS documentation.

By placing the original source code archive on GitHub, we hope to encourage a more collaborative development environment. A guide on how to use the CoS-IT-FloWS git repository and [how to contribute](./Contribute.md) your changes to the system can be found on the git page. The most stable version of the system is in the main branch, while beta versions of releases under development can be obtained from the development branches of this repository.

CoS-IT-FloWS has an incremental nature of development due to which not all sections of the code are equally mature and not every combination of system options has been exhaustively tested or is guaranteed to work. While you are more than welcome to use CoS-IT-FloWS in your own research and development undertakings, the system code comes with no guarantees, expressed or implied, as to suitability, completeness, accuracy, and any other claim you would like to make.

If you make use of this system, please acknowledge all references appropriate to the features you used that are cited in the [CoS-IT-FloWS Documentation](https://readthedocs.org/projects/cos-it-flows-documentation/).

## License

CoS-IT-FloWS is released under the [MIT License](./License.md).See the `License` file for more information.

The CoS-IT-FloWS documentation content is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

![CC BY-SA 4.0](https://i.creativecommons.org/l/by-sa/4.0/88x31.png)

## Help and Support

If you have any questions, feedback, or suggestions, please feel free to reach out to us . You can raise an issue in the issue tracker.
