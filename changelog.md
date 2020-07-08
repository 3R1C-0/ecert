# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

[Added] for new features.
[Changed] for changes in existing functionality.
[Deprecated] for soon-to-be removed features.
[Removed] for now removed features.
[Fixed] any bug fixes.
[Security] in case of vulnerabilities.
[Updated] for guides and documentations.

## Unreleased

Fixed
- Age Column to correctly displays time

## 0.0.5 - 2020-06-19

Updated
- eLot Notice Web API Guide (2020-06-09)

Added
- Payment Type for ePhyto Application
- Archive function for ePhyto's

Changed
- Grid Filter simpified

Fixed
- Manage Profile: update password and update email address works as intended
- Search field on Agreements page works as intended
- Download all Agreements populates with required fields
- Application Referance Number Column shows all applications after 100K ePhytos

## 0.0.4 - 2020-06-10

Added
- Special Characters are now encoded for Frontend - API users to encode with HTML entities
- Super Admin ability to activate or deactivate an Inspector

Changed
- PDF 417 Bardcode size increased

Fixed
- Saving user profiles no longer returns a validation error
- Minor bug fixes

## 0.0.3 - 2020-05-22

Added
- Clear filter for improved search functionality
- Notification Emails: Withdrawn Applications now includes Client Reference Number
- NPPO Module implemented
- eLot API Validations Guide (2020-05-20)
- eInspect Module is live

Changed
- Bardcode on ePhyto PDF is now restricted to 33 Characters
- PDF Header size change, increased Barcode and QR Code for more efficent scanning

Updated
- eCert Agreements Web API User Guide (2020-05-19)

## 0.0.2 - 2020-05-12
Added
- Central Business Register (CBR) Business Linking - Link Businesses and lock the viewing of ePhyto Applications to specific businesses

Fixed
- Agreements - Print/View Agreements no longer returns an error
- Age Column restored
- Inspector Name Column restored

## 0.0.1 - 2020-05-05
Added
- eInspect Module: PPECB Inspections made available for testing.
- Approval/Rejection/Withdrawn Email Notifications for End Users and via the API

Removed
- ePhyto Applications Copies no longer include Inspector Credentials [Security]
