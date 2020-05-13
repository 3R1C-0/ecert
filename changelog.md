# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased - Scheduled 2020-05-15 (UAT)

Added
- Phytosanitary Certificate for Re-Export enabled
- Archive button for completed ePhyto's

Changed
- Active state for Statuses [UX]
- AJAX loader for View Applications [UX]
- Clear Filter for Grid (View Applications) [UX]
- Global Pagination - Various Improvements [Fix]
- Agreements - Multiple commodities text wrapped [UX]

Fixed
- Special Characters are now encoded for both End & API Users

## 0.0.2 - 2020-05-12
Added
- Central Business Register (CBR) Business Linking - Link Businesses and lock the viewing of ePhyto Applications to specific businesses

Fixed
- Agreements - Print/View Agreements no longer returns an error
- Age Column restored
- Inspector Name Column restored

## 0.0.1 - 2020-05-05
Added
- eInspect Module: PPECB Inspections made available. Addendums to be added digitally
- Approval/Rejection/Withdrawn Email Notifications for End Users and via the API

Removed
- ePhyto Applications Copies no longer include Inspector Credentials [Security]
