README
This folder contains files that can be used as templates for your OCAPI resource configuration. The templates contain the minimum necessary configurations for OCAPI 

**IMPORTANT*** Do not replace existing OCAPI configurations with these files. Instead, add them at the end of any existing OCAPI configurations.

**IMPORTANT*** The examples using the "XXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX" client ID represent a customer's existing client ID. The examples using the "aaaaaaaaaaaaaaaaaaaaaaaaaaaaaa" client ID represent changes where a NEW customer client ID should be used. Although "aaaaaaaaaaaaaaaaaaaaaaaaaaaaaa" is acceptable for testing purposes, it should never be used in a customer's configuration.


The following template files represent three ways to configure the necessary OCAPI resources for a client ID for each OCAPI context (Data-Global, Shop-Global, Shop-Site).

The files with the "_min.json" suffix represents the minimum necessary resources for a client ID section in an empty OCAPI configuration.
The files with the "_addl.json" suffix represent using the minimum resources for a client ID section in an OCAPI configuration that already contains another client ID.
The files with the "_existing_clients.json" suffix represent using the minimum necessary resources added to an existing client ID section in an OCAPI configuration.

Note that the example files containing "sitegenesis" represent a Site-specific configuration. If a customer has multiple storefront sites participating in Data Manager, then the Site-specific changes must be applied to each Shop-Site context.

data_global_orgwide_min.json
data_global_orgwide_addl.json
data_global_orgwide_existing_clients.json

shop_global_orgwide_min.json
shop_global_orgwide_addl.json
shop_global_orgwide_existing_clients.json

shop_sitegenesis_min.json
shop_sitegenesis_addl.json
shop_sitegenesis_existing_clients.json
