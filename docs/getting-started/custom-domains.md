# Custom Domains

## Register

The first step will be done at Scribo's Dashboard, where you need to add a new **Domain** to your team.

After this process, you will need to configure a new DNS registry on your DNS provider.

## Main Domain

If you are trying to configure the primary domain like `my-site.com.br`, all you need to do is add the following registry on your DNS provider.

| Type | Name   | Value                       |
| -------- | ------ | --------------------------------- |
| A     | @ | 76.76.21.21 |

After some minutes, check if your domain is verified and working accessing Scribo's dashboard.

## Sub Domain

If you need to point a subdomain to Scribo, add the following registry on your DNS provider:

| Type | Name   | Value                       |
| -------- | ------ | --------------------------------- |
| CNAME    | my-site | cname.vercel-dns.com |

Where `my-site` is the name of your sub-domain.