# HebFix for Windows

**English** | [עברית](#עברית)

Typed in English by mistake while your keyboard was on the wrong layout? Select the text, press **Ctrl+Alt+H**, and it turns into Hebrew (`akuo` → `שלום`). If the selected text is already Hebrew, it's converted to English instead.

A tiny AutoHotkey script. No network access.
macOS version: https://github.com/yinonperets/HebFix

## Install
1. Install [AutoHotkey v2](https://www.autohotkey.com/).
2. Download [`HebFix.ahk`](HebFix.ahk) and double-click it. A green **H** icon appears in the tray.
3. Select text → **Ctrl+Alt+H**.

Start with Windows: press `Win+R`, type `shell:startup`, and put a shortcut to `HebFix.ahk` there.
Want an `.exe`? Right-click the script → *Compile Script*.

## Notes
- Standard Hebrew keyboard layout mapping. Shift/uppercase letters are not converted.
- It copies the selection, converts, and pastes; your clipboard is restored afterwards.

License: MIT

---

<div dir="rtl">

## עברית

<a id="עברית"></a>

כתבתם באנגלית בטעות כשהמקלדת הייתה על השפה הלא נכונה? מסמנים את הטקסט, לוחצים **Ctrl+Alt+H**, והוא הופך לעברית (`akuo` ← `שלום`). אם הטקסט המסומן כבר בעברית, הוא יומר לאנגלית.

סקריפט AutoHotkey קטן. בלי גישה לרשת.
גרסת macOS: https://github.com/yinonperets/HebFix

### התקנה
1. מתקינים [AutoHotkey v2](https://www.autohotkey.com/).
2. מורידים את [`HebFix.ahk`](HebFix.ahk) ופותחים בלחיצה כפולה. מופיע אייקון **H** ירוק במגש המערכת.
3. מסמנים טקסט ← **Ctrl+Alt+H**.

להפעלה עם Windows: `Win+R`, מקלידים `shell:startup`, ושמים שם קיצור ל-`HebFix.ahk`.
רוצים קובץ `.exe`? לחיצה ימנית על הסקריפט ← *Compile Script*.

### הערות
- מיפוי של המקלדת העברית הרגילה. אותיות Shift/גדולות לא מומרות.
- הסקריפט מעתיק את הבחירה, ממיר ומדביק, ומחזיר את הלוח למצבו.

רישיון: MIT

</div>
