---
title: "ConoHa VPS Ver 3.0"
date: 2019-03-03T16:39:46+01:00
draft: false
slug: conohav3
dnsprovider:
  since:    "v4.23.1"
  code:     "conohav3"
  url:      "https://www.conoha.jp/"
---

<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->
<!-- providers/dns/conohav3/conohav3.toml -->
<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->


Configuration for [ConoHa VPS Ver 3.0](https://www.conoha.jp/).


<!--more-->

- Code: `conohav3`
- Since: v4.23.1


Here is an example bash command using the ConoHa VPS Ver 3.0 provider:

```bash
CONOHA_TENANT_ID=487727e3921d44e3bfe7ebb337bf085e \
CONOHA_API_USER_ID=xxxx \
CONOHA_API_PASSWORD=yyyy \
lego --email you@example.com --dns conohav3 -d '*.example.com' run
```




## Credentials

| Environment Variable Name | Description |
|-----------------------|-------------|
| `CONOHA_API_PASSWORD` | The API password |
| `CONOHA_API_USER_ID` | The API user ID |
| `CONOHA_TENANT_ID` | Tenant ID |

The environment variable names can be suffixed by `_FILE` to reference a file instead of a value.
More information [here]({{% ref "dns#configuration-and-credentials" %}}).


## Additional Configuration

| Environment Variable Name | Description |
|--------------------------------|-------------|
| `CONOHA_HTTP_TIMEOUT` | API request timeout in seconds (Default: 30) |
| `CONOHA_POLLING_INTERVAL` | Time between DNS propagation check in seconds (Default: 2) |
| `CONOHA_PROPAGATION_TIMEOUT` | Maximum waiting time for DNS propagation in seconds (Default: 60) |
| `CONOHA_REGION` | The region (Default: c3j1) |
| `CONOHA_TTL` | The TTL of the TXT record used for the DNS challenge in seconds (Default: 60) |

The environment variable names can be suffixed by `_FILE` to reference a file instead of a value.
More information [here]({{% ref "dns#configuration-and-credentials" %}}).




## More information

- [API documentation](https://doc.conoha.jp/reference/api-vps3/)

<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->
<!-- providers/dns/conohav3/conohav3.toml -->
<!-- THIS DOCUMENTATION IS AUTO-GENERATED. PLEASE DO NOT EDIT. -->
