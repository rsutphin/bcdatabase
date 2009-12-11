1.0.0
=====
- Split out from NUBIC internal `bcdatabase` project.
  (Changelog entries below reflect the relevant changes & version numbers from that project.)

0.4.1
=====
- Fix `bcdatabase encrypt` so that it doesn't re-encrypt already encrypted 
  epassword entries.

0.4.0
=====
- Use the YAML entry name as the "database" value if no other value is
  provided.  This is to DRY up PostgreSQL configurations where the username
  (already defaulted) and the database name are the same.

0.2.0
=====
- Change default encrypted secret password location

0.1.0
=====
- Support encrypted passwords
- Command-line utility (also called bcdatabase) for creating encrypted passwords
- Gem distribution

0.0.0
=====
Original release.