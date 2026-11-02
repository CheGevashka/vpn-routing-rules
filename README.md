# Domestic routing rule-set

Public, non-secret domain suffix list for sing-box. These domains route directly only when a local profile places its protected-provider VPN rules first. This list contains no connection configuration or credentials. Some domains have subdomains used by multiple services; application dependencies are not exhaustively verified.

Files: `domestic-v1.json` is the source; `domestic-v1.srs` is compiled by sing-box 1.14.4. Source provenance and review remain in the local project. Treat changes as security-sensitive; retain previous releases for rollback.

The list contains 33 domain suffixes and one exact hostname. The exact host `api.licard.com` was observed in a LUKOIL app connection; no other `licard.com` hosts are included by that observation.

The exact hostname `yaratam.design` is included based on the site's own company offer. Subdomains are not included by this entry.
