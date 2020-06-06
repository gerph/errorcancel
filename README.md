# ErrorCancel

## Introduction

Rick Murray wrote a small module to trigger the cancel on error boxes
after a short delay. This is that module, with no changes other than
the SWI numbers being defined.

The original source can be found on [Rick Murray's site](https://heyrick.eu/random/errorcancel.s.txt).

## Usage

* Load the module.
* Trigger an error
* Wait 5 seconds.
* Watch it cancel.

## Continuous Integration

This release is intended to demonstrate the continuous integration environment
provided by the JFPatch-as-a-service system. Two mechanisms are provided for
building the module - through GitLab CI, and through GitHub's workflows.
Documentation for the .robuild.yaml file format can be found on the
JFPatch-as-a-service website, and the example here just invokes the
assembler and the linker to make the module.

For GitHub workflows, see the file .github/workflows/jfpatch.yml.
For GitLab CI, see the file .gitlab-ci.yml.
