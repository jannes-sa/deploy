# deploy

This binary deployment for deploy service to kubernetes and docker


### Setup Environment
1. GOENV => (local,kube,dev,prod)
2. GOAPP => (account)
3. APPVERSION => (v1,v2)
4. GOPATH => to/your/go/path/work/dir

### Autoscale Service Setup
1. AS => 1 -> (to turn on Auto Scale feature) && 0 -> (to turn off Auto Scale feature)
2. MINPOD => (1,2) (to define minimum replica cluster)
3. MAXPOD => (2,3,4) (to define maximum replica cluster)
4. CPUHOLD => (80) (to defined maximum treshold to create replicas in cluster)
