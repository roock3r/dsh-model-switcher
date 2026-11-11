# Generated standalone distribution

This repository is generated from [the canonical DSH workspace](https://github.com/roock3r/dsh-plugins).

Edit plugin code and the shared installer in that workspace, then run
`npm run package:standalone`. Do not maintain a divergent copy here.
`SOURCE.json` records the exact canonical source-file hashes used for this export.
The exporter includes one plugin and a self-contained installer; setup does not
fetch the combined repository or another plugin.

The package versions remain compatible with existing installations. Release tags
and uploaded asset hashes should be checked against the generated receipt.
