# Water Point Functionality and Service Delivery Monitoring Dataset - 2023

This dataset contains structured field survey responses collected from
water point inspections and interviews with community members or water
point committee representatives. Each record represents a single survey
event linked to a specific water point, including GPS coordinates,
enumerator metadata, timestamps, and detailed observations on
infrastructure condition, functionality, water availability, maintenance
practices, and governance arrangements.

## Usage

``` r
waterpointstatus
```

## Format

A tibble with 1425 rows and 45 variables

- waterpoint_id:

  Unique identifier assigned to each water point.

- latitude:

  Geographic latitude of the water point

- longitude:

  Geographic longitude of the water point

- waterpoint_image:

  File name or reference to image captured during the survey visit.

- functional_status:

  Operational status of the water point at time of visit

- downtime_duration:

  Reported length of time the water point has been non-functional or
  abandoned.

- abandon_reason:

  Primary reason the water point was abandoned or left non-functional.

- has_current_issue:

  Indicates whether any current technical or operational problem was
  observed.

- current_issue:

  Type of current problem affecting the water point.

- water_available_today:

  Indicates whether water was available on the day of the visit.

- continuous_30days:

  Indicates whether the water point provided uninterrupted water supply
  over the past 30 days.

- no_water_30days_reason:

  Reason for water interruptions within the last 30 days.

- repair_duration_days:

  Number of days taken to repair the water point after the most recent
  breakdown

- seasonal_unavailable:

  Indicates whether the water source becomes unavailable during certain
  seasons.

- seasonal_period:

  Time of year when water is typically unavailable due to seasonal
  variation.

- flow_test_possible:

  Indicates whether a flow rate test could be conducted during the
  visit.

- fill_time_20l:

  Time required to fill a 20-litre container during flow rate test.

- latrine_within_100m:

  Indicates presence of a latrine within 100 metres of the water point.

- observed_issues:

  General technical or structural problems observed during the visit,
  multiple responses possible

- water_quality_issues:

  Observed or reported water quality concerns

- preventive_maintenance:

  Indicates whether routine preventative maintenance is performed on the
  water point.

- maintenance_barrier:

  Main reason preventing regular preventative maintenance.

- user_population:

  Estimated number of people regularly using the water point.

- universal_access:

  Indicates whether all community members have access to the water
  point.

- households_no_access:

  Estimated number of households without access to the water point.

- access_barrier:

  Primary reason some households lack access to the water point.

- max_roundtrip_minutes:

  Maximum reported round-trip time in minutes to collect water.

- max_distance_metres:

  Maximum reported one-way walking distance to the water point.

- has_service_provider:

  Indicates whether a designated service provider or operator is
  responsible for the water point.

- provider_type:

  Type of service provider responsible for operation and maintenance

- has_tariff:

  Indicates whether users pay a tariff or fee for water access.

- tariff_frequency:

  Frequency at which the water tariff or user fee is collected.

- tariff_amount_mwk:

  Amount charged per tariff period in Malawi Kwacha

- tariff_cost_basis:

  Cost factors considered when setting the water tariff

- has_financial_records:

  Indicates whether financial records or books are maintained for the
  water point.

- has_positive_balance:

  Indicates whether financial records show a positive account balance.

- savings_or_loans:

  Indicates evidence of savings accumulation or loan repayment in
  financial records.

- record_balance_mwk:

  Reported balance recorded in financial books

- has_bank_account:

  Indicates whether the service provider maintains a formal bank
  account.

- bank_balance_mwk:

  Reported balance held in the bank account

- committee_year_formed:

  Year the water point committee was established.

- committee_member_count:

  Total number of members serving on the water point committee.

- committee_women_count:

  Number of women serving on the water point committee.

- treasurer_gender:

  Gender of the committee treasurer.

- months_unavailable:

  Total number of months per year the water source is unavailable.
