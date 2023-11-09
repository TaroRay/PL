0# 112-1 師大科技系程式語言  
  > 授課教師：蔡芸琤老師
# 基本資料  
  * 姓名：**張育瑞**  
  * 系級：**科技系碩士班三年級**
  * 學號：**61071031H**
# 課程筆記區
## Week1
 1.  [Markdownm語法說明](https://markdown.tw/)  
## Week2
 1.  [Pythonset用法](https://shengyu7697.github.io/python-set/)
 2.  變數  
    int   整數  罰款金額  
    float 浮點數 判賠比例  
    str   字串   法律條文  
    bool  布林值  True&False(成立&不成立)
## Week6
 1.  [資料正則化規則教學](http://perso.ens-lyon.fr/lise.vaudor/strings-et-expressions-regulieres/?fbclid=IwAR0IHvNKp43Qrfo0TqpolYPpMUfViSrCBDY8SmBveKm01yZ6PzHPxspVaNI)
 2.  [資料正則化線上練習](https://regexr.com/)
 3.  資料正則化regular expression適用於有規則可循的資料，才比較利於進行提取。
 4.  內碼表應用於正則化中非英語系之文字
 5.  線上練習內容轉入python的方法：在 text 放文本，pattern後加r。
## Week7 網路爬蟲
  1.  [網路爬蟲範例](https://blog.jiatool.com/series/python%E7%B6%B2%E8%B7%AF%E7%88%AC%E8%9F%B2%E5%AF%A6%E4%BE%8B/page/2/)  
  2.  Beautifulsoup爬蟲套件

## Week9 
  1. 使用套件需要確定輸入輸出之格式
  2. [APIs](https://www.youtube.com/watch?time_continue=1&v=GZvSYJDk-us&embeds_referring_euri=https%3A%2F%2Fwww.bing.com%2F&embeds_referring_origin=https%3A%2F%2Fwww.bing.com&source_ve_path=Mjg2NjY&feature=emb_logo) Application Programming Interface
  3. 邏輯思維：大任務解構成小任務
  4. 從開放式文本進行分詞表製作並完成文字雲：收錄文本在匯入網路試算表，chapGPT可寫"我現在有一段中文文本希望透過python完成分詞，接著讀取分詞頻率該如何進行"
  5. 由於jieba套件所需格式為str，可利用type()檢查文本資料結構形式，並詢問chatGPT如何將Panda轉成str形式。
  6. 清洗不需要分詞的方式：chatGPT：想要對文本中的標點符號做清洗，在Python該怎做？建議先進行清洗再做jieba，(中文標點符號全半形也需注意)，所以需要跟chatGPT說明：chatGPT建議用正則化。
  7. jieba & counter & wordcloud資料結構相同
  8. 程式排版也可能造成問題須留意
  9. 文字雲在colab可能會有中文字型支援不足之問題，可詢問chatGPT尋求字型下載之方法。  
  10. [WordCloud](https://github.com/amueller/word_cloud)，WordCloud 是一個用於生成文字雲的 Python 庫，它可以將一段文本轉換成文字雲圖片，並且支持多種字體、背景顏色、形狀等設置。  
[TextBlob](https://github.com/sloria/TextBlob) TextBlob 是一個用於自然語言處理的 Python 庫，它提供了多種文本處理工具，包括分詞、情感分析、詞性標註等功能。  
[Voyant Tools](https://github.com/sgsinclair/VoyantServer)Voyant Tools 是一個基於 Web 的文字分析工具，它提供了多種可視化工具，包括文字雲、關鍵詞提取、文本聚類等。  
[Textify](https://github.com/mrdbourke/textify)Textify 是一個用於生成 ASCII 藝術文字的 Python 庫，它可以將一段文本轉換成 ASCII 藝術文字，並且支持多種字體和顏色。  
[Termgraph](https://github.com/mkaz/termgraph)Termgraph 是一個用於在終端中繪製簡單圖表的 Python 庫，它支持繪製線圖、柱狀圖、堆積圖等多種圖表類型。  
[Glances](https://github.com/nicolargo/glances)Glances 是一個基於終端的系統監控工具，它可以顯示系統的 CPU、內存、網絡等資源使用情況，並且支持繪製簡單的圖表。  
[ConsolePlot](https://github.com/pascaln/ConsolePlot)，ConsolePlot 是一個用於在終端中繪製線圖的 Python 庫，它支持繪製多種線圖類型，包括折線圖、散點圖、條形圖、熱點圖等。  
  11. ner套件可以過濾國家名稱
## Week10
  1.LDA：資料分群  
  2.[LDA範例程式](https://nbviewer.org/github/pecu/LAT/blob/main/HW3/TextMining.ipynb#topic=0&lambda=0.67&term=)
# 課堂練習區
  1.  [Task1](https://github.com/TaroRay/PL/blob/main/Task1.ipynb)  
  2.  [Task3](https://colab.research.google.com/drive/17P_lXYfHzF-Qx0VSmAq7AlDgA90OG2G1#scrollTo=i3GNb_M5ko47)
# 作業連結區
  1.  [H.W1](https://colab.research.google.com/drive/1v8OO1qbb4BbCyVENj4zvrMgDNiUxL7oV?usp=sharing)
  2.  [H.W2](https://github.com/TaroRay/PL/blob/main/20231007_H_W2%20.ipynb)  
  3.  [H.W3](https://github.com/TaroRay/PL/blob/main/20231030H_W3.ipynb)  [csv](https://github.com/TaroRay/PL/blob/main/matching_titles.csv)  [雲端csv](https://drive.google.com/drive/folders/1uPYyFeVHfgzm-RlxQ5261LIz_D6i-Kan)  [json](https://github.com/TaroRay/PL/blob/main/matching_titles.json)  [雲端json](https://drive.google.com/drive/folders/1uPYyFeVHfgzm-RlxQ5261LIz_D6i-Kan)
  4.  [H.W4](https://medium.com/@61071031h/%E8%87%BA%E7%81%A3%E4%BA%BA%E5%B0%8D%E6%B2%96%E7%B9%A9%E6%97%85%E9%81%8A%E7%9A%84%E9%97%9C%E6%B3%A8-d128d49bb66b) [程式碼](https://github.com/TaroRay/PL/blob/main/H_W4_%E6%B2%96%E7%B9%A9%E7%88%AC%E8%9F%B2%E8%88%87%E6%AD%A3%E5%89%87%E5%8C%96%E8%88%87%E6%96%87%E5%AD%97%E9%9B%B2.ipynb)
  5.  [H.W5](https://medium.com/@61071031h/%E8%87%BA%E7%81%A3%E5%B0%8D%E6%96%BC%E6%B2%96%E7%B9%A9%E6%99%AF%E9%BB%9E%E9%97%9C%E6%B3%A8%E5%9C%B0%E5%9C%96%E7%86%B1%E9%BB%9E-e9c54485330c)
# 專題連結區
