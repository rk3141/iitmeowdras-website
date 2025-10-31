**IIT Meowdras - Campus Animal Welfare Website**

This is a simple, single-page website for the IIT Meowdras initiative, built to provide information, share pictures, and offer resources for animal welfare on the IIT Madras campus.

**Features**

- **Smooth-Scroll Navigation:** A sticky header with links to all major sections.
- **Mission Statement:** A place to describe the group's goals.
- **How to Help:** Clear, actionable steps for reporting animals and volunteering.
- **Resource Sections:**
  - **Helplines & Clinics:** A template for listing important contacts.
  - **Our Vets:** A template for recommended veterinarians.
- **Informational Content:**
  - **Common Misconceptions:** Debunking common myths about cats.
  - **Cat-Friendly Foods:** A simple "Safe vs. Toxic" guide.
- **Community Gallery:** A "Cats of IIT Madras" section to showcase campus residents.
- **Contact Footer:** Links for email and Instagram.

**Tech Stack**

- **HTML:** For all content and structure.
- **Tailwind CSS:** For all styling, loaded directly via a CDN (no build step required).
- **Google Fonts:** Using "Poppins" for headings and "Inter" for body text.

**How to Use**

This entire website is contained in a single iitmeowdras-website/index.html file.

- **No Installation:** There are no dependencies or build steps.
- **Run Locally:** Simply open the iitmeowdras-website/index.html file in any modern web browser to see the website.

**How to Customize**

All content can be edited directly in the iitmeowdras-website/index.html file.

- **Text Content:** Find the section you want to edit (e.g., &lt;div id="mission" ...&gt;) and change the text inside the &lt;p&gt; (paragraph) or &lt;h2&gt; (heading) tags.
- **Helplines & Vets:** The "Helplines" and "Our Vets" sections contain placeholder list items (&lt;li&gt;) and divs. You can copy and paste these templates to add new entries or edit the existing ones with real information.
- **Gallery Images:** In the &lt;div id="gallery" ...&gt; section, replace the <https://placehold.co/>... URLs in the &lt;img&gt; tags with your own image URLs.
- **Contact Links:** In the &lt;footer&gt; at the bottom of the file:
  - Update the href="#" in the "Official Instagram" link to your real Instagram URL.
  - The mailto:iitmeowdras@gmail.com link is already functional.
- **Styling & Colors:** The website's color scheme (theme-golden, theme-dark-text, etc.) and custom styles (like the content-card look) are defined in the &lt;style&gt; tag and the tailwind.config &lt;script&gt; tag in the &lt;head&gt; section. You can modify these values to change the site's appearance.
