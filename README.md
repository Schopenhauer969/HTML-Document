🌐 មគ្គុទេសក៍ HTML ពេញលេញ (ចាប់ពីកម្រិតដំបូង → កម្រិតខ្ពស់)
HTML = HyperText Markup Language
👉 ជាភាសាសម្រាប់បង្កើតរចនាសម្ព័ន្ធគេហទំព័រ (Website Structure)
📄 1. រចនាសម្ព័ន្ធ HTML មូលដ្ឋាន
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Website</title>
</head>
<body>

  <h1>Hello World</h1>
  <p>គេហទំព័រដំបូងរបស់ខ្ញុំ</p>

</body>
</html>
🧠 ពន្យល់
<!DOCTYPE html> → ប្រកាសថាជា HTML5
<html> → ឯកសារមូលដ្ឋាន (root)
<head> → ព័ត៌មានមិនបង្ហាញលើអេក្រង់
<body> → ខ្លឹមសារដែលអ្នកមើលឃើញ
🧱 2. រចនាសម្ព័ន្ធ HTML
Tag	អត្ថន័យ
<html>	ឯកសារ HTML ទាំងមូល
<head>	ផ្នែកព័ត៌មាន (metadata)
<body>	ខ្លឹមសារនៅលើគេហទំព័រ
🏷️ 3. ចំណងជើង (Headings)
<h1>ចំណងជើងធំ</h1>
<h2>ចំណងជើងរង</h2>
<h3>ចំណងជើងតូច</h3>
🧠 ពន្យល់
<h1> ធំជាងគេ
<h6> តូចជាងគេ
👉 ប្រើសម្រាប់រៀបចំរចនាសម្ព័ន្ធ និង SEO
✍️ 4. ការរៀបចំអក្សរ (Text Formatting)
<b>អក្សរដិត</b>
<strong>អត្ថន័យសំខាន់</strong>

<i>អក្សរទ្រេត</i>
<em>ការសង្កត់អត្ថន័យ</em>

<u>គូសបន្ទាត់ក្រោម</u>
<mark>អក្សរបន្លិច</mark>

<small>អក្សរតូច</small>
<del>អក្សរលុប</del>
👉 ប្រើសម្រាប់បង្ហាញអត្ថន័យផ្សេងៗនៃអក្សរ
🔗 5. តំណភ្ជាប់ (Links)
<a href="https://google.com">Google</a>
🧠 ពន្យល់
href → តំណទៅកាន់ URL
👉 ប្រើសម្រាប់បើកគេហទំព័រ ឬផ្នែកផ្សេងៗ
🖼️ 6. រូបភាព (Images)
<img src="image.jpg" alt="រូបធម្មជាតិ" width="300">
🧠 ពន្យល់
src → ទីតាំងរូបភាព
alt → ពិពណ៌នារូបភាព (សំខាន់សម្រាប់ SEO និង accessibility)
📋 7. បញ្ជី (Lists)
បញ្ជីមិនមានលេខ
<ul>
  <li>HTML</li>
  <li>CSS</li>
</ul>
បញ្ជីមានលេខ
<ol>
  <li>ជំហានទី 1</li>
  <li>ជំហានទី 2</li>
</ol>
👉 <ul> = បញ្ជីចំណុច
👉 <ol> = បញ្ជីមានលំដាប់លេខ
📦 8. ប្រអប់ (Containers)
<div>ប្រអប់ Block</div>
<span>អក្សរ Inline</span>
🧠 ពន្យល់
div → block (ចុះបន្ទាត់ថ្មី)
span → inline (នៅជួរដដែល)
🧱 9. Semantic HTML (សំខាន់)
<header></header>
<nav></nav>
<main></main>
<section></section>
<article></article>
<aside></aside>
<footer></footer>
🧠 ពន្យល់
👉 ជួយឲ្យ browser និង Google យល់រចនាសម្ព័ន្ធ website
📥 10. Form (បញ្ចូលទិន្នន័យ)
<form>

  <input type="text">
  <input type="password">

  <button type="submit">ចូលប្រើ</button>

