📸 Responsive Image Grid Layout<br>
A sleek, modern image grid layout that adapts beautifully to any screen size!<br>

✨ Features
<p>Fluid Grid: 3 columns on desktop, 1 on mobile—no fuss.</p>
<p>Auto-Resizing: Images scale perfectly, keeping their aspect ratio with object-fit.</p>
<p>Clean Aesthetic: Minimalist design with subtle shadows and rounded corners.</p>
🚀 Quick Start
Clone the project:
bash
Copy code
git clone https://github.com/Hritik700/Image-Grid-Layout.git
Open index.html in your browser. Done!<br>
🔧 How It Works<br>
<p>Grid Layout: Powered by CSS Grid for flexible columns.</p>
<p>Responsive: Automatically adjusts for different screen sizes.</p>
<p>css</p>
<p>Copy code</p>
.container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    width: 60%;
    gap: 10px;
    box-shadow: 0px 0px 13px 3px rgba(0, 0, 0, .2);
}

@media (max-width: 768px) {
    .container {
        grid-template-columns: 1fr;
    }
}
📝 License
Licensed under MIT.

