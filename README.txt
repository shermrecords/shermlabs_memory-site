SHERMLABS MEMORY LANDING PAGE

1. Replace every instance of:
   https://YOUR-APP-URL.onrender.com
   with your real Render app URL.

2. Open index.html directly to preview locally.

3. To use with Flask, move:
   - index.html into templates/landing.html
   - style.css into static/landing.css
   - images/ into static/images/

   Then update the HTML paths to use Flask url_for(), for example:
   {{ url_for('static', filename='landing.css') }}
   {{ url_for('static', filename='images/mascot.png') }}

4. The GitHub link is already set to:
   https://github.com/shermrecords/shermlabs_memory
