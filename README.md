original json on https://ip-ranges.amazonaws.com/ip-ranges.json
extracted the ips with the command " cat ip-ranges.json | jq -r '.prefixes[] | .ip_prefix' > amzndns.txt "
