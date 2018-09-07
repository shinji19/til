# upper_tab_off

```css
/* タブ非表示 */
.tabbrowser-tab[fadein]:not([pinned]) {
    display: none !important;
}

/* 新しいタブを開くボタンの非表示 */
.tabs-newtab-button {
    display:none !important;
}

/* サイドバーのヘッダも非表示にする場合はこちらも */
#sidebar-header {
  visibility: collapse;
}
```
