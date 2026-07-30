# אתר אריה ברמץ — הוראות פריסה

## הרצה מקומית (לבדיקה)
1. התקינו Node.js (מ-nodejs.org) אם עדיין אין לכם.
2. בטרמינל, בתוך התיקייה הזו:
   npm install
   npm run dev
3. פתחו את הכתובת שתופיע (בדרך כלל http://localhost:5173)

## פריסה לאינטרנט (מומלץ: Vercel)
1. העלו את התיקייה הזו ל-GitHub (repo חדש).
2. היכנסו ל-vercel.com, התחברו עם GitHub.
3. "Add New Project" > בחרו את ה-repo > Deploy.
   Vercel מזהה אוטומטית שזה פרויקט Vite/React.
4. תוך כמה דקות תקבלו כתובת אינטרנט אמיתית (ואפשר לחבר דומיין משלכם בהמשך).

## חלופה מהירה בלי GitHub
1. npm install && npm run build (ייצור תיקיית dist)
2. גררו את תיקיית dist ל-netlify.com/drop
