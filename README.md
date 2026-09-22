# meteo-carrier — PCB Design Brief

One board that connects an ESP32 module to its sensors, its satellite modem, and
an off-board solar and battery power stage — written for whoever lays it out.

**Read it → https://ildarcheg.github.io/carrier-pcb-brief/**

## What this is

The carrier board of **meteo**: solar-assisted, ESP32-based weather probes that
batch hourly readings and forward them over the Iridium satellite network. Three
are built for the 2026/27 austral season — two land stations beside reference
series on King George Island, and one expendable buoy released mid-Drake Passage.

It carries the net list, the connector scheme, the two metering jumpers, and the
full cross-plug matrix: every wrong plug that can still be made on this board,
and what each one does.

Companion to the [Buoy Parts Book](https://ildarcheg.github.io/buoy-parts-book/),
[Battery Pack Wiring](https://ildarcheg.github.io/battery-pack-wiring/) and
[Thermal Probe Wiring](https://ildarcheg.github.io/thermal-probe-wiring/).

It is a school co-build project.

## The section not to skim

**§5, the connectors.** Connector sizes are the keying on this board, and two
ports are deliberately built larger than their wire count needs. The page says
"please don't clean this up" and means it — the matrix underneath shows what
each apparent redundancy is buying.

## About this repository

This repo holds **one published page and nothing else**. It is a mirror, not a
source: `index.html` is generated from the working repository, where every claim
has an owning document that argues it. Corrections belong there — an edit made
directly here is overwritten by the next publish.

The page is self-contained: no JavaScript, no images, no analytics, no cookies.

## Status

The board is **not fabricated**. Two decisions were closed on 2026-09-09 — the
charger port's size and where the fuel gauge sits in the pack link — and the
page marks what is still open, including that the cross-plug matrix rests on one
untested assumption it names.

## Licence

[CC BY 4.0](LICENSE). Reuse it, adapt it, publish it, with credit to
**SouthPing** (<https://southping.org/>) and a link back. Source code in the
project is Apache-2.0. Manufacturers' datasheets and product photographs
remain theirs and are not covered by this grant.
