This repo saves all the initialization scripts needed for all the components of DC4H which have as database MongoDB.

This is used to test the deployment using another url than the one provided (https://xvalue-deploy.dedalus.eu).

# Modifications

The script regarding the component Discovery Service under the version 4.1.1 has been modified to include the registration of a client for Audit with a predefined ClientId and Secret.

This modification is included in the file xdiscovery-service-4.1.1/x1v1/db/xdiscovery-service/mongo/4.1.1.js
