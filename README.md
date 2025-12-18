A custom CF template that uses AllowedDomains and Network Firewall

![Preview](https://github.com/mcgoosh/network_firewall/blob/main/networkfirewall.png)

##### Settings:

Edit the parameters in order to only allow specific domains.

```yaml
Parameters:
  AllowedDomains:
    Description: "comma separated list of allowed domains"
    Type: List<String>
    Default: ".aws.com, .a2z.com, .aws.dev, .aws.amazon.com, .amazon.com, .amazonaws.com, .awsstatic.com, .media-amazon.com, .ssl-images-amazon.com, .demdex.net, .omtrdc.net, .mktoresp.com"
```

**NOTE:**
I created this as a custom solution at work, which eventually was picked up and converted into a custom Vscode restricted egress solution.


