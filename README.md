### Simple Java Application Deployment from Command Line Interface using S2i.


`$ git clone https://github.com/ibm-aws/java-s2i-sample.git`

`oc new-project java-s2i`

`oc new-app java:11~https://github.com/ibm-aws/java-s2i-sample.git`


`oc logs -f bc/java-s2i`

`oc expose svc java-s2i`
