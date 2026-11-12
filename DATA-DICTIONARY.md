> 本文件原有的 v0.2.0 校讀與數量敘述保留為歷史；本版 v0.2.1 的局部非盲覆核、現行數量及未解狀態見 [METHODS.md](METHODS.md) 與 [TARGETED-CORRECTIONS.md](TARGETED-CORRECTIONS.md)。

# 資料字典

pages[]按24官方影像幀fXX；unit的pXX為物理面，非原刻頁碼。每單位固定ID/order及字串，bbox=null。layer=original-print共434；modern-description僅p00-par01/p00-par02共2筆，為現代中文描述，非後加英字／鉛筆逐字轉錄或作者原文。

24幅固定官方影像、42個目標物理面，436總單位、5918Unicode碼點；其中434原印文字單位／5854碼點及2現代描述／64碼點。相對v0.1.0有158個單位字串變動，95筆初錄疑讀各有處理，仍有69筆文字疑讀及40個已查看的來源折緣區。這些數量不是錯字數或準確率。

methods.physical_faces保存本版42面公開metadata；running_title、printed_page_number與other_paratext各投影一次，metadata不要再次拼接正文。

methods.initial_version_snapshot.public_book是v0.1.0已公開book.json的完整JSON值；其原文件SHA與snapshot語意相等分開，不表示新嵌入物件與原檔bytes一樣。該快照從未含source_reading_records私路徑。歷史quality僅指當時；current方法另見source_adjudication與adjudicated_metadata。

69疑讀按單位內Unicode碼點0起半開區間[start,end)，surface=text[start:end]；候選不替換正文。extent只指定位，不表讀法已證明。source_edge_regions另存原圖區、unknown extent及無推算字數，最小TEI以declared-methods快照承載，不另造body文字或gap字數。
