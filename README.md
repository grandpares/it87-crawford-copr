# IT87-Crawford-Copr
An akmods wrapper for [frankcrawford/it87](https://github.com/frankcrawford/it87)
## Build Status
Master:![Master branch build status](https://github.com/grandpares/it87-crawford-copr/actions/workflows/makefile.yml/badge.svg?event=push&branch=master)

Staging:![Staging branch build status](https://github.com/grandpares/it87-crawford-copr/actions/workflows/makefile.yml/badge.svg?event=push&branch=staging)
## Support
This repo contains no new code from upstream and supports the same chips.

<details>

<summary>Supported hardware</summary>

 * IT8603E  Super I/O chip w/LPC interface
 * IT8606E  Super I/O chip w/LPC interface
 * IT8607E  Super I/O chip w/LPC interface
 * IT8613E  Super I/O chip w/LPC interface
 * IT8620E  Super I/O chip w/LPC interface
 * IT8622E  Super I/O chip w/LPC interface
 * IT8623E  Super I/O chip w/LPC interface
 * IT8625E  Super I/O chip w/LPC interface
 * IT8628E  Super I/O chip w/LPC interface
 * IT8528E  Super I/O chip w/LPC interface
 * IT8655E  Super I/O chip w/LPC interface
 * IT8665E  Super I/O chip w/LPC interface
 * IT8686E  Super I/O chip w/LPC interface
 * IT8688E  Super I/O chip w/LPC interface
 * IT8689E  Super I/O chip w/LPC interface
 * IT8695E  Super I/O chip w/LPC interface
 * IT8705F  Super I/O chip w/LPC interface
 * IT8712F  Super I/O chip w/LPC interface
 * IT8716F  Super I/O chip w/LPC interface
 * IT8718F  Super I/O chip w/LPC interface
 * IT8720F  Super I/O chip w/LPC interface
 * IT8721F  Super I/O chip w/LPC interface
 * IT8726F  Super I/O chip w/LPC interface
 * IT8728F  Super I/O chip w/LPC interface
 * IT8732F  Super I/O chip w/LPC interface
 * IT8736F  Super I/O chip w/LPC interface
 * IT8738E  Super I/O chip w/LPC interface
 * IT8758E  Super I/O chip w/LPC interface
 * IT8771E  Super I/O chip w/LPC interface
 * IT8772E  Super I/O chip w/LPC interface
 * IT8781F  Super I/O chip w/LPC interface
 * IT8782F  Super I/O chip w/LPC interface
 * IT8783E/F Super I/O chip w/LPC interface
 * IT8786E  Super I/O chip w/LPC interface
 * IT8790E  Super I/O chip w/LPC interface
 * IT8792E  Super I/O chip w/LPC interface
 * IT87952E  Super I/O chip w/LPC interface
 * Sis950   A clone of the IT8705F


</details>

## Why?
Immutable Fedora distributions (such as UBlue and its flavors) currently do not support dkms. This repo tracks upstream and uploads sources that pass basic checks to copr, from where end users can layer them with rpm-ostree. This also has the advantage of providing a module signed with the user's own MOK for Secure Boot purposes.
## Installation
TODO
