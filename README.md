📺 Netflix Landing Page – Frontend Clone

A clean, responsive Netflix homepage clone built using HTML5, CSS3, and Bootstrap Icons.
This project focuses on UI replication, layout structuring, mobile responsiveness, and use of icon libraries.

🚀 Features

🎨 Fully responsive Netflix-style hero section

🌑 Dark theme overlay with background image

🅱️ Integrated Bootstrap Icons (via node_modules)

📩 Email input UI (non-functional placeholder)

🧭 Navigation bar with language dropdown + Sign In button

🖼️ Hero title, subtitle, and CTA button designed to match Netflix branding

🛠️ Tech Stack
Tech	Why Used
HTML5	Semantic structure of the page
CSS3	Styling, layout, Netflix UI feel
Bootstrap Icons	Icons like translate, chevron (loaded from node_modules)

The dependency is declared in package.json and installed as shown:

"dependencies": {
  "bootstrap-icons": "^1.13.1"
}


package

📦 Installation & Setup
1. Clone the repository
git clone <your-repo-link>
cd netflix

2. Install dependencies
npm install


This will install bootstrap-icons as seen in your lockfile.


package-lock

3. Run the project

Simply open the netflix.html file in your browser:

netflix.html


No build tool required.

📁 Project Structure
/project-root
│── netflix.html
│── package.json
│── package-lock.json
│── /node_modules
│── /images


netflix.html → UI layout, styling, and component structure

package.json → project metadata + dependencies

package-lock.json → exact locked dependency tree

🖥️ UI Overview

The landing page includes:

A background hero image

A black transparent shade overlay

Netflix brand title (red logo text)

Language dropdown (with translate icon)

Sign-in button

Main hero section:

"Unlimited movies, TV shows and more" heading

Pricing subtitle

Email input UI + Get Started button

Everything is styled inside an embedded <style> tag inside netflix.html.


netflix

✔️ Future Enhancements (Optional)

Add responsive breakpoints

Add functional email input using JS

Add footer and content sections

Convert to a React or Next.js project

Use external CSS instead of inline <style>

📜 License

This project is open-source under the ISC License (from your package.json).