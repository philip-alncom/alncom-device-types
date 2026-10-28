# Alncom device types

Device and module type definitions in the NetBox/Nautobot devicetype-library format, for devices that are not in the community library.
Add this repository to Nautobot under Extensibility, Git Repositories, with "Provides" set to Import Wizard.

- `device-types/<Manufacturer>/` holds the device types.
- `module-types/<Manufacturer>/` holds module types (Eltek rectifiers, breakers and load fuses). Import these with Import Objects.

These files are generated from and kept in step with the private alncom-support-checker project. Do not edit them here.
