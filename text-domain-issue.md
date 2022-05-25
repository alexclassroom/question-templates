# Text Domain 相關問題
多數的 WordPress 外掛，國際化程式碼會出現的問題，多半與 Text Domain 相關。
- This plugin's slug is `correct-text-domain`, but the current Text Domain is `wrong-text-domain`. Change the current Text Domain so it is equal to this plugin's slug and modify the text domain in all your source files. This change is **needed**, please refer to [this article](https://developer.wordpress.org/plugins/internationalization/how-to-internationalize-your-plugin/#text-domains).
- **"Requires at least"** (x.y) is below 4.6 so a `load_plugin_textdomain` is **needed**, please refer to [this article](https://developer.wordpress.org/plugins/internationalization/how-to-internationalize-your-plugin/#loading-text-domain).
