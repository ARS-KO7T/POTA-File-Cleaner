# POTA-File-Cleaner
The POTA File Cleaner takes an adi file exported from logging software and removes all superflous aid fields from each QSO record in the log while preserving the minimun adi fields necessary for POTA activator log uploads and organizes the fields for easy review if there are any issues uploading the activator log to the POTA App site.
This updated version will also automatically generate an adi file for multi-park (n-fer) activations by listing all park numbers separated by a comma-separated (e.g. US-1234, US-23456,US-5669).
The output adi file(s) also include the new adi fields of MY_POTA_REF, and POTA_REF for each QSO record in the log.
