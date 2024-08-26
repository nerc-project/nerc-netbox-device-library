# NERC Netbox Device Library

## Description
This repo contains the collection of device and module templates and provides the workflow actions to publish them to NERC Netbox deployment.

## Usage
Template format is expected to be consistent to that use by Netbox export to yaml function.

Main branch is synced with production repo. PR to main branch will trigger push to development install of netbox.

## Limitations
Manufacturer creation is not supported and is being handled by https://github.com/nerc-project/nerc-netbox repo.

CI/CD does not raise a failed job if template import fails inside the import script.  Ouput of the workflow job needs to be examined to confirm success.

## References:
- https://github.com/netbox-community/Device-Type-Library-Import
- https://github.com/netbox-community/devicetype-library
