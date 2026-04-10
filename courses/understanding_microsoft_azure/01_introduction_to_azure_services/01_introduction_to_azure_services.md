## Choosing the right storage option

### Locally Redundant Storage (LRS)

- Lowest cost option.
- Basic protection against server rack and drive failures.
- Recommended for non-critial scenarios.

### Geo Redundant Storage (GRS)

- Intermediate option. 
- Failover capabilities in a secondary region.
- Recommended for backup scenarios.

### Zone Redundant Storage (ZRS)

- Protection against datacenter-level failures.
- Recommended for high available scenarios.

### Geo Zone Redundant Storage (GZRS)
- Optimal data protection.
- Includes the offerings of both GRS and ZRS.
- Recommended for critical data scenarios.


#### Exercise:

When working in the cloud having data storage that is resilient, highly available and protected against failure is important. You are creating your first Azure storage account and need to choose a redundancy option that meets the following criteria:

- Supports backups through second region failover
- Provides highly available access that's protected against data-center level issues

Which of the following storage type best suits our requirements?

- [ ] Locally Redundant Storage (LRS)
- [ ] Geo Redundant Storage (GRS)
- [ ] Zone Redundant Storage (ZRS)
- [X] Geo Zone Redundant Storage (GZRS)

This option offers both GRS and ZRS which is recommended for critical data scenarios.