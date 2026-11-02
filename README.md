# 醫館略述三書（1874；Bodleian Sinica 1634） / yi guan lue shu san shu: Transcription dataset

## 摘要 / Abstract

《醫館略述三書》（yi guan lue shu san shu）是 1874 年的中文醫館文獻，館目刊地疑定為 [Foochow，福州]，列柯為樑（Dauphin William Osgood）校訂。原書包含施醫與傳教宗旨、醫館敘述、圖說、捐款名錄及收支表列，可供研究晚清醫療慈善、募款與機構出版。v0.2.0 依 Bodleian Sinica 1634 的 24 幅影像轉錄 42 個目標物理面，提供 TXT、JSON、TEI XML 與官方影像來源對應。文字為 AI 暫定轉錄，未經人類全文雙校或專家審定。

Yi guan lue shu san shu (醫館略述三書) is a Chinese hospital publication dated 1874, with [Foochow] supplied as its place of publication; the catalogue credits 柯為樑 with revision and identifies him as Dauphin William Osgood. Its statements of charitable and missionary purpose, hospital narratives, illustrations, donor lists and financial statements offer evidence for studying late Qing medical charity, fundraising and institutional publishing. Version 0.2.0 transcribes 42 target physical faces across 24 images of Bodleian Sinica 1634, providing TXT, JSON and TEI XML with references to the official source images. The text is a provisional AI transcription without human double collation or expert review.

原件與書目入口 / Source witness and catalogue:

- [館藏原件 / Source witness](https://digital.bodleian.ox.ac.uk/objects/019188cf-3884-48c4-a8ab-bfb98a65d12d/)
- [館藏書目 / Catalogue](https://east-asian.bodleian.ox.ac.uk/catalog/volume_1370)
- [IIIF manifest](https://iiif.bodleian.ox.ac.uk/iiif/manifest/019188cf-3884-48c4-a8ab-bfb98a65d12d.json)
- [館方固定書目 XML / Fixed official catalogue XML](https://github.com/bodleian/east-asian-mss/blob/c177d5a6db8585168b744d38a6bff02186d1968f/collections/chinese/Sinica%201634.xml)

**v0.2.0｜有界獨立觀察與非盲回圖修訂，保留未解。**

整理者：曲宸宇（Chu, Chen-Yu；GitHub：poplolioi11；[ORCID](https://orcid.org/0009-0003-9738-6914)）。本成果僅歷史文獻數位化與上架；未驗證歷史醫療主張、姓名、金額，未進行生物研究、實驗或現代操作指引整理。

24幅固定官方影像、42個目標物理面，436總單位、5918Unicode碼點；其中434原印文字單位／5854碼點及2現代描述／64碼點。相對v0.1.0有158個單位字串變動，95筆初錄疑讀各有處理，仍有69筆文字疑讀及40個已查看的來源折緣區。這些數量不是錯字數或準確率。

封面「醫館畧述三書」與館藏題名《醫館略述三書》保持三書；內題本版暫錄「醫館畧述二書」，二/三與館/舘疑義仍列，不以題名全域換字。責任題署「大美國醫士柯爲樑校訂」的角色是校訂，不擴稱作者或未核英文名。原印「同治十三年孟夏」及「耶穌降生一千八百七十四年」與Serica同治十二年[1874]並存紀年衝突，不換算精確公曆出版日；地點[Foochow]，出版者未核。

獨立觀察原登記11個Gemini全幅工作，10成功、e工作失敗；e僅p18–p21的32正文欄與14插入小字原生觀察經有界來源評估採用，其工作failed、正式audit incomplete狀態保留，未把缺漏或錯讀版心升格。另40面版心獨立補讀為Gemini b/c/d共30面與全新原生上下文10面；失敗margin-a沒有採用任何回答。另有原生p42段落補讀；p37小註最初裁錯區域，後換正區由全新Gemini補讀，原錯裁及原始輸出均保留。

三組非盲來源覆核後由主代理整合，範圍42目標物理面。錯掛頁、漏字、多處版心誤讀、方框占位及不受來源支持的裁緣正文context均可被拒絕；最終文字未回填冒充原始獨立觀察。另12整欄版心疑義由主代理補記，字串未變，已計入69筆。40來源折緣區的缺失筆畫範圍未知，不推算額外缺字數，亦不改稱未處理或空白。

p00印題簽及p02–p42為目標；p01鏡像透印不反轉重錄，p12只有版心仍納入。圖面p25、p29、p32的文字保存，圖形幾何未重建。

[TXT](book.txt)／[JSON](book.json)／[TEI](book.tei.xml)／[來源](source-pages.json)／[疑讀](uncertainties.json)／[訂正](CORRECTIONS.json)／[校讀範圍](COLLATION.md)／[訂正讀法](CORRECTIONS.md)／[資料字典](DATA-DICTIONARY.md)／[品質](QUALITY-AND-CONTRIBUTIONS.md)／[權利](RIGHTS.md)／[引用](CITATION.cff)。

獨立Gemini實際模型gemini-3.8-flash-high；原生實際模型、effort與計數未知，不當0。未做人類全文雙校、專家審定、同儕審查或準確率量測。工程、AI一致及DOI不證明讀字正確。 不公開掃描、裁片、專用程式、提示或完整私人工作紀錄，未提供由影像完整重跑的方法。

初錄[v0.1.0](https://doi.org/10.5281/zenodo.23876721)固定檔與tag保留，本包完整保存當時公開JSON值快照；歷史的「未套用獨立校讀」指初錄當時。系列DOI：https://doi.org/10.5281/zenodo.23876720。候選包不等於正式發布，以公開回讀為準。

## English summary

Version 0.2.0 compares independent observations with the frozen initial transcription, followed by non-blind source adjudication of 42 target physical faces. Of 11 full-frame Gemini jobs, ten succeeded and one failed; only bounded native body observations from that failed job were accepted, without upgrading its failed/incomplete audit status. Separate source-only margin, paragraph and corrected-crop supplements are disclosed. The dataset contains 434 original-print units plus two modern descriptions, with 158 changed unit strings, 69 text uncertainties and 40 reviewed source-edge regions of unknown missing-stroke extent. These are not error or accuracy estimates. No human double collation, expert review, peer review or measured accuracy is claimed.

Keywords: 醫館略述三書; 醫館略述二書; Sinica 1634; 醫學史; 醫療慈善史; 福州; 捐款名錄; 醫館收支; 題簽與內題; 篆書題頁; history of medicine; medical charity; medical missions history; Fuzhou; hospital reports; Chinese medical print culture; digital humanities; 1874; TEI XML.

預留版本 DOI（reserved；尚未確認正式發布）： https://doi.org/10.5281/zenodo.23878170
