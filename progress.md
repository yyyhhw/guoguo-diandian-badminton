Original prompt: 大幅升级「果果和点点羽毛球」：手感/打击感、合成音效+背景音乐(静音可保存)、画面与标题、HUD/菜单与刘海安全区、60fps、AI 难度曲线与回合节奏、胜负结算画面；保持纯静态网页、中文界面；旧版保留在 /v1/。

## v2 升级（2026-10-04）
- 旧版：/v1/index.html，git tag v1-before-upgrade
- 测试接口：window.render_game_to_text()、window.advanceTime(ms)、window.__game（forceSpecial/forcePlane/score 等）
- 测试脚本在工作区 /workspace/badminton/test_v2.py、test_juice.py（Playwright，桌面 1280x720 + 手机横屏 932x430 触屏，Chromium + WebKit）
- 存档 key：ggdd_badminton_settings / _muted / _records（localStorage）

## TODO / 建议
- 真机 iPhone 上确认音频（静音键开着时、来电打断后回到游戏）
- 可考虑：练习模式、更多角色皮肤、观众音量单独调节
