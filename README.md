# SF_D5.2
Установите Helm Chart prometheus-community/prometheus так, чтобы

в нём не было сервисов:

    pushgateway;
    node-exporter;
    alertnamager;

были только следующие поды:

    prometheus-server;
    prometheus-kube-state-metrics.
