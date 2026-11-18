# IMT Timeclock

Field time clock for IMT Construction (replaces HCSS myField). Installable web app hosted on GitHub Pages; data lives in the Supabase project `imt-data` (schema `timeclock`, app API in `public.tc_*`).

- Crew: employee number + 4-digit PIN, clock in/out with job, GPS stamp, Spanish/English.
- Foremen: approve crew hours, fix missed clock-outs (reason required, audited).
- Office: weekly regular/OT payroll for ComputerEase, certified payroll by job, employees, jobs, PINs.

Rules: pay week Mon–Sun (Central), overtime over 40 hours, 30-minute lunch deducted per day.
