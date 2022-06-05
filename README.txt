`mdvl-pdfscissors` package for tool `pdfscissors` from
https://sites.google.com/site/pdfscissors.

Given a working `ant` command, the necessary jarfile is automatically retrieved.
It is used as-is without recompiling. See branch `test_compile_from_source` for
an incomplete (disfunctional!) effort to try to compile it from source.

Attempting to compile from source (a) produces unusable binaries and
(b) requires JPedal which seems to be impossible to compile from actual sources
as it dependes on proprietary SUN components that in turn supply native
libraries! Interestingly, these native libraries do not seem to be included
in pdfscissors itself, hence it should in theory be possible to work without
them?

!!! License note !!!

The license of pdfscissors is declared as “AGPL” without further specification
from the author's side. The JAR does seem to include a lot of third-party
dependencies under non-AGPL licenses, though. Use with caution.
