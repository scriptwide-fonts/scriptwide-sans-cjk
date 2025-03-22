# Scriptwide Sans CJK

Pan-CJK font based on Source Han Sans and its derivatives

![FontForge](https://github.com/user-attachments/assets/f1d600e7-22b2-49cb-a39e-4fef99c6e883)

*You can already see how bad some of the glyphs are.*

This font is licensed under OFL.

## Description

Very low effort amalgamation of several Source Han Sans-derived fonts with some minute edits.

Note that glyphs are not hinted, so they will look sub-optimal in low resolutions. It is therefore recommended to use Source Han Sans for most CJK ideographs, and use Scriptwide Sans CJK as a fallback.

Glyphs do not necessarily follow any source, but most of them should follow either G-source, or J/K-source, as a result of combining G-source Plangothic, J-source Sukima Gothic, and K-source Gothic Nguyen.

I plan to convert all glyphs to `J→K→S→V→H→M→T→U→G→P` source, roughly in this fallback order where applicable, but this will probably never happen.

Scriptwide Sans CJK consists of 3 fonts to support as many CJK ideographs as possible.

## A note about an incorrect mapping

Though unifiable, in Plangothic, the glyph for `U+26979 𦥹` should be mapped to `U+22C93 𢲓`. This issue has never been addressed. This has already been fixed since `v1.002`.

Below are screenshots from <zi.tools>.

`U+22C93`: ![Screenshot 2025-01-18 214611](https://github.com/user-attachments/assets/a77f84eb-4d74-4d55-b328-9113b651c11f)

`U+26979`: ![Screenshot 2025-01-18 214556](https://github.com/user-attachments/assets/4698276e-ec09-43f4-859b-ed967e0be0b0)

## Coverage

Scriptwide Sans CJK now covers all CJK codepoints as well as Ext-J, as of Unicode 16.0. 

## Who asked?

1. Why does Scriptwide Sans CJK consist of 3 fonts?
  * Scriptwide Sans CJK-A covers the BMP, Scriptwide Sans CJK-B covers ext-B, and Scriptwide Sans CJK-C covers everything else. One font file can only support 65535 glyphs, therefore the font has to be split.
2. Why not 2 fonts?
  * Good question.
3. Why are some glyphs directly integrated from Lorchin Sans?
  * In previous versions of Scriptwide Sans CJK, some glyphs are directly integrated from Lorchin Sans due to my laziness. These should be updated to the glyphs in Plangothic, but some may not be updated properly due to oversights.
4. Why do some glyphs look terrible?
  * With the complexity of certain glyphs, they are sometimes directly drawn and bolded. If this is the case, you may directly use glyphs from Plangothic.
5. Can I expand on this font?
  * Yes, unless you violate the OFL. You probably won't if you're being reasonable.
6. What's the point of these questions?
  * I only know that, that's what Damascus, that's what the point of Damascus.
7. Did you remove the coverage images?
  * Yes, as they are redundant now.

## Disclaimer

This is not a professional font.

Glyphs do not necessarily follow any source.

I am not responsible for any damages caused by misusage of this font, or any misunderstandings that may arise when it is used in any scenario.

If there are inaccuracies in certain glyphs, please create an issue.

## License

As stated above, these fonts are licensed under the Open Font License. Details can be found in [the license file](LICENSE) or [the OFL website](https://openfontlicense.org/).

This portion is partially taken from [the Plangothic repository](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic_Project/blob/main/README.en.md#license) and from the OFL website.

Note that the below is not a substitute for legal advice. Please refer to the OFL text for more details.

### You may:

* Install these fonts.
* Modify these fonts.
* Redistribute these fonts, modified or not. (Please ensure the modified font is licensed under the OFL, and does not use any OFL reserved names. Scriptwide itself is NOT a reserved name, but to prevent confusion, I do not recommend using the "Scriptwide" name in any derivative fonts.)
* Use these fonts for all kinds of design work, both commercial and non-commercial, free of charge, without notice or acknowledgement. (Though, credit is still appreciated.)

### You may not:

* Sell any part of the font files on their own.
  * There are many online merchants (typically on Taobao) illegally reselling OFL fonts. No matter the original creator of the fonts, please refrain from purchasing from these resellers, as sellings fonts directly is a serious violation of the OFL.
* Republish these fonts under a non-OFL license.
  * 鼎〇 (〇猎), I'm talking about you...
* Use these fonts for illegal purposes or those that harm the normal operation of computer systems.
  * I mean, you have common sense... right? 

## Credits

| Font | Brief Description | Author(s) |
| --- | --- | --- |
| [Source Han Sans](https://github.com/adobe-fonts/source-han-sans) | Base font | Google, Adobe |
| [Plangothic](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic_Project) | Provided most glyphs | Fitzgerald Porthmouth Koenigsegg [et. al.](https://github.com/Fitzgerald-Porthmouth-Koenigsegg/Plangothic_Project?tab=readme-ov-file#%E8%B4%A1%E7%8C%AE%E8%80%85) |
| [Noto Unicode](https://github.com/MY1L/Unicode/tree/main/NotoUnicode) | Provided modifications of Plangothic glyphs | MY1L |
| [Gothic Nguyen](https://github.com/TKYKmori/Gothic-Nguyen) | Provided some Vietnamese Han Nom glyphs | TKYKmori, Han-Nom Revival Committee of Vietnam |
| [Sukima Gothic](https://oppekebekkanko.booth.pm/items/2117070) | Provided some Japanese kanji glyphs | (booth.pm) oppekebekkanko |
| [Yuu Gothic](https://github.com/Steve-Yuu/Yuu-Gothic) | Provided some glyphs | Steve-Yuu |
| [Chiron Hei HK](https://github.com/chiron-fonts/chiron-hei-hk) | Provided some glyphs | chiron-fonts |
| [WenYuan Gothic](https://github.com/takushun-wu/WenYuanFonts) | Provided some glyphs | takushun-wu |
| [Lorchin Sans](https://github.com/Losketch/LorchinSans) | Provided some components which were edited into the font; mostly deprecated | Losketch |
