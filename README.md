# automatic-cloudflare-ddns


Creates or updates a Cloudflare A record with the current external IPv4 address.

# Installation

Install using pip : `pip install automatic-cloudflare-ddns`

# Usage

`python -m automatic_cloudflare_ddns -A [AUTHORIZATION] -n [List of domain names to update seperated by spaces]`


Add to your crontab (with `crontab -e`) or another scheduled runner


```
options:
  -h, --help            show this help message and exit
  -A, --authorization AUTHORIZATION *REQUIRED*
  -n, --names NAMES [NAMES ...] *REQUIRED*
  -t, --tries TRIES
  -v, --verbose
  -l, --logtofile
  -m, --maxlogfiles MAXLOGFILES
  ```

### Your Authorization key must have permission to edit DNS Records in your zone(s) which contain the records to change.