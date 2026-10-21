# 素材來源與製作方式

## 角色與圖像參考
角色為《明日方舟》黍／Shu，原角色及官方素材權利歸相關權利人。
本專案為非官方、免費、非營利的同人桌寵模型，未宣稱取得官方認可。

主要表情與 Q 版造型參考，由使用者提供：
- 假日威龙陈阿颐，《超可爱! 【怀黍离】动态表情包》
  https://www.bilibili.com/video/BV12H4y1Y7cB/
- 作者頁：https://space.bilibili.com/36816755/
- 該影片簡介標註「根据官方表情包修改」，並提供其 GIF 於動態。
- 另有使用者提供的角色立繪截圖，以及外觀參考影片：
  https://www.bilibili.com/video/BV1pv421r7NT/

以上為參考來源紀錄，不代表官方或參考作者為本專案背書。
角色、官方素材與參考作品的相關權利仍屬各權利人。
包內未附上述影片、原始 GIF 或其背景音樂。

## AI 輔助製作
基準圖為依使用者參考圖，以 OpenAI image_gen 輔助重新繪製的鍵盤／滑鼠姿勢。
部分被遮住的身體、衣袖與前臂也經 AI 補繪；之後以程式整理透明分層、設定動作與遮擋。
v1.4.1 的最後修補直接恢復基準圖的袖口像素，未在該次修補重新生成圖像。
不宣稱本專案圖像為全手繪。完整基準圖與補繪提示詞見 模型 ZIP 的 IMAGE-PROMPTS.txt。

## 技術與開源參考
- BongoCat 執行程式：https://github.com/ayangweb/BongoCat
- 完整手勢 PNG／隱藏待機手的機制參考：
  https://github.com/A1ters/Theresa-standard-mode
  該專案的 README 標註其特蕾西婭立繪來源為 breadman面包人。
  breadman 並非在此被列為本專案黍圖像的作者。
- MOC3 序列化器：py-moc3，MIT，https://github.com/Ludentes/py-moc3
- 格式參考：Stretchy Studio，MIT，https://github.com/MangoLion/stretchystudio
- 對應 MIT 授權文字隨模型包保留；沒有把角色、美術或參考圖統一宣告為 MIT。
- 本專案沒有附帶第三方 Live2D SDK／Core 執行庫，也沒有 Cubism Editor CMO3 工程。
