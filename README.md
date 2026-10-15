# Dr.i 病毒生存戰

一款原創醫療主題的像素風自動攻擊生存網頁遊戲，參考 Vampire Survivors 類型的玩法。支援 GitHub Pages，無需伺服器或額外套件。

## 玩法

- 以 **WASD / 方向鍵** 移動，手機使用左下角虛擬搖桿。
- 醫療針劑會自動追蹤病毒，擊敗敵人後掉落經驗晶片。
- 累積經驗值升級，每次從三張卡片選擇強化。
- 技能包含免疫針劑、抗體護盾、治癒脈衝、細胞雷射、低溫抑制、免疫增幅與被動能力。
- 每 60 秒出現一隻巨型變異病毒。HP 歸零後結算。最佳存活時間保存在瀏覽器 localStorage。

## 在 GitHub Pages 免費部署

1. 新增公開 GitHub repository，例如 `dri-virus-survivor`。
2. 將本專案內 `index.html`、`style.css`、`game.js`、`assets/dri-pixel.png` 上傳至 repository 根目錄。
3. 進入 **Settings → Pages → Build and deployment**，選擇 **Deploy from a branch**，選擇 `main` 與 `/(root)`，儲存。
4. 等候 GitHub Pages 部署，開啟 `https://你的帳號.github.io/dri-virus-survivor/`。

## 本地測試

直接開啟 `index.html` 即可遊玩；或執行 `python -m http.server 8000` 再開啟 `http://localhost:8000`。

## 素材

Dr.i 主角採用使用者提供的圖像加工成低解析像素風 PNG。病毒、地圖、特效均由 Canvas 程式繪製。未使用 PokéSurvivor 的原始程式碼及美術資產。
