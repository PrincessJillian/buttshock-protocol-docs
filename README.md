# Buttshock Serial Protocol Docs

Documentation for serial based control of the following devices:

- Erostek ET-312 Electrostimulation Device
- Erostek ET-232 Electrostimulation Device
- Estim Systems 2B Electrostimulation Device

## Buttshock Project Goals

If you're going to shock yourself in the butt (or other places) for
sexual pleasure, don't you want to be able to know exactly what and
how you're doing it? Even if you can't understand it, wouldn't it be
nice for people that do to have access to the knowledge and data they
need to make sure things are safe? Why is the best encryption open
source, but electrostim toys are closed?

The Buttshock project exists to reverse engineer and document
eletrostim devices so that any developer that wants to control their
devices can, via their own code.

Some of the goals of this project include:

- Documenting the communications protocols (serial or otherwise)
- Reverse engineering the firmware (where possible)
- Mapping the circuit boards and creating schematics

### Serial Protocol

While partial implementations of the ET-312 serial protocol have
existed for years, they've usually been passed around by hand, and
have never been well documented. While we'll certainly be keeping the
original erosoutsider perl code around the repo as a piece of history,
we're concentrating on getting nicely formatted protocol documentation
finished so that anyone can work with the ET-312 via their language or
program of choice.

Alongside this, we're working on digging up documentation about the
ET-232 and Estim Systems 2B Devices, so we can also document those. In
the end, we hope to provide as much documentation on computer control
for estim devices as possible.

All protocol documentation is in org-mode format, and can be found in
the doc directory of this repository.

## Buttshock Implementations

If you are looking for a language specific version of the buttshock
serial protocol work, each language has a repo assigned to it:

- Python Library - http://github.com/metafetish/buttshock-py
- Rust Library - http://github.com/metafetish/buttshock-rs
- Javascript Library for Node, Chrome Apps, and possibly for a general
  WebSerial API, should one ever exist -
  http://github.com/metafetish/buttshock-js
- Arduino Library - http://github.com/kinkyhacks/venerate

## License

Original Perl ErosOutsider Script is GPL v2, no author information available

All other portions of the Buttshock repository are covered under
the following BSD license:

    Copyright (c) 2016, Buttshock Project
    All rights reserved.

    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions are met:
        * Redistributions of source code must retain the above copyright
          notice, this list of conditions and the following disclaimer.
        * Redistributions in binary form must reproduce the above copyright
          notice, this list of conditions and the following disclaimer in the
          documentation and/or other materials provided with the distribution.
        * Neither the name of the Buttshock Project nor the
          names of its contributors may be used to endorse or promote products
          derived from this software without specific prior written permission.

    THIS SOFTWARE IS PROVIDED BY Buttshock Project ''AS IS'' AND
    ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO,
    THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A
    PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL Kyle
    Machulis/Nonpolynomial Labs BE LIABLE FOR ANY DIRECT, INDIRECT,
    INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
    (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR
    SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
    HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
    CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR
    OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE,
    EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE

