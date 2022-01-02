# week 2: content-based recommendation

- 目的
  - 建立 content-based 的推薦系統
  
- 方法
  - 推薦清單
    - 使用 description 作為 item representation
    - 透過 BeautifulSoup 排除 HTML tags
    - 計算 descripition 的 tf-idf，並用 cosine similarity 計算相似度，取前 50 個物品
  - 推薦排序
    - 將推薦清單的物品依照評論數、平均評分排序，取 top 10 作為最終的推薦物品清單

- 結果
  - 0.0
