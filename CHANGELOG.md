# CHANGELOG

## 1.1.1

### Added

- support for parallel step and sliced step

## 1.1.0

### Added

- support for using Python OP without dflow in the image

## 1.0.26

### Added

- fix a typo in io
- dicts override json_file in dispatcher executor
- allow for returning None for output artifact in OP
- work around Argo pod id != step id for slices and slurm job template

## 1.0.25

### Added

- support for id_rsa, id_dsa, id_ecdsa, id_ed25519

## 1.0.24

### Added

- fix \n in code for dispatcher executor
- handle io in slurm remote executor

## 1.0.23

### Added

- work around pod id != step id

### Fix

- fix: parameter has no attribute value

## 1.0.22

### Added

- map /tmp to pwd/tmp in slurm job

## 1.0.21

### Added

- add dispatcher executor
- with_param receives python list

## 1.0.20

### Fix

- fix: jsonize parameters before reusing

## 1.0.19

### Fix

- fix: handle big parameter whose name changes

## 1.0.18

### Added

- use str instead of jsonpickle to store parameter types

## 1.0.17

### Fix

- fix: cannot pickle types in typing

## 1.0.16

### Added

- fix a bug in 1.0.15
- record parameter type in parameter description

## 1.0.15

### Added

- handle big parameters in query step and reuse step

## 1.0.14

### Added

- name of OP template be optional
- add not allowed input artifact path
- not use pvc in slurm remote executor for default

## 1.0.13

### Added

- auto build docs to branch docs
- add retry for all actions in slurm remote executor
- support for use private key on node for SSH connection

## 1.0.12

### Added

- force lowercase for OP template to fix RFC 1123
- add private key option for SSH connection
- add container mode for remote Slurm executor
- add docs

## 1.0.11

### Added

- add global configurations
- modify lebesgue interfaces
- request kubernetes API server with token

## 1.0.10

### Added

- add Lebesgue plugins
- add resources requirements for templates
- support for slurm template for slices

## 1.0.9

### Fix

- fix a bug in sliced step

## 1.0.8

### Added

- handle empty sliced step

## 1.0.7

### Added

- add BigParameter
- retain empty dir
- optimize opening file descriptors

## 1.0.6

### Added

- add SlurmJobTemplate to submit slurm job by using wlm-operator

## 1.0.5

### Added

- download_artifact returns path list
- add convert_to_argo method to Workflow

## 1.0.4

### Added

- add resource template
- add some manifests

## 1.0.3

### Added

- add some arguments to PVC

## 1.0.2

### Fix

- restrict argo-workflows==5.0.0

## 1.0.1

### Added

- add comments doc

## 1.0.0

### Added

- initial release