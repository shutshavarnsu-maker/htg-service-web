# HTG Service technician web module

Website: https://shutshavarnsu-maker.github.io/htg-service-web/

Authenticated shared-data application connected to the htg-dev Supabase project.
DEV validation only: no ERP stock deduction, billing or receipt is performed.
Only assigned permanent staff accounts can access jobs and private photos.
Submission creates a pending integration event; acknowledgement requires a trusted server adapter.
Source, migrations and integration instructions: https://github.com/shutshavarnsu-maker/htg-service

Published files are generated from web/ using npm run build, not the historical local-only prototype.