</form>
🧠 ពន្យល់
👉 ប្រើសម្រាប់ Login, Register, Contact form
☑️ 11. ប្រភេទ Input
<input type="text">
<input type="email">
<input type="password">
<input type="number">
<input type="date">
👉 ប្រភេទផ្សេងៗសម្រាប់ទិន្នន័យផ្សេងៗ
✅ 12. ការត្រួតពិនិត្យ Form
<input type="email" required minlength="5">
🧠 ពន្យល់
required → ត្រូវបំពេញ
minlength → អក្សរអប្បបរមា
📊 13. តារាង (Tables)
<table border="1">

  <tr>
    <th>ឈ្មោះ</th>
    <th>អាយុ</th>
  </tr>

  <tr>
    <td>John</td>
    <td>20</td>
  </tr>

</table>
👉 ប្រើសម្រាប់ទិន្នន័យជាជួរដេក និងជួរឈរ
🎵 14. សំឡេង និងវីដេអូ
<audio controls>
  <source src="music.mp3">
</audio>

<video controls width="400">
  <source src="video.mp4">
</video>
👉 បញ្ចូល media ទៅក្នុងគេហទំព័រ
🧩 15. Iframe
<iframe src="https://example.com"></iframe>
👉 បង្ហាញគេហទំព័រផ្សេងនៅក្នុង page
🎯 16. ប៊ូតុង (Buttons)
<button>ចុចទីនេះ</button>
👉 ប្រើសម្រាប់ធ្វើសកម្មភាព
🎨 17. ភ្ជាប់ CSS និង JS
<link rel="stylesheet" href="style.css">
<script src="script.js"></script>
👉 CSS = រចនាបថ
👉 JS = តក្កវិជ្ជា (Logic)
📱 18. Responsive Design
<meta name="viewport" content="width=device-width, initial-scale=1.0">
👉 ឲ្យគេហទំព័រសមរម្យលើទូរស័ព្ទ
🌍 19. SEO Meta Tags
<meta name="description" content="គេហទំព័ររបស់ខ្ញុំ">
<meta name="keywords" content="HTML,CSS">
<meta name="author" content="ឈ្មោះអ្នក">
👉 ជួយឲ្យ Google ស្វែងរកងាយ
♿ 20. Accessibility (សម្រាប់អ្នកពិការ)
<img src="cat.jpg" alt="ឆ្មាស្អាត">

<button aria-label="បិទ">X</button>
👉 ជួយ screen reader អានបាន
📂 21. File Path
<img src="./images/photo.jpg">
👉 relative path = ក្នុង project
👉 absolute path = ពេញលេញ
⚙️ 22. Data Attributes
<div data-id="101"></div>
👉 ប្រើសម្រាប់ផ្ទុក data សម្រាប់ JavaScript
🧲 23. Lazy Loading
<img src="image.jpg" loading="lazy">
👉 រូបភាព load ពេល scroll ដល់
🧪 24. Elements ពិសេស
Progress
<progress value="70" max="100"></progress>
Details
<details>
  <summary>បើកមើល</summary>
  ខ្លឹមសារលាក់
</details>
🌐 25. SVG (រូប vector)

👉 មិនបាត់គុណភាពពេល zoom
🔥 26. អនុសាសន៍ល្អបំផុត
✅ ប្រើ semantic HTML
✅ មាន alt text
✅ code ស្អាត
✅ រូបភាព optimize
✅ បំបែក CSS និង JS
✅ responsive design
📁 27. រចនាសម្ព័ន្ធ Project
project/
├── index.html
├── css/
├── js/
├── images/
└── assets/
👉 ធ្វើឲ្យ project មានរបៀបល្អ
🛠️ 28. Tools
VS Code
Live Server
Prettier
Chrome DevTools
Emmet
🚀 29. អ្វីដែលគួររៀនបន្ទាប់
CSS (Flexbox, Grid)
JavaScript
DOM
React
API
❤️ សរុប
👉 HTML = រចនាសម្ព័ន្ធ
👉 CSS = រចនាបថ
👉 JavaScript = តក្កវិជ្ជា និងសកម្មភាព
