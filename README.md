# Google Maps to 高德地圖 分享捷徑

## Introduction

高德地圖上的台灣道路與地標數量不如 Google Maps 與 Apple Maps 來的多，導致時常找不到導航的目標。這個捷徑用來將 Google Maps 上的地標分享給高德地圖，使其能直接導航到僅存在於 Google Maps 上的目的地。

> ⚠️ 由於作者較常使用 iOS，因此 Android 版本可能沒有經過嚴格測試。

## Pre-requirement
Actions (https://apps.apple.com/tw/app/actions/id1586435171)

## Methods

當前我們有三個方法將 Google Maps 上的地標分享給高德地圖：

### 1. 透過瀏覽器分享

1. 在「Google Maps App」中點擊分享
2. 選擇「在 Chrome 中開啟」
3. 點擊「Go back to web」
4. 在瀏覽器中分享到「高德地圖-瀏覽器分享」

### 2. 直接分享

1. 在「Google Maps App」中點擊分享
2. 選擇「高德地圖分享 - GetLoc」

### 3. 設定地點後用圖釘分享

1. 在「Google Maps App」中點擊分享
2. 選擇「高德地圖設定地點」
3. 長按地標旁邊直到出現「已放置圖釘」
4. 點擊分享
5. 選擇「高德地圖圖釘分享」

## Comparison

| 方法 | 準確度 | 操作難度 | 適用場景 |
|------|--------|----------|----------|
| 1 瀏覽器分享 | ⭐⭐⭐⭐⭐ | ⭐⭐ | 需要精確定位時 |
| 2 直接分享 | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | 大路、地址單純的地點 |
| 3 圖釘分享 | ⭐⭐⭐⭐ | ⭐⭐⭐ | 鄉下或偏僻地點 |

### 詳細說明

- **1 瀏覽器分享**：位置一定準確，但是操作稍微麻煩
- **2 直接分享**：較適用於大路上的地標、地址較單純的地點。若是鄉下或偏僻地點，位置可能錯誤，但操作簡單
- **3 圖釘分享**：設置圖釘後分享時，圖釘的位置準確，但有時候不容易點擊出圖釘

三者各有優缺點，可根據實際需求選擇使用。
註：有時也會因為分享遇到暫時性的網路問題，需要多試一次才能正常使用
當前 Android 僅支援透過瀏覽器分享，請自行研究。

---

## English Version

### Introduction

Amap (高德地圖) has fewer roads and landmarks in Taiwan compared to Google Maps and Apple Maps, making it difficult to find navigation targets. This shortcut is designed to share landmarks from Google Maps to Amap, enabling direct navigation to destinations that only exist on Google Maps.

> ⚠️ Since the author primarily uses iOS, the Android version may not have been thoroughly tested.

## Pre-requirement
Actions (https://apps.apple.com/tw/app/actions/id1586435171)

### Methods

Currently, we have three methods to share landmarks from Google Maps to Amap:

#### 1. Share via Browser

1. Tap "Share" in the Google Maps App
2. Choose "Open in Chrome"
3. Tap "Go back to web"
4. Share to "高德地圖-瀏覽器分享" (Amap - Browser Share) in the browser

#### 2. Direct Share

1. Tap "Share" in the Google Maps App
2. Choose "高德地圖分享 - GetLoc" (Amap Share - GetLoc)

#### 3. Set Location and Share via Pin

1. Tap "Share" in the Google Maps App
2. Choose "高德地圖設定地點" (Amap Set Location)
3. Long press next to the landmark until "Dropped pin" appears
4. Tap "Share"
5. Choose "高德地圖圖釘分享" (Amap Pin Share)

### Comparison

| Method | Accuracy | Difficulty | Use Case |
|--------|----------|------------|----------|
| 1 Browser Share | ⭐⭐⭐⭐⭐ | ⭐⭐ | When precise location is needed |
| 2 Direct Share | ⭐⭐⭐ | ⭐⭐⭐⭐⭐ | Major roads, simple addresses |
| 3 Pin Share | ⭐⭐⭐⭐ | ⭐⭐⭐ | Rural or remote areas |

#### Detailed Explanation

- **1 Browser Share**: Location is always accurate, but the process is slightly more complicated
- **2 Direct Share**: More suitable for landmarks on major roads and locations with simple addresses. For rural or remote areas, the location may be incorrect, but the operation is simple
- **3 Pin Share**: When sharing after setting a pin, the pin's location is accurate, but sometimes it's not easy to trigger the pin

Each method has its pros and cons, so you can choose based on your actual needs.
Note: Sometimes temporary network issues may occur during sharing, so you may need to try again for it to work properly.
Currently, Android only supports sharing via browser. Please research on your own.
