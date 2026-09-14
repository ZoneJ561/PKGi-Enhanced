PKGi Enhanced v1.1.58 fixes catalog titles containing Japanese and other
UTF-8 text while preserving the original PSP UI font, spacing, charging icon,
and menu symbols.

Catalog title fitting is cached to keep the settings menu responsive when large
catalogs and all regions are selected. The Unicode glyph cache also releases
reused textures to avoid leaking graphics memory during long sessions.
