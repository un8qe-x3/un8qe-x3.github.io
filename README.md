<!DOCTYPE html>
<html lang="th">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>เว็บไซต์โรค HPV</title>

  <!-- Icons -->
  <link rel="apple-touch-icon" sizes="180x180" href="/apple-touch-icon.png">
  <link rel="icon" type="image/png" sizes="32x32" href="/favicon-32x32.png">
  <link rel="icon" type="image/png" sizes="16x16" href="/favicon-16x16.png">
  <link rel="manifest" href="/site.webmanifest">

  <!-- Google Fonts -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Athiti:wght@200;300;400;500;600;700&family=Sarabun:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800&family=Thasadith:ital,wght@0,400;0,700;1,400;1,700&display=swap" rel="stylesheet">
  <!-- CSS -->
  <style>
    html {
      font-family: 'KoHo', monospace;
      font-size: 18px;
      text-align: left;
      margin: 15px 5px;
      padding: 10px;
      background-color: #2f2f2f;
      color: #f0f0f0;
      letter-spacing: 0.07rem;
      line-height: 1.6rem;
    }

    a {
      color: hotpink;
      text-decoration: none;
      transition: color 0.3s;
    }

    a:hover {
      color: lightskyblue;
    }

    #header-title {
      font-size: 4rem !important;
      text-decoration: none !important;
      font-family: 'Thassadith' !important;
      float: left;
    }

    #namehead,
    #headlinks {
      border: 4px double white;
      margin: 5px;
      padding: 16px;
      border-radius: 12px;
      background-color: rgba(255, 255, 255, 0.05);
    }

    h1,
    h2,
    h3 {
      color: lightskyblue;
      margin-bottom: 0.5rem;
    }

    h1 {
      font-family: "Thasadith", serif;
    }

    h2 {
      font-family: "Athiti", serif;
      border-bottom: 2px solid hotpink;
      padding-bottom: 0.3rem;
      margin-top: 1.5rem;
    }

    h3 {
      font-family: "Athiti";
      color: #ffb6c1;
    }

    p {
			font-family:"Sarabun";
      text-indent: 2rem;
      margin: 0.5rem 0 1rem 0;
    }

    ul {
			font-family:"Sarabun";
      list-style-type: none;
      padding-left: 1rem;
    }

    li {
			font-family:"Sarabun";
      padding: 0.25rem 0;
    }

    li::before {
      content: "• ";
      color: hotpink;
      font-weight: bold;
    }

    .clearfix::after {
      content: "";
      clear: both;
      display: table;
    }

    footer {
			font-family:"Sarabun";
      margin-top: 2rem;
      font-size: 0.9rem;
      color: #ccc;
    }

    mark {
      background-color: hotpink;
      color: white;
      padding: 0 0.2rem;
      border-radius: 2px;
    }

    img.reload-icon {
      vertical-align: baseline;
      width: 1.7rem;
      height: auto;
      float: left;
      margin: 0 1rem;
      transition: transform 0.3s;
    }

    img.reload-icon:hover {
      transform: rotate(20deg);
    }

    nav ul li a {
			font-family:"Sarabun";
      font-size: 1.4rem;
    }

    nav ul li i {
			font-family:"Sarabun";
      font-style: italic;
      color: #aaa;
    }

    /* Responsive */
    @media (max-width: 600px) {
      #header-title {
        font-size: 3rem;
      }

      nav ul li a {
				font-family:"Sarabun";
        font-size: 1.2rem;
      }
    }
  </style>

  <!-- JS -->
  <script type="module">
    import { fairyDustCursor } from "https://unpkg.com/cursor-effects@latest/dist/esm.js";

    window.addEventListener("load", () => {
      new fairyDustCursor({
        colors: ["#ff0000", "#00ff00", "#0000ff", "#ffff00", "#ff00ff", "#00ffff"],
      });
    });
  </script>
</head>

