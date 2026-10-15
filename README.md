# Collapse Hemispheres for Alakazam

A plugin for [Alakazam](https://github.com/markspan/Alakazam): the contralateral and ipsilateral waveforms of a lateralised component, the N2pc or the LRP, collapsed across every pair of lateral electrodes at once.

It was part of Alakazam until it became a plugin of its own, so that it can be
installed, upgraded and documented on its own.

## Manual

The manual is on this repository's pages:
<https://markspan.github.io/AlakazamCollapseHemisphere/>.

## Installing

In Alakazam, **Install plugins** on the Alakazam tab lists this repository:
select it and press **Install**. It installs the latest release. A zip from
the [releases](https://github.com/markspan/AlakazamCollapseHemisphere/releases), or one built with
`build`, installs the same way through **From a link**, and so does the link
to this repository. The tool appears on the Tools tab, as it did before.

It needs an Alakazam that no longer carries `CollapseHemispheres` itself (newer than
V0.4.5.2). Workspaces and templates made with the built-in tool open and
recalculate as before once the plugin is installed; Alakazam offers to
install it when one needs it.

## Building and testing

```matlab
build()                                    % dist/CollapseHemispheres-<version>.zip
runtests('tests')                          % the tool's tests and the install
```

The tests need Alakazam's source: the folder in `ALAKAZAM_ROOT`, or the
Alakazam repository beside this one.

## Licence

GPL-3.0, as Alakazam.
