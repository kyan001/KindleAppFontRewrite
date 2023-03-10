# KindleAppFontRewrite
Use HTTPS URL Rewrites to Costomize iOS/iPadOS Kindle APP Fonts.

## Files
* Shadowrocket Module: `kindle_app_font_rewrite.sgmodule`

### Fonts
* `STKaitiSC.ttf` <-> `TsangerJinKai01-W03.ttf`
* `STSongSC.ttf` <-> `TsangerMingKai-W03.ttf`
* `STYuanMedium-2018-02-16.ttf` <-> `TsangerYunHei-W03.ttf`


## Usage
1. Open iOS/iPadOS Kindle APP -> Manage Fonts -> Delete All Downloaded Fonts.
2. Open Shadowrocket -> Make sure CA Ceritification is installed for MITM HTTPS URL Rewrite.
3. Open Shadowrocket -> Config -> Module -> +: the Shadowrocket Module File -> Enable Module
4. Restart iOS/iPadOS Kindle APP -> Manage Fonts -> Download Fonts -> Use Downloaded Fonts.
