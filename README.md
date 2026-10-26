# WashSlot

WashSlot is a responsive, static laundry-booking demonstration for students in shared housing. It helps residents check machine availability, select a date and time, and see clear feedback during a sample booking flow.

## What is included

- Three selectable machines: Washer 1, Washer 2, and Dryer 1.
- Sample availability matching the project brief.
- A date-aware schedule that moves expired same-day slots into a collapsed **Show earlier slots** section.
- A visible next-available indicator and disabled booked slots.
- A booking form with required resident name and room number, processing feedback, and a clear demo confirmation.
- Responsive layouts, keyboard-accessible controls, visible focus indicators, and live status announcements.
- No framework, external API, build step, or third-party dependency.

## Important: demonstration only

WashSlot does not have a backend. The schedules are illustrative sample data and are not shared with other residents. Submitting the form displays a local demonstration confirmation only; it does not reserve a real machine or save personal details.

## Run locally

Open `index.html` directly in a modern browser. No installation or build command is needed. Alternatively, serve the folder with any static web server.

## Upload the project to GitHub

1. Create a new, empty repository on [GitHub](https://github.com/new).
2. In a terminal, open this project folder and run:

   ```sh
   git init
   git add index.html README.md WIREFRAME.md
   git commit -m "Create WashSlot laundry booking demo"
   git branch -M main
   git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
   git push -u origin main
   ```

3. Replace the example remote URL with the HTTPS URL for your repository. GitHub may ask you to authenticate.

## Deploy to Netlify

### Netlify Drop

1. Visit [Netlify Drop](https://app.netlify.com/drop) and sign in or create an account.
2. Drag the folder containing `index.html`, `README.md`, and `WIREFRAME.md` onto the deploy area.
3. Netlify publishes the static site and displays its public `netlify.app` URL. Use **Site configuration → Change site name** if you want a custom Netlify subdomain.

### Connect a GitHub repository

1. Push the project to GitHub using the instructions above.
2. In Netlify, choose **Add new site → Import an existing project**, connect GitHub, and select the repository.
3. Leave the build command empty and set the publish directory to `.` (the repository root).
4. Select **Deploy site**. Netlify will provide a public URL and automatically redeploy after future pushes.

## Deploy to GitHub Pages

1. Push the project to GitHub.
2. Open the repository's **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. GitHub Pages will show the published URL in the Pages settings when deployment finishes.
