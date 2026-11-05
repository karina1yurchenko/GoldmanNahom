# חתימות ועד הבית — סיום התקשרות מול "עובד"

דף לחתימת דיירים על הודעה והחלטת בעלי הדירות: סיום ההתקשרות מול חברת האחזקה "עובד שירות ואיכות בע"מ" והחלפת חברת האחזקה, מתחם נחום גולדמן 1–9 בבאר שבע.

הדף מאוחסן ב-GitHub Pages. כל חתימה נשמרת בקובץ `signatures.json` בריפו הזה, בלי מסד נתונים. מבוסס על [vaad-sign](https://github.com/Timur-Krasner-RI/vaad-sign).

## קישורים

- לדיירים (חתימה בלבד): https://karina1yurchenko.github.io/GoldmanNahom/
- לוועד (טבלת חתימות והורדת PDF): https://karina1yurchenko.github.io/GoldmanNahom/admin.html

דף הוועד לא מוסתר: הוא רק לא מקושר מדף הדיירים. החתימות עצמן נמצאות בקובץ `signatures.json` בריפו הציבורי.

## הפעלה חד-פעמית

אירוח חינמי ב-GitHub Pages עובד על ריפו ציבורי. השמות, מספרי הדירות והחתימות יהיו גלויים למי שיש לו את הקישור.

1. צרו [Fine-grained personal access token](https://github.com/settings/personal-access-tokens/new) רק לריפו הזה, עם הרשאת Contents: Read and write, ובלי הרשאות נוספות.
2. Settings → Secrets and variables → Actions → New repository secret. השם: `SIGN_TOKEN`.
3. Settings → Pages → Source: GitHub Actions.
4. Actions → Deploy site → Run workflow.

הטוקן נכתב לקובץ `config.js` רק באתר שמתפרסם, כדי שהדפדפן יוכל לשמור חתימה ישר לריפו. מי שפותח את קוד האתר יכול לשלוח או לערוך חתימות בריפו הזה בלבד.

## עדכון נוסח המסמך

הנוסח נמצא ב-`tools/document.html`. אחרי שינוי, מרנדרים מחדש את `page-1.png` (רוחב 1192 פיקסלים) ומעלים.
