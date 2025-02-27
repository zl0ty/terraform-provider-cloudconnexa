---
# generated by https://github.com/hashicorp/terraform-plugin-docs
page_title: "cloudconnexa Provider"
subcategory: ""
description: |-

---

# CloudConnexa Provider

!> **WARNING:** This provider is experimental and support for it is on a best-effort basis. Additionally, the underlying API for CloudConnexa is on Beta, which means that future versions of the provider may introduce breaking changes. Should that happen, migration documentation and support will also be provided on a best-effort basis.

Use this provider to interact with the [CloudConnexa API](https://openvpn.net/cloud-docs/developer/index.html).

<!-- schema generated by tfplugindocs -->
## Schema

### Required

- **base_url** (String) The base url of your CloudConnexa account.

### Optional

- **client_id** (String, Sensitive) If not provided, it will default to the value of the `CLOUDCONNEXA_CLIENT_ID` environment variable.
- **client_secret** (String, Sensitive) If not provided, it will default to the value of the `CLOUDCONNEXA_CLIENT_SECRET` environment variable.

### Credentials

To authenticate with the CloudConnexa API, you'll need the client_id and client_secret.
These credentials can be found in the CloudConnexa Portal.
Go to the Settings page and click on the API tab.
From there, you can enable the API and generate new authentication credentials.
Additionally, you'll find Swagger documentation for the API in the same location.

More documentation on the OpenVPN API can be found here:
[CloudConnexa API Documentation](https://openvpn.net/cloud-docs/developer/cloudconnexa-api.html)
