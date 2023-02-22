This script generates a "Chargeback" of "actual" bytes-used per repository.

** NOTE: ** Binaries that appear multiple times in a repo will be counted once. Binaries appearing in multiple repositories will be counted once per repository!

Pre-requisite:
JFrog CLI installed and pre configured with admin credentials.
Sufficient local disk space ( could be several GB or more).

** IMPORTANT: **
The script invokes an expensive AQL against each repository. For very large repositories it will put a high load on the DB. Be careful using it in production environments.
