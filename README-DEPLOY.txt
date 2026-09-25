NEW PORTFOLIO — GITHUB PAGES DEPLOYMENT

This is a single-file portfolio. The CSS and JavaScript are embedded inside index.html,
so you do not need a separate style.css. Keep profile.jpeg in the same folder.
If profile.jpeg is absent, the page will display a TB fallback.

BEFORE PUBLISHING:
1. Add your current resume PDF to this folder and name it resume.pdf.
2. Open index.html in Notepad or VS Code.
3. Search for "Add project URL" and replace the href URLs for Coca-Cola, Puma,
   and Salesperson Call Analytics with the actual repository URLs.
4. Verify the contact details, CGPA, education, and certificate titles.

PUBLISH ON GITHUB:
1. Open your existing portfolio repository on github.com.
2. Click Add file > Upload files.
3. Upload index.html, profile.jpeg, and resume.pdf into the repository's publishing
   root (usually the main branch root). If prompted, replace the existing index.html.
4. Scroll down, enter commit message "Publish new portfolio", and click Commit changes.
5. In Settings > Pages, make sure Pages publishes from the branch and folder where
   you uploaded the files (usually main / root).
6. Wait a few minutes and refresh your published site with Ctrl+F5.

You do not need style.css for this new single-file version.
