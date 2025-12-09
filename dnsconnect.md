# DNS Connect Domain to GH Pages
## Root DNS Configuration
## Old (depreciated) config
| Type  | Name | Content                |
| ----- | ---- | ---------------------- |
| ALIAS | @    | aidanlenahan.github.io |
| CNAME | www  | aidanlenahan.github.io |
## Recommended
| Type  | Name | Content                |
| ----- | ---- | ---------------------- |
| A     | @    | 185.199.108.153        |
| A     | @    | 185.199.109.153        |
| A     | @    | 185.199.110.153        |
| A     | @    | 185.199.111.153        |
| CNAME | www  | aidanlenahan.github.io |
---

If connecting this to GitHub pages, make sure the repo you are connecting to has a CNAME in its root (```/```) directory pointing to the domain or subdomain you plan on using, no matter what.
