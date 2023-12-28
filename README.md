<a name="readme-top"></a>
# SDE Standard Architecture Model (SDE SAM)

**This Repository is Work in Progress**

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#introduction">Introduction</a></li>
    <li><a href="#modelformat">Model Format</a></li>
    <li><a href="#status">Status</a></li>
    <li><a href="#differences">Differences to SATRE</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>

<!-- INTRODUCTION -->
### Introduction ###
This repository contains an Archimate model describing a standard architecure for a Secure Data Environment ([SDE](https://transform.england.nhs.uk/key-tools-and-info/data-saves-lives/secure-data-environments/)).

It is a specialisation of the [SATRE](https://satre-specification.readthedocs.io/en/stable/) Standard Achitecture for a Trusted Research Environment.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MODELFORMAT -->
### Model Format ###
The model is produced using the [Archi Archimate tool](https://www.archimatetool.com/) and shared to this repository using the [CoArchi](https://github.com/archimatetool/archi-modelrepository-plugin) collaboratinn plugin (which produces output based on the the Grafico Format).

The Archi tool can be used to convert the model into an Open Exchange format for use in other Archimate tools.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- STATUS -->
### Status ###
The focus of the model at this stage are the Motivation and Strategy layers of the Archimate language.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- DIFFERENCES -->
### Differences to SATRE ###
Any elements added to the SATRE reference model have been prefixed with SNSDE and no elements have been removed.

Where the SDEs require a new or more specifc component than provided by the reference model, these have been added with a composistion relationship. Different levels of composition have also been prefixed with and index with an index of 1 being the top componwnt with the index increasing at each level of de-composition.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
### Contributing ###
We are still working on the best way to accept contributions while maintaining a valid Archi model but contributions are still welcome.

You can also simply open an issue with the tag "enhancement". Alternatively, To make additions or changes please fork the repo and create a pull request. 

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingContribution`)
3. Commit your Changes (`git commit -m 'Adding some Amazing Contribution'`)
4. Push to the Branch (`git push origin feature/AmazingContribution`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
