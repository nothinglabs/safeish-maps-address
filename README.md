# Safeish map store address

`store.json` holds the address of the Safeish map store. The Safeish app reads
it only when its main address, `https://nothinglabs.com/safeish/maps/`, does
not answer.

To move the maps to another host, change `storeUrl` here and the redirect on
nothinglabs.com. The address must be an HTTPS folder that ends with a slash
and serves `index.json`.

Do not rename or delete this repository: its address is built into the app.
