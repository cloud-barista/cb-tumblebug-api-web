# GitHub Pages to host CB-Tumblebug API Documentation

CB-Tumblebug is a Framework for Cloud-Barista Platform to Manage Multi-Cloud Infra Service.
(https://github.com/cloud-barista/cb-tumblebug)

This repository is to host CB-Tumblebug API Documentation in GitHub Pages.

```
[NOTE] Development stage of CB-Tumblebug 
CB-Tumblebug is currently under development. 
So, we do not recommend using the current release in production.
Please note that the functionalities of CB-Tumblebug are not stable and secure yet.
If you have any difficulties in using CB-Tumblebug, please let us know.
(Open an issue or Join the cloud-barista Slack)
```

The API document is for CB-Tumblebug master branch (the latest dev branch). 
(https://github.com/cloud-barista/cb-tumblebug/tree/master)


## Access the API documentation page

Access to: https://cloud-barista.github.io/cb-tumblebug-api-web/
(Authorize with `default`/`default`)

The main page will show `swagger.yaml` in master branch of CB-Tumblebug repository.

(https://github.com/cloud-barista/cb-tumblebug/blob/master/src/docs/swagger.yaml)


## How to change veiw for each API version

You can change view accoring to API versions in https://github.com/cloud-barista/cb-tumblebug/tree/master/src/docs

For instance, 

For API master latest, access to 
- https://cloud-barista.github.io/cb-tumblebug-api-web
- https://cloud-barista.github.io/cb-tumblebug-api-web/?url=https://raw.githubusercontent.com/cloud-barista/cb-tumblebug/master/src/docs/swagger.yaml

For API v0.3.0, access to 
- https://cloud-barista.github.io/cb-tumblebug-api-web/?url=https://raw.githubusercontent.com/cloud-barista/cb-tumblebug/master/src/docs/v0.3.0.yaml

For API vX.Y.Z, access to 
- https://cloud-barista.github.io/cb-tumblebug-api-web/?url=https://raw.githubusercontent.com/cloud-barista/cb-tumblebug/master/src/docs/vX.Y.Z.yaml
