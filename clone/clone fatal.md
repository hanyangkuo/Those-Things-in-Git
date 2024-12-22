
# Filename too long
> fatal: cannot create directory at 'plugin/trino-delta-lake/src/test/resources/databricks153/type_widening_partition/Byte_to_Short=1/byte_to_int=1/byte_to_long=1/byte_to_decimal=1/Byte_to_Double=1/short_to_int=1/short_to_long=1/short_to_decimal=1/short_to_double=1': Filename too long
warning: Clone succeeded, but checkout failed.
You can inspect what was checked out with 'git status'
and retry with 'git restore --source=HEAD :/'

**Solution:** `git config --system core.longpaths true`
