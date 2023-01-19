# payag
iykyk. sub in for originals to make it prideful.

changes:
+ menu images (cg_la/2d/eng/male/lyt/menu_FLD_000*.arc)
  + swapped FLD000a with FLD000c; swapped FLD000b with FLD000d
+ character models (cg_la/3d/chr/model/PCC/PCC***.cmp)
  + swapped PCC000.cmp-PCC026.cmp with PCC027.cmp-PCC053.cmp; swapped PCC121.cmp-PCC147.cmp with PCC148.cmp-PCC174.cmp; swapped PCC175.cmp & PCC176.cmp with each other
+ startup menu text (param_la/eng/*/menu/menu_text.dat)
+ name entries (param_la/eng/*/menu/name_entry.dat)
  + fixed issue where names would include full-width latin characters instead of the expected half-width ones
+ save images (cg_la/2d/eng/male/lyt/OTHR_001a.arc):
  + may not work, try .bak with the following instructions through if it doesn't:
    + export as .tiff, make sure to change value at 0x01F to 40 (hex)/@ (asci) in overwrite mode (edit->overwrite) to fix image after import
    + icr what tool this info is for, probably wiimms szs... might be able to do this more easily with dolphin at this point
+ parent terms (param_la/eng/*/chara/pcCallName_*.stb)
  + swapped M with W, vice versa
+ love events (msglang/en/*/love*.mpc)

incomplete:
+ outfit text (param_la/eng/*/menu/costume_text.dat)
+ regular conversation text (talk_la/eng/*)
+ model animations (i think under cg/3d/chr/mot/*)
+ fix broken stuff, whatever that is

thanks to frogglegged (https://frogglegged.tumblr.com) for being a real one and getting this off the ground