<body>
  <header id="uhead">
    <div id="namehead" class="clearfix">
      <h1><span id="header-title">โรค HPV</span></h1>
      <a href="javascript: location.reload();" class="clearfix">
        <img src="reload.png" alt="Reload Page" class="reload-icon">
      </a>
    </div>
    <p>สวัสดีครับ เว็บไซต์นี้จะเป็นเว็บไซต์ที่ให้ความรู้เกี่ยวกับเชื้อ HPV อย่างละเอียด จัดทำโดยห้อง 204 เลขที่ 2,4,5,13,19,24,31,32,36</p>
    <hr>
  </header>

  <main>
		<h1>HPV คืออะไร</h2>
    <p>HPV (Human Papillomavirus) คือ ไวรัสชนิดหนึ่งที่สามารถติดเชื้อในมนุษย์ เป็นสาเหตุสำคัญของโรคติดต่อทางเพศสัมพันธ์ (STIs) และเกี่ยวข้องกับมะเร็งปากมดลูก มะเร็งอวัยวะเพศ และหูคอ</p>

    <h2>สาเหตุการติดเชื้อ HPV</h2>
    <ul>
      <li><b>การมีเพศสัมพันธ์</b>
        <ul>
          <li>ช่องคลอด</li>
          <li>ทวารหนัก (anal sex)</li>
          <li>ทางปาก (oral sex)</li>
          <li>จำนวนคู่เพศมาก</li>
        </ul>
      </li>
      <li><b>การสัมผัสทางผิวหนัง</b>
        <ul>
          <li>HPV ก่อหูดที่มือ เท้า หรือผิวหนังอื่น</li>
          <li>สัมผัสหูดหรือผิวหนังติดเชื้อโดยตรง</li>
          <li>เชื้ออาจอยู่บนผิวหนังที่ไม่มีอาการหูด</li>
        </ul>
      </li>
      <li><b>ภูมิคุ้มกันและปัจจัยร่างกาย</b>
        <ul>
          <li>ภูมิคุ้มกันต่ำ</li>
          <li>โรคเรื้อรังหรือรับยากดภูมิคุ้มกัน</li>
          <li>สูบบุหรี่</li>
        </ul>
      </li>
      <li><b>การแพร่เชื้อจากแม่สู่ลูก</b>
        <ul>
          <li>ช่วงคลอดผ่านช่องคลอด</li>
          <li>เด็กติดเชื้อทางเดินหายใจ</li>
          <li>พบได้น้อยแต่สำคัญ</li>
        </ul>
      </li>
      <li><b>พฤติกรรมและสิ่งแวดล้อม</b>
        <ul>
          <li>ไม่ใช้ถุงยางอนามัย</li>
          <li>เปลี่ยนคู่นอนบ่อย</li>
          <li>เริ่มมีเพศสัมพันธ์ตั้งแต่อายุน้อย</li>
          <li>ไม่ฉีดวัคซีน HPV</li>
        </ul>
      </li>
      <li><b>พันธุกรรมและชีววิทยา</b>
        <ul>
          <li>บางคนไวต่อการติดเชื้อมากกว่า</li>
          <li>เซลล์ปากมดลูกบางชนิดไวต่อการเกิดมะเร็ง</li>
        </ul>
      </li>
    </ul>

    <h2>อาการของ HPV</h2>
    <ul>
      <li>ส่วนใหญ่ไม่มีอาการชัดเจน</li>
      <li>หูด (Warts)
        <ul>
          <li>อวัยวะเพศชาย/หญิง: ก้อนนูนสีเนื้อหรือชมพู</li>
          <li>มือ/เท้า: หูดธรรมดาหรือฝ่าเท้า</li>
          <li>ปาก/ลิ้น: หูดชนิด oral warts</li>
        </ul>
      </li>
      <li>การเปลี่ยนแปลงที่อาจนำไปสู่มะเร็ง
        <ul>
          <li>ปากมดลูก: เลือดออกผิดปกติ, ปวดอุ้งเชิงกราน, การเปลี่ยนแปลงเซลล์จาก Pap smear</li>
          <li>อวัยวะเพศ/ทวารหนัก: แผลหรือก้อนไม่หาย, เลือดออกหรือปัสสาวะลำบาก</li>
        </ul>
      </li>
      <li>ทางเดินหายใจ (เด็ก)
        <ul>
          <li>หูดในลำคอหรือหลอดลม, เสียงแหบ, หายใจลำบาก</li>
        </ul>
      </li>
      <li>อาการอื่นๆ
        <ul>
          <li>คันหรือระคายเคืองบริเวณหูด</li>
          <li>อาจมีการติดเชื้อซ้ำ</li>
        </ul>
      </li>
    </ul>

    <h2>วิธีการรักษา HPV</h2>
    <ul>
      <li>รักษาหูด: ยาทา, Cryotherapy, เลเซอร์</li>
      <li>รักษามะเร็งจาก HPV: ผ่าตัด, เคมีบำบัด, ฉายแสง</li>
      <li>ติดตามผล: Pap smear, HPV DNA test</li>
    </ul>

    <h2>การป้องกัน HPV</h2>
    <ul>
      <li>วัคซีน HPV: ฉีดตั้งแต่อายุ 9–14 ปี (2 เข็ม), ผู้ใหญ่ 15 ปีขึ้นไป 3 เข็ม</li>
      <li>ใช้ถุงยางอนามัย: ลดความเสี่ยง แต่ไม่ป้องกัน 100%</li>
      <li>มีเพศสัมพันธ์อย่างปลอดภัย: ลดจำนวนคู่เพศ, มีความสัมพันธ์มั่นคง</li>
      <li>ตรวจคัดกรอง HPV / Pap smear ตามคำแนะนำแพทย์</li>
      <li>ดูแลภูมิคุ้มกันและสุขภาพ: รับประทานอาหารครบถ้วน, ออกกำลังกาย, หลีกเลี่ยงบุหรี่และแอลกอฮอล์มากเกินไป</li>
      <li>ป้องกันเด็กจากแม่สู่ลูก: ตรวจสุขภาพแม่ก่อนคลอด, ปรึกษาแพทย์ก่อนคลอด</li>
      <li>สร้างความรู้และตระหนัก: เข้าใจ HPV, เพศสัมพันธ์ปลอดภัย, ฉีดวัคซีน, ตรวจคัดกรอง</li>
    </ul>
    <div id="image-content">
      <div>
        <img src="https://www.bangpakok3.com/upload/เพศชายควรฉีดวัคซีน_HPV-01.jpg" alt="HPV Vaccine for Men"width=500 height=700>
        <small>เครดิตภาพ: bangpakok3.com</small>
      </div>
      <div>
        <img src="https://www.bangpakok3.com/upload/ไวรัสตัวร้าย_เสี่ยงโรคทั้งชายและหญิง-01.jpg" alt="HPV Risk"width=500 height=700>
        <small>เครดิตภาพ: bangpakok3.com</small>
      </div>
      <div>
        <img src="https://www.patrangsit.com/wp-content/uploads/2023/02/HPV-02-1024x1024.jpg" alt="HPV Virus"width=500 height=500>
        <small>เครดิตภาพ: patrangsit.com</small>
      </div>
      <div>
        <img src="https://www.pccms.ac.th/wp-content/uploads/2020/01/11266091642445.jpg" alt="HPV Diagram"width=500 height=700>
        <small>เครดิตภาพ: pccms.ac.th</small>
      </div>
    </div>
  </div>
</body>
  </main>
  <footer>
    (c) 2024 ห้อง 204 - All works licensed with <a href="https://creativecommons.org/licenses/by-sa/4.0/">CC BY-SA 4.0</a> unless otherwise stated.
  </footer>
</body>
</html>
