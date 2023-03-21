# Helm Charts

Official **Helm Charts** repo for `k-cloud-labs`.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add k-cloud-labs https://k-cloud-labs.github.io/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
k-cloud-labs` to see the charts.

To install the <chart-name> chart:

    helm install kinitiras-webhook k-cloud-labs/kinitiras --namespace kinitiras-system --create-namespace

To uninstall the chart:

    helm delete kinitiras-webhook --namespace kinitiras-system

