## Vault Smart Contract Structure

The main components of the contract are:

- `Vault`: The core struct that holds the vault's data and logic.
- `VaultSignerCapability`: A struct that holds the capability to sign transactions on behalf of the vault.

Key functions include:

- `init_module`: Initializes the vault when the module is published.
- `deposit_tokens`: Allows permissioned addresses to deposit tokens.
- `allocate_tokens`: Allows the admin to allocate tokens to addresses.
- `claim_tokens`: Allows users to claim their allocated tokens.
- `withdraw_tokens`: Allows the admin to withdraw unallocated tokens.
- `change_admin`: Allows transferring the admin role to a new address.