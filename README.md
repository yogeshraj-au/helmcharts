# helmcharts
This repo contains helm chart for nginx app.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add app [https://yogeshraj-au.github.io/helmcharts](https://yogeshraj-au.github.io/helmcharts/)

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
<alias>` to see the charts.

To install the  chart:

    helm install nginx app/sampleapp

To uninstall the chart:

    helm delete sampleapp
