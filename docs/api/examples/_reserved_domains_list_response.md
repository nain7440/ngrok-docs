<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"reserved_domains": [
		{
			"acme_challenge_cname_target": null,
			"certificate": {
				"id": "cert_2qL7Sl3XJANzRygN2bHyTIyPVjy",
				"uri": "https://api.ngrok.com/tls_certificates/cert_2qL7Sl3XJANzRygN2bHyTIyPVjy"
			},
			"certificate_management_policy": null,
			"certificate_management_status": null,
			"cname_target": "2udamkamcl8pjmrff.3kkdtbgxbvqvgn67y.local-ngrok-cname.com",
			"created_at": "2024-12-17T10:06:43Z",
			"domain": "myapp.mydomain.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2qL7SqWB1xjMWNA3lCP1K89qjzY",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2qL7SqWB1xjMWNA3lCP1K89qjzY"
		},
		{
			"acme_challenge_cname_target": null,
			"certificate": null,
			"certificate_management_policy": {
				"authority": "letsencrypt",
				"private_key_type": "ecdsa"
			},
			"certificate_management_status": {
				"provisioning_job": {
					"error_code": null,
					"msg": "Managed certificate provisioning in progress.",
					"retries_at": null,
					"started_at": "2024-12-17T10:06:43Z"
				},
				"renews_at": null
			},
			"cname_target": "4knqktdwka2umyjjc.3kkdtbgxbvqvgn67y.local-ngrok-cname.com",
			"created_at": "2024-12-17T10:06:43Z",
			"description": "Device 0001 Dashboard",
			"domain": "manage-0002.app.example.com",
			"error_redirect_url": null,
			"http_endpoint_configuration": null,
			"https_endpoint_configuration": null,
			"id": "rd_2qL7SkNZeVtnGONergAC4WGuZzh",
			"metadata": "{\"service\": \"dashboard\"}",
			"region": "",
			"uri": "https://api.ngrok.com/reserved_domains/rd_2qL7SkNZeVtnGONergAC4WGuZzh"
		}
	],
	"uri": "https://api.ngrok.com/reserved_domains"
}
```
