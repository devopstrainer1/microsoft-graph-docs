
```Javascript

const options = {
	authProvider,
};

const client = Client.init(options);

let res = await client.api('/reports/getSkypeForBusinessPeerToPeerActivityMinuteCounts(period='D7')')
	.version('beta')
	.get();

```