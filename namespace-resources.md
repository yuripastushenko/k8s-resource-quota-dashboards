# Dashboard for k8s clusters that use kube-prometheus for collecting metrics.
## About Dashboard
This dashboard will help you visualize resource utilization per namespace with resource quota.
### Singlestat panels
* CPU Requests Allocated / CPU Requests Quota
* CPU Limits Allocated / CPU Limits Quota
* CPU Actual Usage / CPU Requests Quota
* CPU Actual Usage / CPU Limits Quota
* RAM Requests Allocated / RAM Requests Quota
* RAM Limits Allocated / RAM Limits Quota
* RAM Actual Usage / RAM Requests Quota
* RAM Actual Usage / RAM Limits Quota

### Graph panels
#### CPU
* CPU Usage
* CPU Quota Limits
* CPU Quota Requests
* CPU Allocated Limits
* CPU Allocated Requests

#### RAM
* RAM Usage
* RAM Quota Limits
* RAM Quota Requests
* RAM Allocated Limits
* RAM Allocated Requests

#### Network
* Input
* Output

## How to use
After importing dashboard - create variable $source that will contain the datasource (if you are using different datasources for different cluster), or just hardcode it.

## How to contribute
Feel free to make PR in [github repository](https://github.com/yuripastushenko/k8s-resource-quota-dashboards).