# Overview

Do you like terraform stations from my mod [Aesthetic Terraform Stations](https://steamcommunity.com/sharedfiles/filedetails/?id=2622411084)?  Do you also want to have properly-skinned terraform stations for [We are the Imperial Navy](https://steamcommunity.com/sharedfiles/filedetails/?id=864541681)?  Then this mod is for you!

# Changes

Adds a terraform station definition with an active terraforming beam for graphical culture `wain_01`, required for Aesthetic Terraform Stations to apply the correct appearance.

## Compatibility

Should work with practically everything that also works with We are the Imperial Navy and Aesthetic Terraform Stations.

Built for Stellaris version 3.7 "Canis Minor."  Not compatible with achievements, but neither are the dependencies.

### Required Dependency Mods

* [Aesthetic Terraform Stations](https://steamcommunity.com/sharedfiles/filedetails/?id=2622411084) enables the very old-school terraform stations as visual markers for terraforming planets
* [We are the Imperial Navy](https://steamcommunity.com/sharedfiles/filedetails/?id=864541681) for the original graphics and other ship-related code

## Changelog

* 1.0.0 Initial version
* 1.0.1 Tweak mod name

## Source Code

Hosted on [GitHub](https://github.com/corsairmarks/wh40k_shipset_terraform_station_aesthetic)

### Development Notes

It is best to clone this repository into `<Stellaris User's Directory>/Paradox Interactive/Stellaris/mod`, and then make a connection to the `mod` folder via a `*.mod` file's `path` property.  That will ensure the game can see the files, and also that CWTools will parse them.  Also note that the README.md file exists in the `mod` directory but is symbolically linked in the root directory.