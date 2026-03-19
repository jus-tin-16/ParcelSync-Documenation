# Changelog

All changes of ParcelSync will be be documented in this document.

## v1.3.0-alpha - March 19, 20266

### Added in v1.3.0-alpha

- Approval of Authorized Person &rightarrow; every registered person is not going to be subject for approval before officially listed as approved. The property manager can either approve or disapprove.

### Fixes in v1.3.0-alpha

- The images of Authorized Person is now viewable.
- Notifications for Authorized Persons are now only allowed for those who are approved
- The modified forms for registering authorized persons is fixed.

## v1.2.0-alpha - March 17, 2026

### Added in v1.2.0-alpha

- Archive Delivery Logs Bot &rightarrow; it automatically archive the delivery logs which statuses are `claimed` and `returned` after 30 days.

- Old Photo Clean Up Bot &rightarrow; A bot that will run when old photos of QR and Parcel are stored after 30 days will be transfered to Google Drive `trash`.

- Email Report &rightarrow; A report will be sent to the property manager whenever the archive or cleanup occured.

### Fixed in v1.2.0-alpha

- The formula for archiving is changed using HOUR()/24 conversion

## v1.1.0-alpha — March 16, 2026

### Added in v1.1.0-alpha

- Shelf location tracking (Enum field, allows custom values, default: Guard Desk)

- Optional package weight field (kg)

- Tenant ID form validation (regex: TNT-[a-f0-9]{8})

- Tenant ID description text to prevent accidental editing

### Changed

- Package size retained alongside new weight field

- AppScript Forms deployed for Authorized Persons (backup or secondary feature)
