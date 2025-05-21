# CA State Roadkill Project Data

This dataset contains data sourced from iNaturalist on roadkill observations in California up to April 2025.

## iNaturalist Queries (retrieved 2025-04-09)
### Observation Data
* [California Roadkill](iNaturalist/CA_State_Roadkill.csv)

### Query
* https://www.inaturalist.org/observations?quality_grade=any&identifications=any&projects%5B%5D=california-state-roadkill&spam=false

### Columns
* `observed_on`: Normalized date of observation
* `time_observed_at`: Normalized datetime of observation
* `quality_grade`: Quality grade of this observation. See Help section for details on what this means. See https://help.inaturalist.org/support/solutions/articles/151000169936
* `latitude`: Publicly visible latitude from the observation location
* `longitude`: Publicly visible longitude from the observation location
* `positional_accuracy`: Coordinate precision (yeah, yeah, accuracy != precision, poor choice of names)
* `private_latitude`: Private latitude, set if observation private or obscured
* `private_longitude`: Private longitude, set if observation private or obscured
* `public_positional_accuracy`: Maximum horizontal positional uncertainty in meters; includes uncertainty added by coordinate obscuration
* `scientific_name`: Scientific name of the observed taxon according to iNaturalist
* `common_name`: Common or vernacular name of the observed taxon according to iNaturalist

For more information about column headers, see https://www.inaturalist.org/terminology
