# k8s-blue-green

The `k8s-blue-green` extends kubernetes with functionlity to execute [blue-green deployments](https://martinfowler.com/bliki/BlueGreenDeployment.html)

that was built as an exercise on [Programming Kubernetes: Developing Cloud-Native Applications](https://programming-kubernetes.info) and follow the [example](https://github.com/programming-kubernetes/cnat) provided by the book

for sake of exercise the controller is implemented here in three different ways:

* Following the [`sample-controller`](https://github.com/kubernetes/sample-controller) in [client-go](client-go/)
* Using [`Kubebuilder`](https://github.com/kubernetes-sigs/kubebuilder) in [kubebuilder](kubebuilder/)
* Using the [`Operator SDK`](https://github.com/operator-framework/operator-sdk) in [operator](operator/)
