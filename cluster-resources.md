# Dashboard for k8s clusters that use kube-prometheus for collecting metrics.
## About Dashboard
This dashboard will help you visualize resource utilization by cluster with resource quota.
### Pie Charts
* CPU Allocated Requests by Namespace
* CPU Allocated Limits by Namespace
* RAM Allocated Requests by Namespace
* RAM Allocated Limits by Namespace

### Singlestat panels
* CPU Namespaces Limits Quota / CPU Cluster Resources
* CPU Namespaces Requests Quota / CPU Cluster Resources
* CPU All Pods Requests / CPU Cluster Resources
* CPU All Pods Limits / CPU Cluster Resources
* RAM Namespaces Limits Quota / RAM Cluster Resources
* RAM Namespaces Requests Quota / RAM Cluster Resources
* RAM All Pods Requests / RAM Cluster Resources
* RAM All Pods Limits / RAM Cluster Resources
* Actual Pods Count / Pods quota
### Graph panels
#### CPU
* CPU All Allocable Resources
* CPU Actual Usage
* CPU Quota Limits
* CPU Quota Requests
* CPU Used Limits
* CPU Used Requests

#### RAM
* RAM All Allocable Resources
* RAM Actual Usage
* RAM Quota Limits
* RAM Quota Requests
* RAM Used Limits
* RAM Used Requests

#### Pods Count per Node
* Pods per node

## How to use
After importing dashboard - create variable $source that will contain the datasource (if you are using different datasources for different cluster), or just hardcode it.

## How to contribute
Feel free to make PR in [github repository](https://github.com/yuripastushenko/k8s-resource-quota-dashboards).