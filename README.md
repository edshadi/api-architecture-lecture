# Architecting an API

## Versioning
APIs should be properly versioned. APIs evolve and change, we must do this while supporting
old versions. Otherwise, if you just change your API, a lot of your clients would be in trouble.
Although, we won't be developing multiple versions (today we're working on V1), it is important
that we plan for the future and properly namespace our documentation and work under V1 namespace.
