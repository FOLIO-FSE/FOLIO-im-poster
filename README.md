# FOLIO-im-poster
Posts FOLIO ILS Items and Holdings into a FOLIO tenant.

A few tweaks are added to the objects

In order to hook up with the right Instance record, these are looked up using the old bib record ID wich were added when the bib records were imported.

# Usage
## posting holdings
python3 main.py holdings PATH_TO_HOLDINGS_JSONs OKAPI_URL TENANT_ID X-OKAPI-TOKEN

## posting Items
python3 main.py holdings PATH_TO_HOLDINGS_JSONs OKAPI_URL TENANT_ID X-OKAPI-TOKEN
