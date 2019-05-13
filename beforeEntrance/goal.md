# 暑期目標

## To-do list
1. 裝好 Netbrick
    1. 有問題可以問 Bangwen
    2. 需要實體機器的話可以向 Junlin 尋求幫助
2. 嘗試 Netbrick 上的範例，像是 packetGenerator --> NF --> PacketPrinter
3. 建立一個簡單的模組：一個收到封包後馬上轉送出去的模組
4. 用 rust 匹配封包 IP 訊息（類似簡易版的 route table）
5. Build a simple module: the module receives packets and then sends them out.

## Final goal
最終目標在於部屬部份自製的 NFs 到 Netbrick 上，目前有兩種實現方式

1. 把 C++ 程式轉譯成 Rust （比較不建議，因為 Rust 比 C++ 多了很多寫法上的限制）
2. 從 Rust 上呼叫嵌入的 C++ 程式，需要比較少的轉換成本，但是需要通過測試其可行性（在網路上找相關解答方向，或者問 Rust 開發者，隨後會與一位 Rust 開發者接觸）