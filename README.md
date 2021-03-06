# NoiseFloorReporter

## Version
Prototype

## What is this
Amateur radio operators often like to chat with other hams on HF or Short-Wave bands, but that isn't always easy.
Sometimes propagation isn't good, other times local noise levels are too high, and signals are buried in the noise.
A question came about during a discussion between myself and a few ham friends:

"How far from my home [in the city] do I need to go, to find an RF *quiet* area, so I can hear other's signals better?"

This project aims to use Software Defined Radio (SDR), a computer, a whip antenna, and some scripts to report on noise levels
at various locations -- even while driving around town or out in the country.

## Requirements
Python 3.6 or newer
Access to the hardware mentioned above
Some knowledge of an SDR Radio interface (this project uses SDRPlay's RSP2pro and SDRuno software)
54" whip or tuned antenna system for an amateur HF band (example: a center-loaded antenna for the popular 20 meter band)
Windows or Linux/Raspbian computer with USB ports, capable of loading and running SDRuno and Python
USB/Serial GPS antenna/puck
USB A/B cables, power cables, and antenna feed line

## Optional
An APRS program (example: DireWolf... natively supported by this project)

## Additional Information
For additional details on setup, use, and assumptions, see "Project flooRFinder User Guide.pdf" in this repository"
