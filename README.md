# KAZU update metadata

This public repository contains only the small metadata manifest required by
the KAZU update checker. It contains no plugin source, licenses, credentials,
or installer binaries.

Beta installers are stored separately in the private
`everyreasontopanic/kazu-beta-downloads` repository. Its release URLs require
an explicitly authorized GitHub account signed in through the browser.

## Safe release order

1. Build and verify the new macOS and Windows installers.
2. Upload installers and checksums to the private beta-download release.
3. Confirm an invited tester can download both installers.
4. Change `latest.json` to the new version as the final publication step.

Never place access tokens, passwords, signed temporary URLs, or other secrets
in this repository. Everything here is intentionally public.

