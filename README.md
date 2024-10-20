# **AR Holeplate Manual 使用說明**

歡迎使用 MyApp，這是一款專為 [目標用戶群] 設計的 [功能描述] 應用。本文檔將為您提供詳細的安裝指南及使用說明，幫助您快速上手。

## **目錄**
1. [系統需求](#系統需求)
2. [安裝指南](#安裝指南)
   - [Android](#android)
   - [iOS](#ios)
3. [使用指南](#使用指南)

---

## **系統需求**

- **Android**：版本 11.0 或更高版本
- **iOS**：版本 12.0 或更高版本

## **安裝指南**

### **Android**

#### **手動安裝 APK**
1. 前往 [MyApp APK 下載頁面](https://example.com) 下載最新版本的 APK 文件。
2. 開啟 Android 設定，進入 **安全性**，啟用 **允許來自未知來源的應用**。
3. 打開已下載的 APK 文件，按照提示完成安裝。
4. 完成安裝後，您可以從應用列表中啟動 MyApp。

### **iOS**

#### **使用 Xcode 安裝**
如果您希望直接從 Xcode 將應用安裝到 iPhone，請按照以下步驟操作：

1. **準備工作：**
   - 確保已在 Mac 上安裝最新版本的 Xcode。
   - 使用 USB 線將 iPhone 連接到 Mac。
   - 將應用的 Xcode 專案檔案下載到本地。

2. **打開 Xcode 專案並配置 Apple ID：**
   - 進入已下載的專案目錄，找到並打開 `Unity-iPhone.xcodeproj` 文件，這將啟動 Xcode 並載入您的應用專案。
   - 在 Xcode 中，選擇左側的 **Project Navigator**。
   - 點擊藍色的專案檔案，選擇 **TARGETS** 下的應用名稱。
   - 切換到 **Signing & Capabilities** 分頁。
   - 在 **Team** 下拉選單中，選擇 **Add Account...**。
   - 輸入您的 Apple ID 和密碼，添加帳戶。
   - 添加後，選擇您的 Apple ID 所在的團隊。

   ![Xcode設定](https://github.com/justinhshz/ar-holeplate/blob/main/Images/xcode_project_signing.png)

3. **選擇設備並運行應用：**
   - 在 Xcode 工具欄中，點擊 **Scheme** 菜單，選擇您的 iPhone 設備。
   - 點擊 **Run** 按鈕，Xcode 將開始編譯應用。
   - 編譯完成後，應用會自動安裝到您的 iPhone 並啟動。
   - 如果在 iPhone 上看到信任提示，請手動在 iPhone 上啟動應用，並選擇 **信任**。


**注意：** 使用 Xcode 安裝應用到實際設備需要有效的 Apple 開發者帳戶。 此外，應用在設備上運行時可能會有時間限制，過期後需要重新安裝。 更多詳細信息，請參閱 Apple 的官方文檔。


## **使用指南**

1. **底部導覽列功能**（僅在選取物體後出現）：
   當使用者選取畫面中的物體時，底部的導覽列將顯示四個主要操作按鈕，從左到右依次是：
   - **開始/暫停播放動畫**：點擊這個按鈕可以控制物體動畫的播放或暫停。
   - **切換顯示Holeplate孔洞編號**：此按鈕可以切換是否顯示Holeplate上的孔洞編號。
   - **調整動畫速度**：點擊此按鈕會打開一個控制面板（panel），面板中有一個滑桿（slider），用來調整動畫的播放速度，範圍從 1 到 25。您可以拖動滑桿來設置所需的速度，設定完成後，動畫會根據您選擇的速度進行播放。
   - **刪除Holeplate物件**：點擊此按鈕可以刪除目前畫面中的Holeplate物件。

   ![底部導覽列](https://github.com/justinhshz/ar-holeplate/blob/main/Images/navigation_bar.png)

2. 如需幫助，請點擊右上角的「幫助」圖標查看詳細的使用說明。

---

感謝您使用 MyApp，期待您的反饋以幫助我們不斷改進！
