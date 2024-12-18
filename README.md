# cloudflare-ddns
To create a CloudFlare API token for your DNS zone go to https://dash.cloudflare.com/profile/api-tokens⁠ and follow these steps:

Click Create Token
Provide the token a name, for example, cloudflare-ddns
Grant the token the following permissions:
Zone - Zone Settings - Read
Zone - Zone - Read
Zone - DNS - Edit
Set the zone resources to:
Include - All zones
Complete the wizard and copy the generated token into the API_KEY variable for the container
