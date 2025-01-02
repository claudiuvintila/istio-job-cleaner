Once Helm has been set up correctly, add the repo as follows:

    helm repo add claudiuvintila https://claudiuvintila.github.io/istio-job-cleaner


To install the istio-job-cleaner chart:

    helm install istio-job-cleaner claudiuvintila/istio-job-cleaner

To uninstall the chart:

    helm delete istio-job-cleaner
