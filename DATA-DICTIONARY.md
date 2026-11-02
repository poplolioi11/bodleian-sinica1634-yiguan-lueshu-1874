# 資料字典

book.json為固定主本。pages[]依24幅官方影像幀排列，page_id=fXX；unit ID開頭pXX為物理面，非原刻頁碼。p01是已明確排除的透印，不是漏頁。bbox=null，未提供逐字座標。

unit.layer為original-print或modern-description。後者僅p00-par01/p00-par02，內容是現代中文描述，非後加英文／鉛筆的逐字轉錄，亦不屬作者原文。role保留固定稿原層及附文角色。兩筆描述保留於本包，但不可當古籍正文使用。

methods.initial_metadata與physical_faces完整保存核定公開原稿欄位、notes與版面metadata；原units.order以陣列序表示。running_title、printed_page_number及other_paratext各投影一次，metadata不是第二份正文。source_reading_records含私路徑，整欄排除；公開projection與完整私檔不是同bytes。

uncertainties採單位內Unicode碼點0起半開區間[start,end)，surface=text[start:end]。extent=known僅表定位明確，不表讀法已核。候選不替換正文。uncertainties.json展平並帶fXX。

363個主單位及73個metadata投影單位，合計436單位、5566Unicode碼點、95筆疑讀；其中434個原印文字單位、5502碼點，另2筆共64碼點為後加標籤／鉛筆的現代描述。碼點數不是漢字數，疑讀數不是錯誤率。

source-pages.json全部24幀不因沒有正文而省略；required_layers及layer_states區分原印、現代描述及排除範圍。methods.bibliography把固定初錄及書目／非盲前置候選分開，不將候選寫入正文。
