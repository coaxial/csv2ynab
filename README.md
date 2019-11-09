# CSV 2 YNAB

This is a small utility to convert CSV files from eBanking webapps into the
format that YNAB expects for import. It targets my specific use case, but
hopefully can serve as a source of inspiration for anyone else attempting to do
the same.

I am very new to Go, so this will probably make your eyes bleed if you know Go
better than I do.

## Compatibility

I am using YNAB 4 (so called "old YNAB") in Wine with data from UBS Switzerland
and Revolut.

## Alternatives

Check out https://is.gd/ynabcsv. It processes your CSV files in the browser and
lets you choose which one of your bank's columns to use for YNAB's expected
columns.

## License

MIT (c) coaxial 2019. Do whatever you want with it, and don't blame me for it.
