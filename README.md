# Vault-Session
1 Compare Authentication Methods </br>
1A Describe authentication methods</br>
https://www.vaultproject.io/docs/auth/index.html</br>
https://www.vaultproject.io/docs/concepts/auth.html</br>
1B Choose an authentication method based on use case</br>
https://www.vaultproject.io/docs/concepts/auth.html</br>
1C Differentiate human vs. system auth methods</br>
https://www.vaultproject.io/docs/concepts/auth.html</br>

 

2 Create Vault Policies</br>
2A Illustrate the value of Vault policy</br>
https://www.vaultproject.io/docs/concepts/policies.html</br>
2B Describe Vault policy syntax: path</br>
https://www.vaultproject.io/docs/concepts/policies.html#policy-syntax</br>
2C Describe Vault policy syntax: capabilities</br>
https://www.vaultproject.io/docs/concepts/policies.html#capabilities</br>
2D Craft a Vault policy based on requirements</br>
https://learn.hashicorp.com/vault/getting-started/policies#writing-the-policy</br>

 

3 Assess Vault Tokens</br>
3A Describe Vault token</br>
https://www.vaultproject.io/docs/concepts/tokens.html</br>
3B Differentiate between service and batch tokens. Choose one based on use-case</br>
https://www.vaultproject.io/docs/concepts/tokens.html#service-tokens</br>
https://www.vaultproject.io/docs/concepts/tokens.html#batch-tokens</br>
https://www.vaultproject.io/docs/concepts/tokens.html#token-type-comparison</br>
3C Describe root token uses and lifecycle</br>
https://www.vaultproject.io/docs/concepts/tokens.html#root-tokens</br>
3D Define token accessors</br>
https://www.vaultproject.io/docs/concepts/tokens.html#token-accessors</br>
3E Explain time-to-live</br>
https://www.vaultproject.io/docs/concepts/tokens.html#token-time-to-live-periodic-tokens-and-explicit-max-ttls</br>
3F Explain orphaned tokens</br>
https://www.vaultproject.io/docs/concepts/tokens.html#token-hierarchies-and-orphan-tokens</br>
3G Create tokens based on need</br>
https://learn.hashicorp.com/vault/identity-access-management/tokens#step-1-create-service-tokens-with-use-limit</br>

 

4 Manage Vault Leases</br>
4A Explain the purpose of a lease ID</br>
https://www.vaultproject.io/docs/concepts/lease.html#lease-ids</br>
4B Renew leases</br>
https://www.vaultproject.io/docs/commands/lease/renew.html</br>
4C Revoke leases</br>
https://www.vaultproject.io/docs/commands/lease/revoke.html</br>

 

5 Compare and Configure Vault Secrets Engines</br>
5A Choose a secret method based on use case</br>
5B Contrast dynamic secrets vs. static secrets and their use cases</br>
5C Define transit engine</br>
https://www.vaultproject.io/docs/secrets/transit/index.html</br>
5D Define secrets engines</br>
https://www.vaultproject.io/docs/secrets/index.html#secrets-engines</br>

 

6 Utilize Vault CLI</br>
6A Authenticate to Vault</br>
https://www.vaultproject.io/docs/commands/auth/index.html</br>
6B Configure authentication methods</br>
https://www.vaultproject.io/docs/commands/auth/enable.html</br>
https://www.vaultproject.io/docs/commands/auth/disable.html</br>
6C Configure Vault policies</br>
https://www.vaultproject.io/docs/commands/policy/index.html</br>
6D Access Vault secrets</br>
https://www.vaultproject.io/docs/commands/secrets/index.html</br>
6E Enable Secret engines</br>
https://www.vaultproject.io/docs/commands/secrets/enable.html</br>
6F Configure environment variables</br>
https://www.vaultproject.io/docs/commands/index.html#environment-variables</br>

 

7 Utilize Vault UI</br>
https://www.hashicorp.com/resources/vault-oss-ui-introduction</br>
https://vault-ui.io/</br>

7A Authenticate to Vault</br>
7B Configure authentication methods</br>
7C Configure Vault policies</br>
7D Access Vault secrets</br>
7E Enable Secret engines</br>

 

8 Be Aware of the Vault API</br>
8A Authenticate to Vault via Curl</br>
https://learn.hashicorp.com/vault/getting-started/apis</br>
8B Access Vault secrets via Curl</br>
https://www.vaultproject.io/api/overview.html#api-operations</br>

 

9 Explain Vault Architecture</br>
9A Describe the encryption of data stored by Vault</br>
https://www.vaultproject.io/docs/internals/security.html#external-threat-overview</br>
9B Describe cluster strategy</br>
https://www.vaultproject.io/docs/internals/high-availability.html</br>
9C Describe storage backends</br>
https://www.vaultproject.io/docs/configuration/storage/index.html</br>
9D Describe the Vault agent</br>
https://www.vaultproject.io/docs/agent/index.html</br>
9E Describe secrets caching</br>
https://www.vaultproject.io/docs/agent/caching/index.html</br>
9F Be aware of identities and groups</br>
https://www.vaultproject.io/docs/secrets/identity/index.html#identity-groups</br>
https://www.vaultproject.io/docs/secrets/identity/index.html#group-hierarchical-permissions</br>
https://www.vaultproject.io/docs/secrets/identity/index.html#external-vs-internal-groups</br>
9G Describe Shamir secret sharing and unsealing</br>
https://en.wikipedia.org/wiki/Shamir’s_Secret_Sharing</br>
9H Be aware of replication</br>
https://www.vaultproject.io/docs/internals/replication.html</br>
9I Describe seal/unseal</br>
https://www.vaultproject.io/docs/concepts/seal.html</br>
9J Explain response wrapping</br>
https://www.vaultproject.io/docs/concepts/response-wrapping.html</br>
9K Explain the value of short-lived, dynamically generated secrets</br>

 

10 Explain Encryption as a Service</br>
10A Configure transit secret engine</br>
https://www.vaultproject.io/docs/secrets/transit/index.html#setup</br>
10B Encrypt and decrypt secrets</br>
https://www.vaultproject.io/api/secret/transit/index.html#encrypt-data</br>
https://www.vaultproject.io/api/secret/transit/index.html#decrypt-data</br>
10C Rotate the encryption key</br>
https://www.vaultproject.io/api/secret/transit/index.html#rotate-key</br>
