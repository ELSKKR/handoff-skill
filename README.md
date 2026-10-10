# handoff-skill

English: A Claude Code skill (`/handoff`) that writes a 7-field handoff note to `~/.claude/handoffs/` so you can `/clear` and start a fresh session without compacting. Pairs with the [cache-meter](https://github.com/ELSKKR/cache-meter) button, but works on its own. Traditional Chinese output for now; English is on the to-do list.

`/handoff`：把目前對話整理成 7 個欄位的交接內容，存到 `~/.claude/handoffs/`，讓你 `/clear` 後用它開始新對話（取代 compact）。

## 安裝

```bash
git clone https://github.com/ELSKKR/handoff-skill.git
mkdir -p ~/.claude/skills/handoff
cp handoff-skill/skills/handoff/SKILL.md ~/.claude/skills/handoff/SKILL.md
```

## 使用

- 手動：輸入 `/handoff`，看過交接檔後 `/clear`，再把內容貼進輸入框。
- 一鍵：裝 [cache-meter](https://github.com/ELSKKR/cache-meter)，按 handoff 按鈕。

## 授權

MIT
