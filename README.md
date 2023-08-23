# Using Random Forest to classify objects from SDSS DR18


In this notebook we want to test our capabilities in using classification algorithms to distinguish between
Galaxies and Quasars from the dataset. We’re going to use python package querySDSS which makes a
specific SQL query to SDSS DR18 and returns a table with at least 2500 observations of
- **Objid, Specobjid** - Object Identifiers
- **ra** - J2000 Right Ascension
- **dec** - J2000 Declination
- **redshift** - Final Redshift of the celestial object
- **u**, **g**, **r**, **i**, and **z** - magnitude fit for u, g, r, i, and z. (they correspond to the five photometric bands:
ultraviolet band, green band, red band, infrared band, and near infrared band respectively)
- **run** - Run number
- **rerun** - Rerun number
- **camcol** - Camera column
- **field** - Field number
- **extinction_u** - Extinction in u-band
- **extinction_g** - Extinction in g-band
- **extinction_r** - Extinction in r-band
- **extinction_i** - Extinction in i-band
- **extinction_z** - Extinction in z-band
