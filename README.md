<h1>SmartStyle – AI-based Family Wardrobe and Outfit Recommendation System</h1>

<p>
SmartStyle is a full-stack web application that helps families manage their wardrobe digitally and generate smart outfit recommendations. The system supports OTP-based email authentication, family profile management, cloud-based wardrobe storage, solo and couple outfit generation, and lookbook saving. It is built using HTML, CSS, JavaScript, and Supabase.
</p>

<h2>Features</h2>
<ul>
  <li>OTP-based email authentication.</li>
  <li>Family wardrobe management.</li>
  <li>Add clothing items with images and metadata.</li>
  <li>Cloud storage for wardrobe images.</li>
  <li>Solo outfit generation.</li>
  <li>Couple outfit generation.</li>
  <li>Lookbook for saving preferred outfits.</li>
  <li>Migration from localStorage to cloud storage.</li>
  <li>Responsive and interactive frontend.</li>
</ul>

<h2>Tech Stack</h2>
<ul>
  <li><strong>Frontend:</strong> HTML, CSS, JavaScript</li>
  <li><strong>Backend:</strong> Supabase</li>
  <li><strong>Database:</strong> PostgreSQL</li>
  <li><strong>Authentication:</strong> Supabase Auth with OTP login</li>
  <li><strong>Storage:</strong> Supabase Storage</li>
</ul>

<h2>Project Structure</h2>
<pre>
SmartStyle/
├── assets/
├── screenshots/
├── src/
│   ├── css/
│   ├── js/
│   └── pages/
├── supabase/
│   └── config.js
├── index.html
└── README.md
</pre>

<h2>How It Works</h2>
<ol>
  <li>The user enters their email and verifies the OTP sent to their inbox.</li>
  <li>The user creates or accesses a family wardrobe profile.</li>
  <li>Clothing items are added with images and details.</li>
  <li>The system stores data in Supabase PostgreSQL and Supabase Storage.</li>
  <li>The outfit generator creates solo or couple outfit suggestions.</li>
  <li>Users can save preferred combinations in the lookbook.</li>
  <li>The system supports cloud synchronization across devices.</li>
</ol>

<h2>Database Tables</h2>
<ul>
  <li><code>families</code></li>
  <li><code>family_members</code></li>
  <li><code>wardrobe_items</code></li>
  <li><code>saved_outfits</code></li>
</ul>

<h2>Future Scope</h2>
<ul>
  <li>Advanced AI outfit recommendations.</li>
  <li>Mobile application version.</li>
  <li>Weather-based outfit suggestions.</li>
  <li>Virtual try-on integration.</li>
  <li>Improved recommendation logic.</li>
</ul>

<h2>Conclusion</h2>
<p>
SmartStyle provides a practical and user-friendly solution for family wardrobe management and outfit recommendation. By combining a simple frontend with cloud-based backend services, the project offers a secure, scalable, and modern digital wardrobe experience.
</p>
