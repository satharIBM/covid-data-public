Repository for all public source data used by
[covid-data-model](https://github.com/covid-projections/covid-data-model)
and/or
[covid-projections](https://github.com/covid-projections/covid-data-model)

Notes:
* Use README.md files to document where data has been sourced from.
* When committing updated data, include timestamp / version info to help
  describe the exact version of the data that's being imported. To the
  extent possible, we want clear audit trails for incoming data.
* Don't check in multiple versions of the same data. We can rely on git history
  instead.
* If data is being downloaded / scraped by a script, check the script in under
  scripts/
