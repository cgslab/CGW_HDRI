# CGW_THETAZ1_VFXHDRIHandbook

## ABOUT

本リポジトリはCGWORLD.jp内で連載されている「THETA Z1を用いたVFX向け高品質HDRI作成ハンドブック」で利用する設定データ等を提供するリポジトリとなります。

基本的には弊社で制作したファイルとなりますが、以下特筆する内容については再配布及びライセンスを継承している内容になります。

再配布及び継承しているライセンスについての記載を確認して利用してください。

## 本リポジトリについて

以下ファイルは弊社で制作したファイルになります。

- darktable
  - THETA_Z1_HDRI_IDT_REC2020_v2.dtstyle
  - THETA_Z1_HDR2EXR.dtstyle
  - darktable_CGWHDRI_DevBatch.bat
  - darktable_CGWHDRI_DevBatch_Subdir.bat
- blender
  - HDRI_STmap_node_16bit.blend
  - HDRI_STmap_node_32bit.blend
  - Mult_HDRI_Projection.blend
- PTGui
  - ThetaZ1.pts
- Nuke関連
  - Nuke_HDRI_Merge/Nuke_HDRI_Merge_v2.nk
  - Nuke_HDRI_Merge/data/BIS_0000/0003/0004/0005.tif
  - Nuke_HDRI_Merge/data/STMapPTGui_A.exr
  - Nuke_HDRI_Merge/data/STMapPTGui_B.exr
  - Nuke_HDRI_Merge/data/STMapPTGui_Mask.exr
  - Nuke_HDRI_Merge/data/UVMap.exr
  - Nuke_HDRI_Merge/data/XH2_Plate_ACEScg.exr
- ColorChart
  - ColorChart/target_ricd_macbeth_xrite_ACES(cat02).exr
  - ColorChart/target_ricd_macbeth_xrite_ACEScg(cat02).exr
  - ColorChart/target_ricd_macbeth_xrite_lin-srgb(cat02).exr

これらのファイルはCC BY-SA 4.0で提供されています。

https://creativecommons.org/licenses/by-sa/4.0/

## ダウンロードについて

一部ファイルサイズの大きなバイナリファイルが含まれているためリリースページからのダウンロードをお願いします。

リポジトリのソースコードについては主に設定関連と25MB未満のバイナリファイルの管理のために存在しています。

[第3回：シンプルな現像・HDRI化フロー向け配布ファイル](https://github.com/cgslab/CGW_TEHTAZ1_VFXHDRIHandbook/releases/tag/CGW_HDRI_vol3)

[第4回：Nukeを用いた高品質フロー向け配布ファイル](https://github.com/cgslab/CGW_TEHTAZ1_VFXHDRIHandbook/releases/tag/CGW_HDRI_vol4)

[第6回：実践！HDRI撮影から合成まで](https://github.com/cgslab/CGW_TEHTAZ1_VFXHDRIHandbook/releases/tag/CGW_HDRI_vol6)

[第7回：第7回：HDRI TIPS集](https://github.com/cgslab/CGW_TEHTAZ1_VFXHDRIHandbook/releases/tag/CGW_HDRIvol7)

## 再配布ファイルについて

本リポジトリで提供するファイルには一部再配布ファイルが含まれています。

### TEHTA Z1 IDT(.icc)ファイルについて

本リポジトリ内で提供しているTHETA Z1向けのIDT(.icc)ファイルに関しては、株式会社ロゴスコープ 亀村氏が制作して、同社サイト上で提供している内容を再配布しています。

https://www.logoscope.co.jp/development/2020/05/idt-for-theta/?fbclid=IwAR0urHEfMt00RJWbHOW8iFtwBHTkWMvKXGdVoP3RaCBUcAGxZuU3Yx2jmn8

ファイル名：**THETA-Z1-normalized-5000k-adaptation-whiteInput-Device-Transform-developed-by-logoscope.icc**

### Elle Stone's ICC profileについて

本リポジトリ内で提供されているICCプロファイルは、Elle Stone's氏によってコンパイルされ、以下のリポジトリで提供されている内容を再配布しています。

https://github.com/ellelstone/elles_icc_profiles

elles_icc_profilesリポジトリの内容はCC BY-SA 3.0 DEEDで提供されています。

https://github.com/ellelstone/elles_icc_profiles/blob/master/LICENSE

https://creativecommons.org/licenses/by-sa/3.0/
