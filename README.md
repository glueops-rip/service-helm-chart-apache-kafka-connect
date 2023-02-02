# service-helm-chart-apache-kafka-connect

`vault_path` : The path in vault containing the key `.dockerconfigjson`.

The secret must follow this convention

```
{"auths":{"https://index.docker.io/v1/":{"username":"example_username","password":"team:dckr_pat_example","email":"email@example.com","auth":"dGVhbTpkY2tyX3BhdF9leGFtcGxlCg=="}}}
```

Where `dGVhbTpkY2tyX3BhdF9leGFtcGxlCg==` is the `base64` encoded value of `team:dckr_pat_example`.