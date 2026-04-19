# BSInfo CDN

BSInfo CDN は、[BSInfo](https://bsinfox.com) の開発者によって管理・運営されている非公式のアセット CDN です。
この CDN は、[Brawl Stars API](https://developer.brawlstars.com/)、[BSInfo API](https://api.bsinfox.com/dev)、およびそれに関連するサービスで使用されるアセットの配信を目的としています。
ただし、すべてのサードパーティ API や実装との互換性を保証するものではありません。

## Usage

アセットはカテゴリごとのパスで配信されています。

形式:

`https://cdn.bsinfox.com/{category}/{id}`

実装に使用する際は、正しいアセット ID とパスを使用していることを確認してください。

例:

https://cdn.bsinfox.com/fame/alien.png

https://cdn.bsinfox.com/tier/39000000/16000000.png

https://cdn.bsinfox.com/brawlers/skins/29000000.png

より軽量な画像を配信したい場合は、対応している画像アセットについて、
拡張子を `.png` から `.webp` に変更して利用することもできます。

例:

https://cdn.bsinfox.com/fame/alien.webp

https://cdn.bsinfox.com/tier/39000000/16000000.webp

https://cdn.bsinfox.com/brawlers/skins/29000000.webp

元の `.png` URL も引き続き利用できます。

## Notes

この CDN は、Brawl Stars API、BSInfo API、および関連サービスとあわせて利用されることを想定しています。
そのため、一部のアセット、ID、ファイル名、パスは、互換性のために一定であることが前提となっている場合があります。

たとえば、fame 関連のデータは `https://api.bsinfox.com/fame` と対応しています。
BSInfo API に関する詳細は、`https://api.bsinfox.com/dev` をご確認ください。

また、ゲームのアップデート後に追加・更新されるアセットが、すぐに反映されない場合があります。

この CDN やそのアセットを利用する場合は、以下を含む Supercell のポリシーを必ず遵守してください。

- [Supercell Fan Content Policy](https://supercell.com/en/fan-content-policy/)
- [Supercell Terms of Service](https://supercell.com/en/terms-of-service/)

## Contributing

アセットの追加や更新に関する Pull Request は歓迎します。

PR を送る前に、以下を確認してください。

- アセットが正しいカテゴリに配置されていること
- ID が正しいこと
- ファイル名が正しいこと
- 対象のゲーム内リソースに対応していること

判断に迷う場合は、変更を送る前に Discord からご連絡ください。

## Credit

クレジット表記は必須ではありませんが、記載していただけると嬉しいです。
表記する場合は、BSInfo CDN やこのリポジトリなどへのリンクで十分です。

## Credits

**Kosuke** - brawler/skin
X: [@LMDKosuke](https://x.com/LMDKosuke)
Web: [brawlinsights.com](https://brawlinsights.com/)

## Contact

お問い合わせは、こちらの Discord サーバーからお願いします。
Discord: [https://discord.com/invite/85bQwpWUB2](https://discord.com/invite/85bQwpWUB2)

## Disclaimer

この CDN は個人により運営されており、アップデート後すぐに更新できない場合があります。
ここに掲載されているアセットは、ゲーム内ファイルから確認されたもの、または Supercell Fankit から収集したものです。

EN: This material is unofficial and is not endorsed by Supercell. For more information, see Supercell's Fan Content Policy: www.supercell.com/fan-content-policy.
JA: このコンテンツは非公式であり、Supercell による承認を受けていません。詳細については、Supercell のファンコンテンツポリシーをご確認ください: www.supercell.com/fan-content-policy.
