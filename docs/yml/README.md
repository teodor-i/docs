# 🧬 Full yaml

See [options](https://helmwave.github.io/yml/options/) for more details.

```yaml
project: my-project
version: 0.9.3


repositories:
- name: bitnami
  url: https://charts.bitnami.com/bitnami
  username: ""
  password: ""
  certfile: ""
  keyfile: ""
  cafile: ""
  insecureskiptlsverify: false
  force: false

releases:
- name:  ""
  chart: ""
  tags: []
  values: []
  store: {}
  options:
    chartpathoptions:
      cafile: ""
      certfile: ""
      keyfile: ""
      insecureskiptlsverify: false
      keyring: ""
      password: ""
      repourl: ""
      username: ""
      verify: false
      version: 1.0.0
    install: true
    devel: false
    namespace: test1
    skipcrds: false
    timeout: 15m0s
    wait: true
    waitforjobs: false
    disablehooks: false
    dryrun: false
    force: false
    resetvalues: false
    reusevalues: false
    recreate: false
    maxhistory: 10
    atomic: false
    cleanuponfail: false
    subnotes: false
    description: ""
    postrenderer: null
    disableopenapivalidation: false
```