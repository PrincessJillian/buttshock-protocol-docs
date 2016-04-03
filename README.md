# Erosoutsider

Documentation for serial based control and firmware implementation of
the Erostek ET-312 Electrostimulation Device.

## Project Goals

This project exists to try and map the full RS-232 protocol for the
Erostek ET-312 Electrostimulation Device. While partial
implementations have existed for years, they've usually been passed
around by hand, and have never been well documented. While we'll
certainly be keeping the original perl code around the repo as a piece
of history, we're concentrating on getting nicely formatted protocol
documentation finished so that anyone can work with the ET-312 via
their language or program of choice.

We're also interested in analyzing and exploring the firmware for the
device, two versions of which we include with the repo.

## Repo Contents

This repo contains the following:

- Protocol, Firmware, and Hardware Documentation (doc directory)
- The original erosoutsider (erosoutsider directory)
- Copies of available firmware

## erosoutsider Implementations

If you are looking for a language specific version of the erosoutsider
work, each language has a repo assigned to it:

- Python Library - http://github.com/metafetish/erosoutsider-py
- Rust Library - http://github.com/metafetish/erosoutsider-rs
- Javascript Library for Node, Chrome Apps, and possibly for a general
  WebSerial API, should one ever exist -
  http://github.com/metafetish/erosoutsider-js
- Arduino Library - http://github.com/kinkyhacks/venerate

## License

Original Perl Erosoutsider Script is GPL v2, no author information available

All other portions of the Erosoutsider repository are covered under
the following BSD license:

    Copyright (c) 2016, Kyle Machulis/qDot
    All rights reserved.

    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions are met:
        * Redistributions of source code must retain the above copyright
          notice, this list of conditions and the following disclaimer.
        * Redistributions in binary form must reproduce the above copyright
          notice, this list of conditions and the following disclaimer in the
          documentation and/or other materials provided with the distribution.
        * Neither the name of the Kyle Machulis/Nonpolynomial Labs nor the
          names of its contributors may be used to endorse or promote products
          derived from this software without specific prior written permission.

    THIS SOFTWARE IS PROVIDED BY Kyle Machulis/Nonpolynomial Labs ''AS IS'' AND ANY
    EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
    WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
    DISCLAIMED. IN NO EVENT SHALL Kyle Machulis/Nonpolynomial Labs BE LIABLE FOR ANY
    DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
    (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
    LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
    ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
    (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
    SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE

