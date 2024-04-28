# Helm Chart for deployment of Mediawiki Application and backend Database.

## To use this helm chart,
    1. Add the Helm Repo

            > helm repo add mediawikirepo https://pranav03singh.github.io/mediawikiapp/

    2. Get the charts details,
            > helm search repo mediawikirepo

    3. Install the chart
            > helm install mediawikiapp mediawikirepo/mediawiki
            > helm install mediawikidb mediawikirepo/mediawiki-db