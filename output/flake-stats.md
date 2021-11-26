# odo test statistics
Last update: 2021-11-26 02:00:30 (UTC)

Generated with https://github.com/kadel/odo-tools
## FLAKY TESTS: Failed test scenarios in past 14 days
| Failure Score<sup>*</sup> | Failures | Test Name | Last Seen | PR List and Logs 
|---|---|---|---|---|
| 90 | 3 | [ssh:Fedora-32-minikube] [Fail] odo link command tests for OperatorHub when one component is deployed when another component is deployed [It] should link the two components successfully without service binding operator  |  | 3: [#5244](https://github.com/openshift/odo/pull/5244)<sup>[1](https://storage.googleapis.com/origin-ci-test/pr-logs/pull/openshift_odo/5244/pull-ci-openshift-odo-main-psi-kubernetes-integration-e2e/1463168091184697344/build-log.txt)</sup> [#5237](https://github.com/openshift/odo/pull/5237)<sup>[1](https://storage.googleapis.com/origin-ci-test/pr-logs/pull/openshift_odo/5237/pull-ci-openshift-odo-main-psi-kubernetes-integration-e2e/1463493708052697088/build-log.txt)</sup> [#5228](https://github.com/openshift/odo/pull/5228)<sup>[1](https://storage.googleapis.com/origin-ci-test/pr-logs/pull/openshift_odo/5228/pull-ci-openshift-odo-main-psi-kubernetes-integration-e2e/1463447021150015488/build-log.txt)</sup> 
| 40 | 2 | [ssh:Fedora-32-minikube] [Fail] odo link command tests for OperatorHub Operators are installed in the cluster when a component and a service are deployed when a storage is added and deployed when a link between the component and the service is created [It] should run odo push successfully  |  | 2: [#5252](https://github.com/openshift/odo/pull/5252)<sup>[1](https://storage.googleapis.com/origin-ci-test/pr-logs/pull/openshift_odo/5252/pull-ci-openshift-odo-main-psi-kubernetes-integration-e2e/1463967354881839104/build-log.txt)</sup> [#5228](https://github.com/openshift/odo/pull/5228)<sup>[1](https://storage.googleapis.com/origin-ci-test/pr-logs/pull/openshift_odo/5228/pull-ci-openshift-odo-main-psi-kubernetes-integration-e2e/1463440061558165504/build-log.txt)</sup> 


<sup>*</sup> - Failure score is an arbitrary severity estimate, and is approximately `(# of PRs the test failure was seen in * # of test failures) / (days since failure)`. See code for full algorithm -- PRs welcome for algorithm improvements.
