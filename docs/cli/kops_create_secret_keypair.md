
<!--- This file is automatically generated by make gen-cli-docs; changes should be made in the go CLI command code (under cmd/kops) -->

## kops create secret keypair

Create a secret keypair.

### Synopsis


Create a secret keypair

### Examples

```
  Add a ca certificate and private key.
  kops create secret keypair ca \
  --cert ~/ca.pem --key ~/ca-key.pem \
  --name k8s-cluster.example.com --state s3://example.com
```

### Options inherited from parent commands

```
      --alsologtostderr                  log to standard error as well as files
      --config string                    config file (default is $HOME/.kops.yaml)
      --log_backtrace_at traceLocation   when logging hits line file:N, emit a stack trace (default :0)
      --log_dir string                   If non-empty, write log files in this directory
      --logtostderr                      log to standard error instead of files (default false)
      --name string                      Name of cluster. Overrides KOPS_CLUSTER_NAME environment variable
      --state string                     Location of state storage. Overrides KOPS_STATE_STORE environment variable
      --stderrthreshold severity         logs at or above this threshold go to stderr (default 2)
  -v, --v Level                          log level for V logs
      --vmodule moduleSpec               comma-separated list of pattern=N settings for file-filtered logging
```

### SEE ALSO
* [kops create secret](kops_create_secret.md)	 - Create a secret.
* [kops create secret keypair ca](kops_create_secret_keypair_ca.md)	 - Add a ca cert and key
