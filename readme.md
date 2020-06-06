### Simple repository that uses Terraform for generating PKI

#### Quick summary :

- Generates CA.
- Self-signs it.
- Generates three certs for the Vault servers.
- Signs the three generated certs with the CA.

The naming convention of the generated CA and certs matches the names of the certs in Vaultron.