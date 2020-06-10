# hello-terratest

## Run Terraform manually
```
$ terraform init
$ terraform plan
$ terraform apply
...
hello = "Hello, Terratest!"
```

## Run Terratest
```
$ go test -timeout 30m
--- PASS: TestHelloTerratest (0.36s)
PASS
ok  	github.com/estensen/hello-terratest	0.775s
...
```

