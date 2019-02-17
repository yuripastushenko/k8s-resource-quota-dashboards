# Dashboard for k8s clusters that use kube-prometheus for collecting metrics.
## About Dashboard
This dashboard will help you visualize resource utilization per pod or container.

### Graph panels
#### CPU
* Actual usage
* Requested
* Limited

#### RAM
* Actual usage
* Requested
* Limited

#### Network
* Input
* Output

## How to use
After importing dashboard - create variable $source that will contain the datasource (if you are using different datasources for different cluster), or just hardcode it.

## How to contribute
Feel free to make PR in [github repository](https://github.com/yuripastushenko/k8s-resource-quota-dashboards).