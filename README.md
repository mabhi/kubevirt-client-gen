Go client for talking to [KubeVirt](https://github.com/kubevirt/kubevirt).


To download and install the Kubernetes API client code generator client-gen, run:
```
go install k8s.io/code-generator/cmd/client-gen@latest
```

The following command creates the client inside an example project called `kubevirt-client-gen` at the location one level up the current directory inside `github.com/mabhi/kubevirt-client-gen` :

```
~/go/bin/client-gen --input-base="kubevirt.io/api/" --input="core/v1" --output-package="github.com/mabhi/kubevirt-client-gen" --output-base="../" --clientset-name="versioned" --go-header-file boilerplate.go.txt 
```
