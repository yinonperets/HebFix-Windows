# HebFix for Windows

**English** | [עברית](#עברית)

Typed in English by mistake while your keyboard was on the wrong layout? Select the text, press **Ctrl+Alt+H**, and it turns into Hebrew (`akuo` → `שלום`). If the selected text is already Hebrew, it's converted to English instead.

A tiny standalone program (built from an AutoHotkey script). No network access, nothing else to install.
macOS version: https://github.com/yinonperets/HebFix

## Install
1. Download [`HebFix.exe`](https://github.com/yinonperets/HebFix-Windows/releases/latest/download/HebFix.exe) and double-click it. A green **H** icon appears in the tray.
   Windows SmartScreen may warn because the file isn't code-signed: *More info → Run anyway*.
2. Select text → **Ctrl+Alt+H**.

Start with Windows: press `Win+R`, type `shell:startup`, and put a shortcut to `HebFix.exe` there.
Prefer to run the source? Install [AutoHotkey v2](https://www.autohotkey.com/) and open [`HebFix.ahk`](HebFix.ahk).

## Notes
- Standard Hebrew keyboard layout mapping. Shift/uppercase letters are not converted.
- It copies the selection, converts, and pastes; your clipboard is restored afterwards.

License: MIT

---

<div dir="rtl">

## עברית

<a id="עברית"></a>

כתבתם באנגלית בטעות כשהמקלדת הייתה על השפה הלא נכונה? מסמנים את הטקסט, לוחצים **Ctrl+Alt+H**, והוא הופך לעברית (`akuo` ← `שלום`). אם הטקסט המסומן כבר בעברית, הוא יומר לאנגלית.

תוכנה קטנה ועצמאית (נבנתה מסקריפט AutoHotkey). בלי גישה לרשת ובלי צורך להתקין שום דבר נוסף.
גרסת macOS: https://github.com/yinonperets/HebFix

### התקנה
1. מורידים את [`HebFix.exe`](https://github.com/yinonperets/HebFix-Windows/releases/latest/download/HebFix.exe) ופותחים בלחיצה כפולה. מופיע אייקון **H** ירוק במגש המערכת.
   Windows SmartScreen עלול להזהיר כי הקובץ לא חתום: *More info ← Run anyway*.
2. מסמנים טקסט ← **Ctrl+Alt+H**.

להפעלה עם Windows: `Win+R`, מקלידים `shell:startup`, ושמים שם קיצור ל-`HebFix.exe`.
מעדיפים להריץ את הקוד? מתקינים [AutoHotkey v2](https://www.autohotkey.com/) ופותחים את [`HebFix.ahk`](HebFix.ahk).

### הערות
- מיפוי של המקלדת העברית הרגילה. אותיות Shift/גדולות לא מומרות.
- הסקריפט מעתיק את הבחירה, ממיר ומדביק, ומחזיר את הלוח למצבו.

רישיון: MIT

</div>
