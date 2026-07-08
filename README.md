# MapVR Atlas

VRChat ワールド **MapVR** の行き先カタログ (GitHub Pages 配信)。

- すべてのパノラマは [Poly Haven](https://polyhaven.com) の **CC0** 素材を 2048x1024 に変換したものです。撮影者クレジットは catalog.json と ワールド内プレートに表示されます。
- 追加・修正は MapVR 本体リポジトリの Tools/atlas/build_atlas.py で生成して push してください。

## live/ — ライブどこでもピンの高画質タイル

- Panoramax (https://panoramax.xyz) の 360° 写真を 4096x2048 に整え、左右 2048x2048 の2タイルで配信。
- 各写真のライセンスは CC-BY-SA 4.0 / etalab-2.0 等 (帰属表示つき再ホスト許諾)。
  撮影者・ソース・ライセンスはワールド内プレートに常時表示される (メタデータは MapVR Live Service /q が返す)。
- 生成: MapVR 本体リポジトリ Tools/live-service/build_live_hd.py
