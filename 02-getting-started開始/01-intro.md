---
sidebar_position: 1
---

# 你的第一個合約

準備好，我們現在就會有第一手的 CosmWasm經驗，通過：
* 開始我們自己的CosmWasm-enabled區塊鏈 (現在只有一個節點node)
* 修改一個已經存在的合約
* 部署它到我們的系統
* 通過cli來執行它

如果你更希望先探索，然後再進行實踐的人，你應該先去看看[架構](https://docs.cosmwasm.com/docs/1.0/architecture/multichain)。先閱讀架構的內容然後再看這部分內容。

在這部分我們暫時不會深入智能合約開發。你可以根據這裡的步驟去測試我們在測試網的智能合約而不需要沈溺在智能合約開發的細節中。我們演示配置環境，編輯，發布以及交互智能合約。
然後，我們會讓事情變得更有趣，我們將會展示如何修改一個契約合約例子，在[劫持契約教程](https://docs.cosmwasm.com/tutorials/hijack-escrow/intro)學習為它增加一個後門。
它會向原始的暴露一個一個相同的API，但是添加了一個隱藏的指令。這個還顯示了在你運行任何智能合約之前都應該驗證源碼的重要性。 <b>在你運行之前永遠先驗證源碼</b>

這是為熟悉命令行和使用Linux或者macOS的開發者設計的。 如果你理解基本的Rust和GO的會跟容易的學習，但是我們會引導你， 所以你不是必須要有任何已有經驗。在下一個教程[name service](https://docs.cosmwasm.com/tutorials/name-service/intro)中，會假設你已經有這些基本的知識。 並且，會向你展示從零到生產的所有開發流程。

# 章節

[安裝](https://docs.cosmwasm.com/docs/1.0/getting-started/installation)會告訴你如何去配置必須的CosmWasm軟體工具。
[配置環境](https://docs.cosmwasm.com/docs/1.0/getting-started/setting-env)會告訴妳如何去配置客戶端環境，並且和接口交互。
[下載和編寫合約](https://docs.cosmwasm.com/docs/1.0/getting-started/compile-contract)會展示下載和編寫智能合約代碼到wasm的字節碼。
[合約交互](https://docs.cosmwasm.com/docs/1.0/getting-started/interact-with-contract)會展示部署，初始化和執行智能合約。
[下一步](https://docs.cosmwasm.com/docs/1.0/getting-started/next-steps)是這個教程的最後一個部分。會概括這個章節並且給你未來的學習方向。

# 開發學院
[開發學院](https://docs.cosmwasm.com/dev-academy/intro)是一系列的模塊和一步一步的學習材料被設計成為每一個想要學習和開始區塊鏈，智能合約，DAOs以及更多概念的人提供一個快速開始的地方。
開發學院的內容可以被workshops, 大學課程或者在家使用。最終，你會對許多有趣的話題包括CosmWasm有一個很好的理解。 

# 視頻版本

為智能合約編寫源碼部分有系列的視頻，會引導你[學習源碼結構](https://vimeo.com/showcase/6671477)。







