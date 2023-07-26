# Nostr Needlecast

Nostr Needlecast is a web service designed for the Nostr network that allows for the easy transfer of data from one Nostr account to another. This tool is especially useful for users who wish to migrate their data from one account to another, or for backup purposes.

## Features

- Retrieve all data associated with a specific Nostr account, including kind:0 (profile) and kind:1 (all posts) entities.
- Transfer the retrieved data to another Nostr account.

## Usage

1. **Retrieve Data:** Input the ID of the Nostr account that you wish to retrieve data from. The service will fetch all associated entities of kind:0 (profile) and kind:1 (posts).

2. **Transfer Data:** Input the ID of the destination Nostr account where you wish to transfer the data. The service will automatically transfer all the fetched data to the new account.

Please note that the transfer process will respect the original timestamps of the posts.

## Limitations

Currently, the service only supports the transfer of kind:0 (profile) and kind:1 (posts) entities. Future updates may include support for other kinds of entities.

## Contributing

If you have suggestions for how Nostr Needlecast could be improved, or want to report a bug, open an issue! We'd love to hear from you.

## License

MIT License. See `LICENSE` for more information.
