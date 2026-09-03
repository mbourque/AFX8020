# AFX 8020 Library for Creo

An open-source 8020 profile library for **AFX in PTC Creo Parametric**.

## Overview

The built-in AFX library in Creo does not include 8020 metric profiles, connectors, and equipment. This project adds an 8020 metric library that extends the existing AFX library instead of replacing it.

The library is intended to make it easier to create metric 8020-style aluminum framing assemblies directly in Creo AFX.

## Status

This library is in active development.

Most standard framing elements are complete. Additional work is planned for more profiles, connectors, and equipment.

## Included Content

This library currently includes 8020 metric AFX components such as:

* Metric framing profiles
* Connectors
* Equipment and related library items

More components will be added over time.

## Installation

1. Download or clone this repository.

2. Store the `AFX8020` folder somewhere on your computer.

   Example:

   ```text
   C:/ptc/afx8020
   ```

3. In Creo, configure the AFX setting:

   ```text
   CUSTOMIZATION_PATH
   ```

   Set it to the location where you stored the library.

   Example:

   ```text
   CUSTOMIZATION_PATH c:/ptc/afx8020
   ```

4. Restart Creo.

5. Open AFX. The 8020 metric library should now be available alongside the existing AFX library.

## Notes

This library extends the existing AFX library. It is not intended to overwrite or replace the default Creo AFX library.

If the library does not appear after installation, verify that:

* `CUSTOMIZATION_PATH` points to the correct folder location.
* The path does not contain a typo.
* Creo was restarted after changing the setting.
* The `AFX8020` folder structure was not changed after download.

## Development Roadmap

Planned improvements include:

* Additional metric profiles
* More connectors
* More equipment
* Expanded standard framing content
* Community-submitted additions and corrections

## Contributing

Contributions are welcome.

This project is being released as open source so the Creo and AFX community can improve and expand the library together.

Useful contributions may include:

* New profiles
* Additional connectors
* Equipment models
* Corrections to existing library items
* Documentation improvements
* Example assemblies

Please open an issue or submit a pull request if you would like to contribute.

## Disclaimer

This project is an independent community library for Creo AFX.

It is not affiliated with, endorsed by, or maintained by PTC or 80/20 Inc. All trademarks and product names belong to their respective owners.

Use this library at your own discretion. Verify all profiles, connectors, dimensions, and equipment before using them for design, manufacturing, or purchasing decisions.

## License

```text
MIT License
```
