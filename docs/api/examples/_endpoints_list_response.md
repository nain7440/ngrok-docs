<!-- Code generated for API Clients. DO NOT EDIT. -->

#### Example Response

```json
{
	"endpoints": [
		{
			"bindings": ["public"],
			"created_at": "2024-12-18T10:07:49Z",
			"hostport": "50cd1f79a0ff.ngrok.paid:443",
			"id": "ep_2qNwihCNX40xX3yoPYeTNiaE1ZD",
			"name": "command_line",
			"principal": {
				"id": "usr_2qNwgC59wZbtm2YoH1z2lAQ0qpu",
				"uri": ""
			},
			"proto": "https",
			"public_url": "https://50cd1f79a0ff.ngrok.paid",
			"tunnel": {
				"id": "tn_2qNwihCNX40xX3yoPYeTNiaE1ZD",
				"uri": "https://api.ngrok.com/tunnels/tn_2qNwihCNX40xX3yoPYeTNiaE1ZD"
			},
			"tunnel_session": {
				"id": "ts_2qNwikRsTVdC2VGdQ05n78sxRcM",
				"uri": "https://api.ngrok.com/tunnel_sessions/ts_2qNwikRsTVdC2VGdQ05n78sxRcM"
			},
			"type": "ephemeral",
			"updated_at": "2024-12-18T10:07:49Z",
			"upstream_url": "http://localhost:80",
			"url": "https://50cd1f79a0ff.ngrok.paid"
		},
		{
			"bindings": ["public"],
			"created_at": "2024-12-18T10:07:46Z",
			"domain": {
				"id": "rd_2qNwiGkKyyCUGdkrZ0xJVnz0AK5",
				"uri": "https://api.ngrok.com/reserved_domains/rd_2qNwiGkKyyCUGdkrZ0xJVnz0AK5"
			},
			"edge": {
				"id": "edgtls_2qNwiChUhOALLpxoZM0Fmli9GpH",
				"uri": "https://api.ngrok.com/edges/tls/edgtls_2qNwiChUhOALLpxoZM0Fmli9GpH"
			},
			"hostport": "endpoint-example2.com:443",
			"id": "ep_2qNwiBV6ZXxWyOuMs5kZ9w7uzfT",
			"proto": "tls",
			"public_url": "tls://endpoint-example2.com",
			"type": "edge",
			"updated_at": "2024-12-18T10:07:46Z"
		}
	],
	"next_page_uri": null,
	"uri": "https://api.ngrok.com/endpoints"
}
```
