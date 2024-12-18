<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"next_page_uri": null,
	"tls_edges": [
		{
			"backend": null,
			"created_at": "2024-12-18T10:07:57Z",
			"description": "acme tls edge",
			"hostports": ["example.com:443"],
			"id": "edgtls_2qNwjmJzadAkvpvDYmKXZPTtUTj",
			"ip_restriction": null,
			"metadata": "{\"environment\": \"staging\"}",
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qNwjmJzadAkvpvDYmKXZPTtUTj"
		},
		{
			"backend": {
				"backend": {
					"id": "bkdhr_2qNwiEMbuX3YQZ7UPuRtYpRPWtA",
					"uri": "https://api.ngrok.com/backends/http_response/bkdhr_2qNwiEMbuX3YQZ7UPuRtYpRPWtA"
				},
				"enabled": true
			},
			"created_at": "2024-12-18T10:07:45Z",
			"description": "acme tls edge",
			"hostports": ["endpoint-example2.com:443"],
			"id": "edgtls_2qNwiChUhOALLpxoZM0Fmli9GpH",
			"ip_restriction": null,
			"mutual_tls": null,
			"policy": null,
			"tls_termination": null,
			"traffic_policy": null,
			"uri": "https://api.ngrok.com/edges/tls/edgtls_2qNwiChUhOALLpxoZM0Fmli9GpH"
		}
	],
	"uri": "https://api.ngrok.com/edges/tls"
}
```
