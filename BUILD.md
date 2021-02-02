# Prerequisites

Before you can build a PDF, you must ensure that your environment is supported by the open source command line tools [AsciiDoctor](https://asciidoctor.org/) and [AsciiDoctor PDF](https://asciidoctor.org/docs/asciidoctor-pdf/) 
Supported environments are Linux, macOS and Windows.

# Requirements

AsciiDoctor is made with the programming language Ruby, you need to install and use a supported version. Please visit for detailed information. [https://asciidoctor.org/#requirements](https://asciidoctor.org/#requirements).

# Installation

## Git

Git is used to download and sync this repository. Please read more at
[https://github.com/git-guides/install-git](https://github.com/git-guides/install-git)

## AsciiDoctor

Please read and follow the installation instructions at [https://asciidoctor.org/#installation](https://asciidoctor.org/#installation)

## AsciiDoctor PDF

Installation of AsciiDoctor PDF is similar, please find the information at [https://asciidoctor.org/docs/asciidoctor-pdf/#getting-started](https://asciidoctor.org/docs/asciidoctor-pdf/#getting-started)

## Build

- Clone this repository
```console
~$ git clone https://github.com/pm2alliance/opm2-en.git opm2-en
```

- Navigate to the publications folder in the local checked out project folder
```console
~$ cd opm2-en/publications
```

- Run AsciiDoctor PDF command to generate `pm²-guide.pdf`

```console
~$ asciidoctor-pdf pm²-guide.adoc
```





