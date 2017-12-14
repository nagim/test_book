{% sample lang="bash" %}
Let's make some noise. {{ book.apiBaseUri }}

```bash
curl {{ book.apiBaseUri }}/v2/components \
   -u {EMAIL}:{APIKEY} \
   -H 'Accept: application/json'
```
