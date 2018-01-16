# Naming conventions

# Conventions
## Model-level views and functions
- **_Anchor** holds anchor metadata
- **_Attribute** holds attribute metadata
- **_Tie** holds tie metadata
- **_Knot** holds knot metadata
- **_Schema** hold schema changes
- **_Schema_expanded** holds the information from _Schema plus extra information about high-level configuration
- **_Evolution** holds a view of the schema that tells you which bits existed for a given point in time

## Base tables & model name conventions
- **anchors** have a two letter mnemonic and a proper-case descriptor `[A-Z]{2}_([A-Z][a-z]*)+` e.g. AC_Actor
- **knots** have a three letter mnemonic and a proper-case descriptor `[A-Z]{3}_([A-Z][a-z]*)+` e.g. PRF_ProfessionalLevel
- **attributes** have the anchor name plus have a three letter mnemonic and a proper-case descriptor `[A-Z]{2}_([A-Z][a-z]*)_[A-Z]{3}_([A-Z][a-z]*)+` e.g. AC_Actor_PRF_ProfessionalLevel
- **ties** have the anchor mnemonics and lower-case role descriptors `[A-Z]{2}_([a-Z][A-z]*)+_[A-Z]{2}_([a-Z][A-z]*)+` e.g. AC_wasCast_PE_in

