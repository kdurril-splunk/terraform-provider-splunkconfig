## 1.7.4 (July 29, 2024)
FEATURES:

* **Fixed** Added gzip compression to `splunkconfig_app_package` to resolve app inspect check_package_compression


## 1.7.3 (January 23, 2024)

FEATURES: 

* **Schema Change** Add Dynamic Data Active Archive settings to Index schema

## 1.7.2 (April 3, 2023)

FEATURES:

* **Fixed release workflow to use newer version of Go**

## 1.7.1 (March 30, 2023)

FEATURES:

* **New Capability Validation**: Adding `-` as a valid character in capability names

## 1.7.0 (February 8, 2022)

FEATURES:

* **New Data Source**: `splunkconfig_index_names`
* **New Data Source**: `splunkconfig_index_attributes`

## 1.6.1 (December 2, 2021)

FEATURES:

* **Schema Change**: Index has `datatype`.

## 1.6.0 (November 12, 2021)

FEATURES:

* **New Data Source**: `splunkconfig_app_package`
* **New Resource**: `splunkconfig_app_auto_version`
* **Deprecated Resource**: `splunkconfig_app_package`

## 1.5.0 (October 26, 2021)

FEATURES:

* **Data Source Enhancement**: `splunkconfig_lookup_attributes` implements `row_number_field`
* **Data Source Enhancement**: `splunkconfig_app_ids` implements `exclude_tag`

## 1.4.0 (October 19, 2021)

FEATURES:

* **Provider Change**: New configuration argument `configuration_path`.
* **Schema Change**: `Apps` can have `collections`.
* **New Tool**: `template-lookup-csv`

## 1.3.2 (September 28, 2021)

FIXES:

* **Schema Change**: Index names can have asterisks (*) for `srchIndexesAllowed`.

## 1.3.1 (September 27, 2021)

FIXES:

* **Schema Change**: `App` IDs can have dashes

## 1.3.0 (September 21, 2021)

FEATURES:

* **Schema Change**: `Apps` can have tags
* **Data Source Enhancement**: `splunkconfig_app_ids` implements `require_tag`

## 1.2.0 (September 3, 2021)

FEATURES:

* **Resource Enhancement**: `Lookups` generate transforms.conf when packaged with `splunkconfig_app_package`
* **New Data Source:** `app_ids`
* **New Data Source:** `app_attribtes`
* **Schema Change**: `Apps` can have ACLs

## 1.1.0 (August 23, 2021)

FEATURES:

* **New Data Source:** `splunkconfig_lookup_attributes`

## 1.0.0 (August 11, 2021)

Initial version
