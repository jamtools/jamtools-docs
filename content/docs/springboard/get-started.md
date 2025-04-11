Note that dependencies in a springboard project must be kept in lockstep
The springboard CLI provides a way to do this
sb upgrade 0.15.0 --packages package.json,apps/mobile/package.json


This is because all code in this monorepo is released at the same time, to ensure any breaking situations between version mismatches
