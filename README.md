# Magento patches

The official Magento CE/OS patches, grouped in one place.

I verified that they can be correctly installed on a fresh Magento instance. USPS-related patches are not included as their installation throws an error in multiple cases.

Patches can be installed in numbering order. Just be careful with the two SUPEE-7405, install v1 then v1.1.

To install a patch, simply download the file in the root folder of your Magento instance and execute the command `sh ./PATCH_SUPEE-...`.

The list of security patches required for all Magento versions can be found [here](https://docs.google.com/spreadsheets/d/1MTbU9Bq130zrrsJwLIB9d8qnGfYZnkm4jBlfNaBF19M). But this list includes SUPEE-1533 which has to be reverted in order to apply SUPEE-8788 and ommits SUPEE-3941 which is required, again for SUPEE-8788.
