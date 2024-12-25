# 3-Input-Simple-Rock-Paper-Scissors-Game-with-FPGA
這是基於 Verilog 設計的簡單猜拳遊戲，運行於 FPGA 開發板上。設計兩名輸入，進行三局兩勝的猜拳比賽，並通過 8x8 LED 矩陣顯示最終的勝利者結果。 

功能
兩人對戰： A 和 B 通過按鍵輸入猜拳結果。
三局兩勝：系統根據設計輸入計算結果，最終確定贏家。
結果顯示：
如果 A 獲勝，LED 矩陣顯示字母「A」。
如果 B 獲勝，LED 矩陣顯示字母「B」。
如果雙方平手，LED 矩陣不顯示任何內容。

硬體需求
FPGA 開發板
Quartus 
8x8 LED 矩陣
三個按鍵作為輸入裝置

使用說明
連接 LED 矩陣和按鍵至 FPGA 開發板。
使用 Quartus  將 Verilog 程式碼燒錄到 FPGA。
按下按鍵輸入猜拳結果。
查看 LED 矩陣顯示的勝利者結果。

