# CCNP Linkstate
Link-State

鏈結狀態路由協定包含 OSPF、IS-IS 等協定。

* 連結速度 (實際頻寬)

鏈結狀態路由協定是以連結速度為基礎的計算方式，用來定義從一段網路到另一段網路的距離。而更新資訊也只有 Topology 有異狀時，才會使用鏈結狀態的廣播（通告） LSA, Link-State Advertisement 。

* 路徑處理

1. 發現路徑, Discovery

2. 選擇路徑, Selection

3. 維護路徑, Maintanance

https://github.com/QueenieCplusplus/CCNP_IGRP/blob/master/README.md#觸發更新

* 定期更新

倘若無異常狀態促使觸發更新，則路由表會預設時間從半小時至兩小時自動更新。

* 預設距離值

https://github.com/QueenieCplusplus/CCNP_IGRP#預設的距離值


