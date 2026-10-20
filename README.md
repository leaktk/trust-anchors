# trust-anchors

Repository for managing PKI references and trust anchors.

## Directory Structure

Each top-level folder in this repository represents a different group or scope.
The internal directory structure within those group folders is based on the
needs of the respective use-case.

### Person-Specific Directories

Folders may exist under `people/<user>` for individuals to add their own
public keys. The existence of a person-specific folder is not indicative of
their status as an active contributor.

If you are contributing a key, please note its location. In the event that a
private key is compromised, please submit a pull request to remove or rotate
it.

Expired keys may remain in the repo for historical purposes. It is the client's
responsibility to confirm that a key is not expired.

## Contributing

- All commits MUST be signed
- All updates MUST be submitted via pull requests.
- All pull requests must be approved by the appropriate CODEOWNERS

### Scope

Currently this repo is not accepting exernal contributions.
