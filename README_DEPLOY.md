# Campus Intern — Website deployment package

This folder contains the static website frontend:
- `index.html`
- `styles.css`
- `app.js`

## Preview on your computer
1. Extract this folder from the ZIP.
2. Keep all three files together.
3. Open `index.html` in Chrome.

Do not open the HTML file from inside the ZIP preview. Extract it first so the browser can load `styles.css` and `app.js`.

## Publish it online (static demo)
You can publish this folder using a static hosting service such as Netlify Drop:
1. Open https://app.netlify.com/drop
2. Sign in or create an account (follow the service's age and account rules; ask a parent/guardian if needed).
3. Drag the extracted `Campus_Intern_Website` folder onto the upload area.
4. Wait for the deployment to finish and open the website URL provided by the host.

## Important limitations
This is the frontend demonstration version. It stores demo information in the browser's local storage. It does not yet connect to the advanced Node.js/SQLite backend, and users on different devices will not share data. The role selector is for demonstration only, not secure authentication. Do not publish or enter real student personal information in this demo.

The advanced backend is in the separate `Campus_Internship_Management_System_Advanced.zip` project package. A real multi-user deployment requires connecting this frontend to a hosted backend and managed database, configuring HTTPS and secure secrets, and testing all role permissions before launch.

Project team registration numbers: 12623720 and 12621897. Registration 12622260 is excluded as confirmed. No team name was provided in the allocation sheet.
