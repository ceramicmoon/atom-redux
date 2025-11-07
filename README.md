# Atom Redux

## The Hackable Text Editor for the 21st Century. Revived.
Originally developed by GitHub, [Atom](https://atom.io) is a hackable text editor for the 21st century, built on [Electron](https://github.com/electron/electron). Atom and all repositories under Atom has been officially archived on December 15, 2022. 

The **Atom Redux** project aims to extend the lifetime of Atom as a real open-source editor, maintaining its original characteristic while improving on its functionality following the need of its lovers. It features full privacy, improved extensibility and performance, as well as adherence to Atom's original design philosiphy.

### Agenda
At this stage, there are currently 3 primary objectives:
- [ ] Privacy & offline: Eliminate all telemetry and remote services (including auto update); remove all automatic, non-user-initiated network activities, so that it becomes an offline editor by default
- [ ] Local extension system: Default local installation of all extensions, remove deprecated online extension installation module
- [ ] Performance optimization: Improve startup speed and responsiveness

## Legacy Documentation

If you want to read about using Atom or developing packages in Atom in its GitHub ages, the [Atom Flight Manual](https://flight-manual.atom.io) is free and available online. You can find the source to the manual in [atom/flight-manual.atom.io](https://github.com/atom/flight-manual.atom.io). The [API reference](https://atom.io/docs/api) for developing packages is also documented on Atom.io.

## Installing

### Prerequisites
- [Git](https://git-scm.com)

### Windows (default development platform)
Once a version is finalized, pre-built 64-bit installers will be made available under the Releases tag as `AtomSetup-x64.exe`. Support for 32-bit systems has been temporarily discontinued, but may be restored at a later date. Portable binaries as `atom-x64-windows.zip` (64-bit) will also be released. 

The pre-existing automatic update functionality has been removed.

### Linux
> We are not yet officially building and testing on Linux. You are still welcome to try with caution on your own.

## Building
We have tried to maintain the original building workflow to minimize the effort to set up building environments. The Atom Flight Manual has dedicated sections on building Atom on various platforms, which also in principle applies to Atom Redux. There may be some subtleties specific to each version, which will be addressed either in the planned Atom Redux Documentation or in the Release notes.

## License
MIT
