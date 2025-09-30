# My New Project
هذا أول مشروع ليا في GitHub ✨
<!DOCTYPE html>
<html lang="ar">
<head>
  <meta charset="UTF-8">
  <title>موقعي الأول</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <h1>🎉 أهلا بيكم في موقعي الأول 🎉</h1>
  <img src="profile.jpg" alt="صورة شخصية" class="profile">
  <p>هذا الموقع معمول بــ GitHub Pages 🚀</p>
  <button onclick="alert('مرحبا بيك 👋')">إضغط هنا</button>
</body>
</html>
<!DOCTYPE html>
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <title>تجربة HTML مع CSS</title>
    <style>
        body {
            font-family: Tahoma, Arial, sans-serif;
            direction: rtl;
            margin: 20px;
            background: #f4f4f9;
            color: #333;
        }
        h1, h2, h3, h4 {
            color: #2c3e50;
        }
        a {
            color: #2980b9;
            text-decoration: none;
        }
        a:hover {
            text-decoration: underline;
        }
        img {
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.2);
        }
        table {
            border-collapse: collapse;
            width: 50%;
            margin: 10px 0;
        }
        table, th, td {
            border: 1px solid #555;
            padding: 8px;
            text-align: center;
        }
        th {
            background: #3498db;
            color: white;
        }
        tr:nth-child(even) {
            background: #ecf0f1;
        }
        form {
            background: #fff;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            width: 300px;
        }
        input, textarea, select, button {
            margin: 8px 0;
            padding: 8px;
            width: 100%;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        button {
            background: #27ae60;
            color: white;
            border: none;
            cursor: pointer;
        }
        button:hover {
            background: #219150;
        }
        header, nav, main, aside, footer {
            margin: 15px 0;
            padding: 10px;
            border-radius: 8px;
        }
        header {
            background: #2ecc71;
            color: white;
        }
        nav {
            background: #34495e;
            color: white;
        }
        nav a {
            color: white;
            margin: 0 10px;
        }
        nav a:hover {
            color: #f1c40f;
        }
        main {
            background: #fff;
        }
        aside {
            background: #bdc3c7;
        }
        footer {
            background: #2c3e50;
            color: white;
            text-align: center;
        }
    </style>
</head>
<body>

    <header>
        <h1>مثال HTML مع CSS</h1>
    </header>

    <nav>
        <a href="#">الرئيسية</a> |
        <a href="#">عن الموقع</a> |
        <a href="#">تواصل معنا</a>
    </nav>

    <main>
        <h2>العناوين والنصوص</h2>
        <p>هذه فقرة فيها <strong>نص غامق</strong> و <em>نص مائل</em>.</p>

        <h2>روابط وصور</h2>
        <a href="https://www.google.com" target="_blank">اذهب إلى جوجل</a><br><br>
        <img src="https://via.placeholder.com/200" alt="صورة تجريبية">

        <h2>القوائم</h2>
        <ul>
            <li>عنصر 1</li>
            <li>عنصر 2</li>
            <li>عنصر 3</li>
        </ul>

        <ol>
            <li>الأول</li>
            <li>الثاني</li>
            <li>الثالث</li>
        </ol>

        <h2>الجدول</h2>
        <table>
            <tr>
                <th>الاسم</th>
                <th>العمر</th>
            </tr>
            <tr>
                <td>سليم</td>
                <td>20</td>
            </tr>
            <tr>
                <td>ليلى</td>
                <td>22</td>
            </tr>
        </table>

        <h2>النموذج</h2>
        <form>
            <label>الاسم:</label>
            <input type="text" name="name">
            <label>كلمة المرور:</label>
            <input type="password" name="pass">
            <label><input type="checkbox"> أوافق على الشروط</label><br>
            <label>الجنس:</label>
            <input type="radio" name="gender" value="ذكر"> ذكر
            <input type="radio" name="gender" value="أنثى"> أنثى
            <textarea rows="4" placeholder="أدخل ملاحظاتك..."></textarea>
            <select>
                <option>الجزائر</option>
                <option>تونس</option>
                <option>المغرب</option>
            </select>
            <button type="submit">إرسال</button>
        </form>

        <h2>وسائط</h2>
        <audio controls>
            <source src="audio.mp3" type="audio/mpeg">
        </audio>
        <br><br>
        <video width="300" controls>
            <source src="video.mp4" type="video/mp4">
        </video>
    </main>

    <aside>
        <p>هذا قسم جانبي (Aside)</p>
    </aside>

    <footer>
        <p>© 2025 جميع الحقوق محفوظة</p>
    </footer>

</body>
</html>