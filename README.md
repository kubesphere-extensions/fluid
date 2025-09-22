## Introduction

[Fluid](https://github.com/fluid-cloudnative/fluid) is an open-source, Kubernetes-native distributed dataset orchestrator and accelerator, designed for data-intensive applications such as big data and artificial intelligence. It is hosted as a sandbox project by the Cloud Native Computing Foundation (CNCF). Fluid enables the transformation of distributed caching systems (such as Alluxio and JuiceFS) into observable cache services with self-management, elastic scaling, and self-healing capabilities by supporting dataset operations. Additionally, by providing data cache location information, Fluid offers data affinity scheduling for applications using datasets.

The Fluid plugin is a KubeSphere extension based on Fluid, providing a visual interface for dataset management, data loading, runtime management, and more. It aims to offer a better user experience for managing Fluid core resources, lowering the barrier of CLI operations, and improving the management efficiency of data-intensive applications.

### Main Features

- **Dataset Management**: Supports creation, viewing, editing, and deletion of datasets.
- **Data Load Tasks**: Visual management of data loading tasks with support for multiple loading strategies.
- **Runtime Management**: Monitors the status and events of various runtimes (such as Alluxio, JuiceFS, GooseFS, etc.).
- **Multi-Cluster and Namespace Support**: Allows switching between different clusters and namespaces, suitable for multi-tenant scenarios.

### Installation

- Find the Fluid extension component on the Extension Marketplace page, click Install, select the latest version, and click the Next button.
- On the Extension Installation tab page, click and modify the extension configuration as needed. After configuration, click the Start Installation button to begin installation.
- After installation is complete, click the Next button to enter the cluster selection page. Select the clusters to install, click Next, and proceed to the Differential Configuration page.
- Update the differential configuration as needed. After updating, start the installation and wait for it to complete.

### Configuration

Click on the extension component configuration, and control whether to install the frontend by setting enabled.
```yaml
frontend:
  enabled: true
```

### Contact and Support

If you have any questions or suggestions, feel free to submit an issue or participate in community discussions.
