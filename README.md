# HTG Service technician web module

Website: https://shutshavarnsu-maker.github.io/htg-service-web/

Technician module for HTG ERP menu 3.3, connected to the htg-dev Supabase project.
No separate login page: staff use their HTG ERP sign-in once the module is hosted inside the ERP.
Opened anywhere else (including this GitHub Pages copy) it only shows a link to the ERP.
DEV validation only: no ERP stock deduction, billing or receipt is performed.
Only assigned permanent staff accounts can access jobs and private photos.
Submission creates a pending integration event; acknowledgement requires a trusted server adapter.
Source, migrations and integration instructions: https://github.com/shutshavarnsu-maker/htg-service

Published files are generated from web/ using npm run build, not the historical local-only prototype.