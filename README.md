# Web-Calculators
Practical engineering calculators.  Built by LED for the community. 

A collection of browser-based engineering calculators built and maintained by
[Lotus Electronics Design](https://lotuselectronicsdesign.com).

These are small, focused tools for common electrical and embedded-systems
calculations — the kind of quick math you'd otherwise do by hand or in a
scratch spreadsheet. Each calculator is self-contained and written in PHP.

## Purpose

This repository is the home for all of our web calculators in one place. Rather
than scattering one-off scripts across projects, everything lives here so the
tools can be versioned, improved over time, and eventually embedded into the
Resources section of the Lotus Electronics Design website.

The collection is expected to grow. New calculators get added as their own
folder — nothing else has to move.

## Current Calculators

| Calculator | Description |
|------------|-------------|
| **LED Resistor** | Calculates the series current-limiting resistor for an LED given supply voltage, LED forward voltage, and desired forward current. |
| **Voltage Divider** | Solves for output voltage, resistor values, or current in a two-resistor voltage divider. |
| **STM32 Timers** | Computes STM32 timer prescaler and auto-reload (ARR) values to hit a target frequency or period from a given clock. |

## Planned Additions

Future calculators will be added here as they're built. Ideas on the list
include filter design, trace-width / current capacity, and unit conversions.

## Requirements

These calculators are written in PHP and need a PHP-enabled web server
(for example, Apache with `mod_php`, or PHP-FPM) to run. Drop a calculator's
folder onto a PHP-capable host and open its file in a browser.

## License

See the [LICENSE](LICENSE) file for details.

## Contact

Lotus Electronics Design — lotuselectronicsdesign@gmail.com

