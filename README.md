# automatic-cloudflare-ddns


Creates or updates a Cloudflare A record with the current external IPv4 address.


# Usage

```
options:
  -h, --help            show this help message and exit
  -A, --authorization AUTHORIZATION
  -n, --names NAMES [NAMES ...]
  -t, --tries TRIES
  -v, --verbose
  -l, --logtofile
  -m, --maxlogfiles MAXLOGFILES
  ```

### Your Authorization key must have permission to edit DNS Records in your zone(s) which contain the records to change.