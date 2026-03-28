# BSInfo CDN

BSInfo CDN is an unofficial asset CDN maintained by the developers of [BSInfo](https://bsinfox.com).
It is intended to support the delivery of assets used in projects related to the [Brawl Stars API](https://developer.brawlstars.com/), the [BSInfo API](https://api.bsinfox.com/dev), and similar services.
Compatibility with all third-party APIs or implementations is not guaranteed.

## Usage

Assets are served through category-based paths.

Format:

`https://cdn.bsinfox.com/{category}/{id}`

Please ensure that the correct asset IDs and paths are used in your implementation.

Examples:

https://cdn.bsinfox.com/fame/alien.png

https://cdn.bsinfox.com/tier/39000000/16000000.png

https://cdn.bsinfox.com/brawlers/skins/29000000.png

## Notes

This CDN is intended to be used together with the Brawl Stars API, the BSInfo API, and related services.
Because of that, some assets, IDs, filenames, or paths may be expected to remain consistent for compatibility reasons.

For example, fame-related data is linked to `https://api.bsinfox.com/fame`.
For more information about the BSInfo API, please see `https://api.bsinfox.com/dev`.

Please also note that newly added or updated assets may not always be available immediately after a game update.

When using this CDN or its assets, please make sure your use complies with Supercell's policies, including the following:

- [Supercell Fan Content Policy](https://supercell.com/en/fan-content-policy/)
- [Supercell Terms of Service](https://supercell.com/en/terms-of-service/)

## Contributing

Pull requests for adding or updating assets are welcome.

Before submitting a pull request, please verify that:

- the asset belongs to the correct category
- the ID is accurate
- the file naming is correct
- the asset corresponds to the intended resource

If you are unsure, please contact us through Discord before submitting changes.

## Credit

Credit is appreciated, but not required.
If you would like to provide credit, a link to BSInfo CDN, this repository, or something similar is enough.

## Credits

**Kosuke**
X: [@LMDKosuke](https://x.com/LMDKosuke)
Web: [brawlinsights.com](https://brawlinsights.com/)

## Contact

If you have any questions or requests, please contact us through this Discord server.
Discord: [https://discord.com/invite/85bQwpWUB2](https://discord.com/invite/85bQwpWUB2)

## Disclaimer

This CDN is operated independently and may not always be updated immediately after game updates.
The assets listed here are either collected from game files or sourced from the Supercell Fankit.

This material is unofficial and is not endorsed by Supercell. For more information, see Supercell's Fan Content Policy: www.supercell.com/fan-content-policy.