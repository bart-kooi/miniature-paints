# Entries awaiting colour values

`paints.json` preserves researched paint and ancillary product entries that do not yet have verified RGB and hex values. These entries are kept outside `paints/*.md` because the catalogue importer requires numeric RGB channels and matching hex values for every row.

Each entry retains its source file, original column values, verified EAN codes and original Markdown row. Empty EAN cells remain unverified. No placeholder colour values have been assigned.

Once a colour is verified, move its entry back into the source table with matching RGB and hex values, then remove it from this file. Keep each source file's rows in one continuous table before its footer.
