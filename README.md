# The Open PM² Project Management Methodology - English

The goal of this repository is to preserve a copy of the English Open PM² guide and related publications/works in an open format that allows easy follow-up of the publication's evolution. 

It is based on the original version of the guide and related works produced and published by the European Commission, DIGIT Centre of Excellence in Project Management (COEPM²), without modifications other than the format change. This repository aims to act as an enabler for community collaboration and revision.

The repository makes use of the AsciiDoc format for the publication texts. The AsciiDoc format is a useful presentation format in its own right: AsciiDoc markup is simple, intuitive and as such is easily proofed and edited. You can learn more about it in the [AsciiDoc quick reference](https://asciidoctor.org/docs/asciidoc-syntax-quick-reference/).

This repository contains the English version of the works. The translations are managed in a decentralized way. Each translation is kept in its own repository.

## Contributing & signaling issues

- For any discrepancies (i.e. errors) between the publications and this repository please contact the repository maintainers.

- For an up to date version that includes amendments and corrections to the original publications, as well as for submitting any proposals/suggestions please refer to the [PM² Alliance](https://github.com/pm2alliance) repository that contains the most up-to-date version of the guide.

## Download the PDF

- Download your copy at [PM² Alliance Publications](https://www.pm2alliance.eu/publications/)
  
  or an automated build of the latest pre-release version from [Github](https://github.com/as-op/opm2-en/blob/publish/pm%C2%B2-guide.pdf)

## Build the PDF

- Install the command-tool [AsciiDoctor](https://asciidoctor.org/#installation) for your system.

- Clone this repository
```console
~$ git clone https://github.com/pm2alliance/opm2-en.git opm2-en
```

- Navigate to the publications folder in the local checked out project folder
```console
~$ cd opm2-en/publications
```

- Run AsciiDoctor command to generate `pm²-guide.pdf`

```console
~$ asciidoctor-pdf pm²-guide.adoc
```


## License & Disclaimer

Staying true to the spirit of open source, the content of this repository is open source under European Public License, see the [license details](./LICENSE.md) for more information.

Neither the owner nor any of collaborators of this repository is responsible for the use which might be made of the information contained within.

## References and Resources
Thanks to the following for making their content and guidelines public, allowing us to "build on the shoulders of giants".
- [AsciiDoc](https://github.com/asciidoc)
- [AsciiDoctor](https://github.com/asciidoctor)
- [European Commission](https://ec.europa.eu)
- [Inkscape](https://github.com/inkscape)
- [ISA² - Interoperability solutions for public administrations, businesses and citizens](https://ec.europa.eu/isa2/home_en)
- [Kubernetes](https://github.com/kubernetes/)
- [LibreOffice](https://github.com/LibreOffice)
- [Mozilla](https://github.com/mozilla)
- [Pandoc](https://github.com/jgm/pandoc)
- [PM² Alliance](https://github.com/pm2alliance)
- [Pro Git Book](https://github.com/progit/progit2/)
