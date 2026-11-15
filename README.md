# LocalTab-Scores

[简体中文](README.zh-CN.md) · [LocalTab editor](https://github.com/phageous01/LocalTab)

Public MusicXML scores maintained by [phageous01](https://github.com/phageous01).
Each score has a stable landing page suitable for linking from video descriptions,
music platforms and profile pages. Download the MusicXML and open it in LocalTab
or another notation program that supports guitar/bass tablature.

## Score index

| Score | Instrument | Tuning (low → high) | Links |
| --- | --- | --- | --- |
| 【スパロボOGs】 悪を断つ剣 | Five-string bass | B0 E1 A1 D2 G2 | [Score page](scores/aku-wo-tatsu-tsurugi/README.md) · [MusicXML](scores/aku-wo-tatsu-tsurugi/score.musicxml) · [Raw file](https://raw.githubusercontent.com/phageous01/LocalTab-Scores/main/scores/aku-wo-tatsu-tsurugi/score.musicxml) |

## Download and use

1. Open the **Score page** above for details, then its MusicXML file.
2. On the GitHub file page, use **Download raw file**. If the raw link opens XML in
   your browser, save it as a `.musicxml` file instead of a web page.
3. In LocalTab, click **导入乐谱** (Import score) and select the downloaded file.
   MusicXML applications can differ in layout and technique rendering.

GitHub displays the XML source; it is not an interactive notation player. MP3
recordings and LocalTab synchronization metadata are not included in this public
repository. You can attach your own recordings and calibrate them in LocalTab.

## Linking and updates

Use the score's **landing-page URL** for external platforms. It remains useful as
the score is revised and can hold additional information later. The raw MusicXML
URL also stays stable as long as the folder and filename are kept unchanged.
Links under `main` always point to the current version; Git history records earlier
versions. These links are intended to replace external score links you maintain;
this repository does not itself edit profiles or links on other platforms.

To publish another score, add `scores/<stable-slug>/score.musicxml`, add a short
README in that folder, and update the English and Chinese indexes. To update an
existing score, export MusicXML from LocalTab and replace its file, then commit
and push. Saving in LocalTab does not automatically update this repository.

## Rights

The MIT license for the LocalTab software does not apply automatically to these
scores. Rights in the underlying compositions remain with their respective owners;
publication here does not grant a blanket license to the music or recordings.
Any score-specific license or permission will be stated on its score page.
