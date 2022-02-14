# 介紹

:::info信息

CosmWasm 是一個為 Cosmos生態系統打造的新的智能合約平台。 如果你還沒有聽說過，請[查看這個信息](https://blog.cosmos.network/announcing-the-launch-of-cosmwasm-cc426ab88e12)。這個文檔是為了讓希望嘗試或者集成這項技術的開發者能深入了解這項技術。特別是有Cosmos SDK开发经验的Go開發者，以及尋找一個區塊鏈平台的 Rust開發者。
:::

 # 如何使用 CosmWasm

 CosmWasm被設計成一個模塊並且可以集成到 Cosmos SDK。 這意味著任何人目前在使用Cosmos SDK創建區塊鏈都可以快速並且容易的將 CosmWasm 智能合約去支持他們當前的鏈， 不需要調整任何的邏輯。我們還提供了集成<code>gaiad</code>的CosmWasm樣本，叫做<code>wasmd</code>，所以你可以上線一個擁有智能合約的區塊鏈沒有任何難度，就像Cosmos Hub那樣安全的，註釋好測試好的工具。

 你會需要一個已經運行的區塊鏈去運行你的智能合約，並且通過一個app來使用。我們將會在後面的部分解釋如何去連結一個[測試網](https://docs.cosmwasm.com/docs/1.0/getting-started/setting-env#setting-up-environment)或者[創獎一個本地的“開發網”](https://docs.cosmwasm.com/docs/1.0/getting-started/setting-env#run-local-node-optional)。並且計劃儘快發佈一個測試網， 讓開發者可以容易的上載他們的智能合約，從而可以非常簡單的運行一個演示和其他人分享他們的智能合約。

 # 章節
* [開始](https://docs.cosmwasm.com/docs/1.0/getting-started/intro)部分讓你可以快速上手。 漸漸的讓你在本地區塊鏈上修改，發布，執行智能合約。這裡是一個理想的地方，讓你無需寫很多代碼就可以快速的了解整個系統的各個部分。
* [架構](https://docs.cosmwasm.com/docs/1.0/architecture/multichain)部分解釋了很多關於CosmWasm高水平的設計和03-架構。在你開始設計系統之前，很好的理解整個系統的模式和能力是非常好的。如果你希望馬上就開始寫代碼，你可以現在就跳過這部分，然後，再回來看看這部分等你想仔細了解架構設計。
* [學習](https://docs.cosmwasm.com/tutorials/simple-option/intro)部分很好的詮釋了如何從零到部署開始開發智能合約，通過一步一步的解釋，代碼塊，腳本以及更多。
  * [開發學院](https://docs.cosmwasm.com/dev-academy/intro)提供了CosmWasm智能合約和客戶端開發結構化學習材料。
* [Workshops](https://docs.cosmwasm.com/tutorials/videos-workshops)有很多由我們團隊錄製的事件和活動關於CosmWasm技術棧的演示和解釋。
* [生態系統](https://docs.cosmwasm.com/ecosystem/overview)提供了生態系統的概覽  
* [Plus](https://docs.cosmwasm.com/cw-plus/0.9.0/overview) 提供了可以直接使用的CosmWasm智能合約。
* [測試網](https://docs.cosmwasm.com/ecosystem/testnets/build-requirements) 是一個很好的起點，如果你在尋找一個已經上線的網絡去測試和檢驗你的智能合約，在一個穩定並且易用的測試環境。並且，“我們有足夠的驗證人加入測試網”，以前沒人說過😉

# 更進一步的學習
你可以深入研究我們的源碼然後開始寫你自己的智能合約：
* [一系列的智能合約例子](https://github.com/CosmWasm/cw-examples)你可以fork和實驗
* 學習[核心智能合約庫](https://docs.rs/cosmwasm-std/0.14.0/cosmwasm_std/)的Rustdoc
* 學習[存儲助手](https://docs.rs/cosmwasm-storage/0.14.0/cosmwasm_storage/)的Rustdoc 

還有許多高水平的文章在medium，解釋了我們的技術棧各種各樣的組件以及我們目前正在進行的。

非常感謝[Interchain Foundation](https://interchain.io/)為我們開發工作提供了大部分的資金讓CosmWasm成為可用的技術。
