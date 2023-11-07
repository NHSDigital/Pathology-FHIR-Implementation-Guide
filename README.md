# Pathology-FHIR-Implementation-Guide
This repository is maintained by Pathology Team. Any queries contact us via [email test].

Pathology Repository of FHIR Assets for NHSE Pathology FHIR Implementation Guide [Simplifier project](https://simplifier.net/Pathology/~guides).


## Main Branch Status

FHIR Validation with Terminology Checks 

 [![NHSDigital IOPS Validation)](https://github.com/NHSDigital/Pathology-FHIR-Implementation-Guide/actions/workflows/terminology.yml/badge.svg)](https://github.com/NHSDigital/Pathology-FHIR-Implementation-Guide/actions/workflows/terminology.yml)

## Develop Branch Status

FHIR Validation with Terminology Checks 

 [![NHSDigital IOPS Validation)](https://github.com/NHSDigital/Pathology-FHIR-Implementation-Guide/actions/workflows/terminology.yml/badge.svg?branch=develop)](https://github.com/NHSDigital/Pathology-FHIR-Implementation-Guide/actions/workflows/terminology.yml?branch=develop)

## Validation
The validator will validate any assets and examples against the Profiles within the CabilityStatement, or HL7 resource otherwise. The Validation check status will be seen within the Pull Requst and will stop merge if incorrect. All validator actions can be seen within the [Action]([England-Pathology-Conformance](https://github.com/NHSDigital/Pathology-FHIR-Implementation-Guide/actions)) tab. 

## CapabilityStatement
The CapabilityStatement is used by the validation tool to check which profile to validate against. If no Profile is stated then the base FHIR resource will be used.

## Developers Information
### GitHub Actions
- *IOPS-FHIR-Validation-call* - Validates assets and examples against the FHIR packages found within package.json, and validation of SNOMED CT codes against the ontoserver. This action calls the [IOPS-FHIR-Test-Scripts repo](https://github.com/NHSDigital/IOPS-FHIR-Test-Scripts/tree/main).
- *IOPS-FHIR-QualityControlChecker-call* - (Optional) Information on the IG content spell / link / error checking can be found within the [IOPS-FHIR-Test-Scripts repo](https://github.com/NHSDigital/IOPS-FHIR-Test-Scripts/tree/main/IGPageContentValidator).
- *Replace tab with 2 spaces* - (Optional) Simple standardisation workflow to replace all tabs within text files with 2 spaces.

Information on the QualityControlChecker can be within the [IOPS-FHIR-Test-Scripts repo](https://github.com/NHSDigital/IOPS-FHIR-Test-Scripts/tree/main/QualityControlChecker).
