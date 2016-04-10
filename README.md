# Erosoutsider

Documentation for serial based control and firmware implementation of
the Erostek ET-312 Electrostimulation Device.

## Project Goals

This project exists to reverse engineer the Erostek ET-312
Electrostimulation Device. 

This includes

- Mapping the serial communications protocol
- Unencrypting and reverse engineering the firmware
- Mapping the circuit board

### Serial Protocol

While partial implementations have existed for years, they've usually
been passed around by hand, and have never been well documented. While
we'll certainly be keeping the original perl code around the repo as a
piece of history, we're concentrating on getting nicely formatted
protocol documentation finished so that anyone can work with the
ET-312 via their language or program of choice.

The protocol documentation is in the repo at:

[docs/et312-protocol.org](docs/et312-protocol.org)

### Firmware

The last firmware upgrade to the ET-312 happened in 2004, yet the box
is still sold to this day, for the same price. The serial port
implementation is broken, and there's quite a few bugs and half
implemented features hidden around the firmware. We'd like to be able
to go in, fix those, and distribute new, better firmware to ET-312
owners.

### Circuit Mapping

The circuit board is most likely a pretty simple 2 layer board,
meaning it should be easily mappable. There's probably nothing
groundbreaking happening here, but it's an interesting exercise
nonetheless.

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

## FAQ

### WHY?!

There's probably hundreds if not thousands of ET-312 boxes around the
world. We'd like them to work better.

### Why not just build a new, better box?

That's certainly a solution, and we've been contacted by multiple
people who are doing just that. While that's totally awesome, and we
might take a crack at doing that ourselves at some point, we'd also
like what's out there to work better than it does right now.

### Why not just reimplement the firmware from the ground up?

The idea is to provide a way to upgrade things without having to crack
the box open and replace the CPU completely. That's a time consuming
process not everyone can pull off. If we can just have people reflash
their box, it saves a lot of trouble for everyone involved.

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

