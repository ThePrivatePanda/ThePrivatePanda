## Parth Mittal

Computer science at Cornell, class of 2028. I build a wide range of software: simulators, radios, navigation, libraries, games. The domain changes between projects. What I care about in each one is the design: how it's layered, where the interfaces sit, and how it behaves when something fails. I'm heading toward aerospace.

**Now:** junior year at Cornell, writing flight software for the Cornell SSDS ChipSat team, and looking for 2027 internships in software and aerospace.

**Flight software and research**

- [ChipSat flight software](https://privatepanda.co/research/chipsat/) (Cornell Space Systems Design Studio): a chipsat is a gram-scale, single-board spacecraft, released near 100 km and transmitting telemetry over LoRa the whole way down. I rebuilt the flight software from an Arduino sketch into a CMake project on STM32 and rewrote the Rust ground software that configures and flashes the boards. Three layers, one interface per peripheral with two implementations behind each, so drivers could be ported one at a time against a build that still flew. Six drivers written against datasheets, replacing vendor libraries whose bugs I traced by reading their source. Flight logic is tested on a laptop against mocks, because there is no spacecraft on my desk. Two launches this semester. The lab's repository is private.
- [compute-location-moo](https://github.com/ThePrivatePanda/compute-location-moo): multi-objective optimization for where a spacecraft should run its computation, onboard, in orbit, on the ground or in the cloud. The code behind a paper under review at the AIAA Journal of Aerospace Information Systems (second of four authors).
- [Roman Coronagraph target database](https://privatepanda.co/research/roman-db/) ([corgidb](https://github.com/roman-corgi/corgidb)): a Python query client and star-alias resolution for the database of stars the instrument may observe, at Cornell SIOSLab. Published at SPIE Astronomical Telescopes + Instrumentation 2026, [arXiv:2608.17152](https://arxiv.org/abs/2608.17152).

**Other work**

- [Meddler](https://privatepanda.co/projects/meddler/): a deterministic world simulator you can pause, rewind and fork, then watch the future you caused run beside the one that was coming. In development.
- [TypeKeeper](https://github.com/PrivatePandaCO/TypeKeeper): one decorator that checks Python function arguments against their type hints at runtime. No dependencies.
- [pyloggor](https://github.com/PrivatePandaCO/pyloggor): structured, column-aligned logging for Python, with file writes batched on a background thread. On PyPI.
- Internships on visual-inertial odometry for GPS-denied drone flight (Spin Drift Technologies) and LLVM-based compiler infrastructure for a fuzzer (Phi Dynamics). Both under NDA, so no code here.

Libraries and tools are grouped under [PrivatePandaCO](https://github.com/PrivatePandaCO).

[privatepanda.co](https://privatepanda.co) · [LinkedIn](https://www.linkedin.com/in/parth-mittal-o6) · [meparthmittal@gmail.com](mailto:meparthmittal@gmail.com)
