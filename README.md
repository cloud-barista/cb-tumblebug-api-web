# GitHub Pages to host CB-Tumblebug API Documentation

CB-Tumblebug is a Framework for Cloud-Barista Platform to Manage Multi-Cloud Infra Service.
(https://github.com/cloud-barista/cb-tumblebug)

This repository is to host CB-Tumblebug API Documentation in GitHub Pages.

The API document is for CB-Tumblebug main branch (the latest dev branch). 
(https://github.com/cloud-barista/cb-tumblebug/tree/main)


## Access the API documentation page

Access to: https://cloud-barista.github.io/cb-tumblebug-api-web/
(Authorize with `default`/`default`)

The main page will show `swagger.yaml` in main branch of CB-Tumblebug repository.

(https://github.com/cloud-barista/cb-tumblebug/blob/main/src/docs/swagger.yaml)


## How to change veiw for each API version

You can change view accoring to API versions in https://github.com/cloud-barista/cb-tumblebug/tree/main/src/docs

For instance, 

For API main latest, access to 
- https://cloud-barista.github.io/cb-tumblebug-api-web
- https://cloud-barista.github.io/cb-tumblebug-api-web/?url=https://raw.githubusercontent.com/cloud-barista/cb-tumblebug/main/src/docs/swagger.yaml

For API v0.3.0, access to 
- https://cloud-barista.github.io/cb-tumblebug-api-web/?url=https://raw.githubusercontent.com/cloud-barista/cb-tumblebug/main/src/docs/v0.3.0.yaml

For API vX.Y.Z, access to 
- https://cloud-barista.github.io/cb-tumblebug-api-web/?url=https://raw.githubusercontent.com/cloud-barista/cb-tumblebug/main/src/docs/vX.Y.Z.yaml
