<div align="center">
<h1>📈 Sales Leadership Conference (SLC) 2026</h1>
<h3>Interactive Brochure Generator</h3>
<p><em>Designed for Leaders Who Must Win in Hard Markets</em></p>
</div><hr><p>This is a single-page, interactive HTML web application designed to generate dynamic, industry-specific brochures for the <strong>Sales Leadership Conference (SLC) 2026</strong> hosted by <strong>SalesRuby</strong>.</p><p>The application allows users to seamlessly switch between different industry verticals, viewing customized content, agendas, and value propositions, and includes a highly optimized "Print" feature to save or print pixel-perfect A4 PDF brochures.</p><h2>🚀 Key Features</h2><ul>
<li>
<strong>Dynamic Industry Switching:</strong> Users can toggle between four specific industries:
<ul>
<li>💎 Luxury, Real Estate & Automobile</li>
<li>⚙️ B2B, Technology & Oil and Gas</li>
<li>🛒 FMCG, Retail & Pharmaceuticals</li>
<li>🏦 Financial Services & Insurance</li>
</ul>
</li>

<li><strong>Customized Content:</strong> Automatically updates the target audience description, learning outcomes (bullet points), industry-specific paragraphs, and agenda schedules based on the selected tab.</li>
<li><strong>Print/PDF Optimization:</strong> Engineered with precise CSS print media queries. Clicking "Print Brochure" formats the document into perfect A4 dimensions (794px by 1123px), removes UI elements, and preserves background colors/gradients for a professional output.</li>
<li><strong>Automated Lead Generation:</strong> Features a built-in prompt that appears after 5 minutes of inactivity/browsing, asking users if they want to register or make an inquiry.</li>
<li><strong>WhatsApp Integration:</strong> The inquiry form automatically formats the user's Name, Email, and Location, redirecting them to a pre-filled WhatsApp chat with the SalesRuby team.</li>
<li><strong>Fully Responsive:</strong> Built with Tailwind CSS, ensuring the on-screen UI looks great on mobile phones, tablets, and desktop computers.</li>
</ul><h2>🛠️ Tech Stack</h2><ul>
<li><strong>HTML5:</strong> Semantic markup and structure.</li>
<li><strong>Tailwind CSS (via CDN):</strong> Rapid, utility-first styling and responsive design.</li>
<li><strong>Vanilla JavaScript:</strong> Logic for state management, tab switching, form handling, and timers.</li>
<li><strong>FontAwesome (via CDN):</strong> Icons for UI elements and bullets.</li>
</ul><h2>📂 File Structure</h2><p>The entire application is self-contained within a single file to make hosting and sharing as easy as possible:</p>
<ul>
<li><code>slc_brochures.html</code>: The main file containing all HTML, CSS, and JS logic.</li>
</ul><h2>💻 How to Use</h2><ol>
<li><strong>Run Locally:</strong> Simply double-click <code>slc_brochures.html</code> to open it in any modern web browser (Chrome, Safari, Edge, Firefox). No server setup is required.</li>

<li><strong>Generate a Brochure:</strong>
<ul>
<li>Click on one of the industry tabs at the top of the page.</li>
<li>Review the generated content.</li>
<li>Click the green <strong>"Print Brochure"</strong> button.</li>
<li>In the print dialog, select your physical printer, OR choose <strong>"Save as PDF"</strong> to download the professional brochure.</li>
</ul>
</li>

<li><strong>Submit an Inquiry:</strong> Wait for the prompt to appear, click "Make Inquiries", fill out the form, and click "Send to WhatsApp".</li>
</ol><h2>⚙️ Customization Guide</h2><p>If you need to edit the code directly, here are a few helpful tips:</p><h3>1. Changing the Pop-up Timer</h3>
<p>By default, the inquiry pop-up appears after 5 minutes. If you want to change this (e.g., for testing purposes), open <code>slc_brochures.html</code> in a text editor, scroll to the bottom JavaScript section, and find this code:</p><pre><code>setTimeout(() => {
// ... modal logic ...
}, 300000); // 300000 ms = 5 minutes
</code></pre><p><em>Change <code>300000</code> to <code>3000</code> if you want it to appear after just 3 seconds for testing.</em></p><h3>2. Updating Content or Agendas</h3>
<p>All text, bullet points, and agenda items are stored in a JavaScript array called <code>industries</code>. Simply locate this array in the <code>&lt;script&gt;</code> tag and update the text inside the quotes.</p><h3>3. Updating the WhatsApp Number</h3>
<p>Locate the <code>submitInquiry</code> function in the JavaScript. Find this line:</p><pre><code>const phoneNumber = '2348109006065';
</code></pre><p>Change this number to any valid WhatsApp number (always include the country code, without the <code>+</code> symbol).</p><hr><div align="center">
<p><small><strong>📝 License:</strong> Created for <strong>SalesRuby</strong>. All rights reserved.</small></p>
</div>
