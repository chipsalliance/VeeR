<picture>
  <!-- User prefers light mode: -->
  <source srcset="img/VeeR-logo-black-rgb.png" media="(prefers-color-scheme: light)"/>

  <!-- User prefers dark mode: -->
  <source srcset="img/VeeR-logo-white-rgb.png"  media="(prefers-color-scheme: dark)"/>

  <!-- User has no color preference: -->
  <img src="img/VeeR-logo-black-rgb.png"/>
</picture>

# VeeR

VeeR (Very Efficient & Elegant RISC-V) is an open source production-grade RISC-V core family hosted by CHIPS Alliance and comes in three variants:

* [EH1](https://github.com/chipsalliance/Cores-VeeR-EH1) - a high-performance single threaded RV32IMCZ core, the original implementation,
* [EH2](https://github.com/chipsalliance/Cores-VeeR-EH2) - a dual-threaded successor to EH1, originally the world’s first dual-threaded commercial, embedded RISC-V core designed for IoT and AI systems,
* [EL2](https://github.com/chipsalliance/Cores-VeeR-EL2) - a tiny and low-power RV32IMC (with partial support for Z extension) core, which is the variant used in the Caliptra project.

[Guineveer](https://github.com/chipsalliance/guineveer) project provides a simple SoC design with the VeeR-EL2 core.
