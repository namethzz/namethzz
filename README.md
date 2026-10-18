<p>
  <picture>
    <source media="(max-width: 600px)" srcset="./nameth-header-mobile.svg">
    <img src="./nameth-header.svg" width="100%" alt="Nameth Wongmongkol (ณเมธ วงค์มงคล): Data and AI engineering, full-stack">
  </picture>
</p>

<p align="center">
  <a href="https://namethzz.github.io/nameth-portfolio/">
    <img src="https://img.shields.io/badge/Portfolio-F2A93B?style=for-the-badge&logo=googlechrome&logoColor=14120F" alt="Portfolio">
  </a>
  &nbsp;
  <a href="https://github.com/namethzz?tab=repositories">
    <img src="https://img.shields.io/badge/All_projects-14120F?style=for-the-badge&logo=github&logoColor=F2A93B" alt="All projects">
  </a>
  &nbsp;
  <a href="mailto:nameth.won@spumail.net">
    <img src="https://img.shields.io/badge/Email-14120F?style=for-the-badge&logo=gmail&logoColor=F2A93B" alt="Email">
  </a>
</p>

## About / เกี่ยวกับผม

**TH** ผมชื่อ **ณเมธ วงค์มงคล** เรียนวิทยาการคอมพิวเตอร์ที่มหาวิทยาลัยศรีปทุม (GPAX 3.79) ผมออกแบบหน้าเว็บของทุกโปรเจกต์เอง โดยเลือก component จาก shadcn/ui และ 21st.dev มาจัดเป็น layout ของผม บางงานผมวาดหน้าจอใน Figma ก่อน เช่น KickHub จากนั้นผมสร้างต่อจนครบทั้งหน้าบ้าน หลังบ้าน และข้อมูล ทุกงานด้านล่างมีเว็บที่ deploy อยู่ กดเข้าไปลองได้

**EN** I'm **Nameth Wongmongkol**, a Computer Science student at Sripatum University (GPAX 3.79). I design every project's interface myself. I pick components from shadcn/ui and 21st.dev and arrange them into my own layouts, and for some projects, like KickHub, I draw the screens in Figma first. Then I build the frontend, backend, and data behind them. Each project below has a live site you can open.

<p align="center">
  <sub>Looking for internships in / สนใจฝึกงานสาย</sub>
  <br>
  <strong>Data Engineer · AI Engineer · Data Scientist · Full-Stack Developer</strong>
</p>

## How I work / วิธีทำงานของผม

- **Design the screens before writing code.** I plan the user flow and layout first, in Figma or with ready-made components, so I know what each page has to show.<br>
  **ออกแบบหน้าจอก่อนเขียนโค้ด** ผมวาง flow ของผู้ใช้และ layout ก่อน ใน Figma หรือด้วย component สำเร็จรูป จะได้รู้ว่าแต่ละหน้าต้องแสดงอะไร
- **Check the data before trusting it.** Some CSV files in the crop chatbot sat in the wrong province folder, so I read the province from the file name and use the folder only as a fallback.<br>
  **ตรวจข้อมูลก่อนเชื่อ** ไฟล์ CSV บางไฟล์ของแชตบอตพืชอยู่ผิดโฟลเดอร์จังหวัด ผมจึงอ่านจังหวัดจากชื่อไฟล์ก่อน แล้วใช้ชื่อโฟลเดอร์เป็นตัวสำรอง
- **Tell users what isn't real yet.** THAI TAY puts a "demo data" tag on every price, estimate, and shared link until the forecast model is ready.<br>
  **บอกผู้ใช้ว่าอะไรยังไม่จริง** THAI TAY ติดป้าย "ข้อมูลตัวอย่าง" บนทุกราคา ใบประมาณ และลิงก์ที่ส่งต่อ จนกว่าโมเดลพยากรณ์จะพร้อม
- **Audit my own old code.** I re-read my year-2 store, listed 20 mistakes, and fixed the 11 that affected security or data correctness.<br>
  **ตรวจงานเก่าของตัวเอง** ผมอ่านโค้ดร้านค้าที่ทำตอนปี 2 ใหม่ จดข้อผิดพลาดได้ 20 ข้อ และแก้ 11 ข้อที่กระทบความปลอดภัยหรือความถูกต้องของข้อมูล

## Projects / โปรเจกต์

<p><sub>01 / APPLIED AI · DATA PREPARATION · TEAM OF 2</sub></p>

<table>
  <tr>
    <td width="36%" valign="top">
      <a href="https://github.com/namethzz/chatbot-project">
        <img src="./assets/economic-crops-chat.webp" width="100%" alt="Economic Crops Chat answering a question about crops">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/namethzz/chatbot-project">Economic Crops Chat ↗</a></h3>
      <p><em>A Thai RAG chatbot that answers farming questions about 14 economic crops from government data.</em></p>
      <p><strong>ส่วนที่ผมทำ</strong></p>
      <ul>
        <li>เตรียมข้อมูล: แปลง CSV จากหน่วยงานรัฐกว่า 4,000 ไฟล์เป็นข้อมูลความเหมาะสมของพื้นที่ 45,746 รายการใน 77 จังหวัด และข้อมูลโรคและแมลง 97 รายการ</li>
        <li>ออกแบบหน้าแรก หน้าแชต และไอคอนพืชแต่ละชนิด</li>
      </ul>
      <p><strong>จุดเด่น</strong></p>
      <ul>
        <li>แก้ภาษาไทยที่ทำให้ค้นผิด: "ข้าวโพด" ถูกจับเป็น "ข้าว", "เลย" "ตาก" "แพร่" เป็นทั้งชื่อจังหวัดและคำทั่วไป และ "เเ" ที่พิมพ์เป็นสระเอสองตัว</li>
        <li>แชตบอตแยกคำถามเป็นเรื่องพื้นที่ วิธีปลูก หรือโรคพืช แล้วกรอง ChromaDB ตามพืชและจังหวัดก่อนส่งให้ LLM ตอบ คำถามนอกเรื่องเกษตรได้คำปฏิเสธโดยไม่ต้องค้น</li>
      </ul>
      <p><code>Python</code> <code>Pandas</code> <code>FastAPI</code> <code>ChromaDB</code> <code>bge-m3</code> <code>React</code></p>
      <p><a href="https://chatbot-project-phi-nine.vercel.app">Live demo ↗</a></p>
    </td>
  </tr>
</table>

<p><sub>02 / DATA PRODUCT · PRICE FORECASTING (IN PROGRESS) · SOLO</sub></p>

<table>
  <tr>
    <td width="36%" valign="top">
      <a href="https://github.com/namethzz/THAITAY">
        <img src="./assets/thaitay.webp" width="100%" alt="THAI TAY construction material price interface">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/namethzz/THAITAY">THAI TAY ↗</a></h3>
      <p><em>Price lookup and estimate builder for 287 structural building materials, with a 1–3 month forecast on the way.</em></p>
      <p><strong>ส่วนที่ผมทำ</strong></p>
      <ul>
        <li>คิดโปรดักต์และออกแบบหน้าเว็บทั้งหมด</li>
        <li>คัดวัสดุ 287 รายการใน 9 หมวดจากรหัสสินค้าของกระทรวงพาณิชย์ และเตรียมข้อมูลราคารายเดือนไว้ฝึกโมเดล</li>
      </ul>
      <p><strong>จุดเด่น</strong></p>
      <ul>
        <li>ช่องค้นหาเข้าใจคำหน้างาน พิมพ์ "sd40" เจอ "SD.40" และพิมพ์ "4 หุน" "ไวร์เมช" "DB12" ก็เจอ</li>
        <li>ร้านขายเหล็กเส้นเป็นตัน แต่ช่างนับเป็นเส้น เว็บแปลงให้ด้วยสูตรน้ำหนักมาตรฐาน 0.00617 × ศก.² กก./ม.</li>
        <li>ส่งใบประมาณราคาทาง LINE เป็นลิงก์ที่เก็บรายการและราคาไว้ในตัว ผมจึงไม่ต้องมีเซิร์ฟเวอร์</li>
        <li>ใช้ได้ตั้งแต่จอกว้าง 320 px และสีตัวอักษรทุกคู่ผ่าน WCAG AA</li>
      </ul>
      <p><code>React</code> <code>TypeScript</code> <code>Recharts</code> <code>Python</code> <code>Pandas</code></p>
      <p><a href="https://thaitay.vercel.app">Live demo ↗</a></p>
    </td>
  </tr>
</table>

<p><sub>03 / FULL-STACK · SERVICE MARKETPLACE · SOLO</sub></p>

<table>
  <tr>
    <td width="36%" valign="top">
      <a href="https://github.com/namethzz/Air-clean-">
        <img src="./assets/airclean.webp" width="100%" alt="AirClean air-conditioner cleaning service screens">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/namethzz/Air-clean-">AirClean ↗</a></h3>
      <p><em>A marketplace that matches customers with nearby air-con technicians, with real PromptPay payments.</em></p>
      <p><strong>ส่วนที่ผมทำ</strong></p>
      <ul>
        <li>ออกแบบ flow ของผู้ใช้ 4 บทบาท: ลูกค้า ช่าง ผู้ดูแลอาคาร และแอดมิน</li>
        <li>ออกแบบทุกหน้าจอ วางลำดับสถานะของงาน และสร้างทั้งเว็บ API และฐานข้อมูล</li>
      </ul>
      <p><strong>จุดเด่น</strong></p>
      <ul>
        <li>งานหนึ่งงานมี 11 สถานะ ตั้งแต่ลูกค้าส่งคำขอจนปิดงาน ลูกค้ามีเวลาเลือกช่าง 1 ชั่วโมงนับจากข้อเสนอแรก</li>
        <li>ช่างเห็นแค่ระยะทางคร่าว ๆ และเห็นที่อยู่จริงหลังลูกค้าเลือกแล้วเท่านั้น</li>
        <li>ช่างจ่ายค่าสมาชิกด้วย QR พร้อมเพย์ ระบบตรวจสลิปกับธนาคารผ่าน Slip2Go แล้วต่ออายุให้ทันที</li>
        <li>แจ้งเตือนผ่าน Web Push ได้ถึง iPhone ที่เพิ่มแอปไว้หน้าจอหลัก และลูกค้าเห็นตำแหน่งช่างบนแผนที่ระหว่างเดินทาง</li>
      </ul>
      <p><code>React</code> <code>TypeScript</code> <code>ASP.NET Core 8</code> <code>MongoDB</code> <code>PWA</code></p>
      <p><a href="https://aircare-connect-web.onrender.com">Live site ↗</a></p>
    </td>
  </tr>
</table>

<p><sub>04 / FULL-STACK · DESIGNED IN FIGMA · SOLO</sub></p>

<table>
  <tr>
    <td width="36%" valign="top">
      <a href="https://github.com/namethzz/kickhub">
        <img src="./assets/kickhub.webp" width="100%" alt="KickHub football meetup platform">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/namethzz/kickhub">KickHub ↗</a></h3>
      <p><em>Find a pickup football game, join a team, and chat with the players.</em></p>
      <p><strong>ส่วนที่ผมทำ</strong></p>
      <ul>
        <li>ออกแบบทุกหน้าจอใน Figma ก่อนเขียนโค้ด</li>
        <li>สร้างหน้าเว็บ API และฐานข้อมูล แล้ว deploy บน Render คู่กับ MongoDB Atlas</li>
      </ul>
      <p><strong>จุดเด่น</strong></p>
      <ul>
        <li>หัวตี้เลือกรูปแบบได้ 2 แบบ: บุฟเฟต์ไม่ล็อกตำแหน่ง หรือเปิดรับตามตำแหน่ง GK DF MF FW</li>
        <li>สมาชิกคุยกันในแชตของปาร์ตี้ ได้แจ้งเตือน และโหลดนัดลงปฏิทินได้</li>
        <li>การลบบัญชีใช้ MongoDB transaction ข้อมูลจึงหายครบทุกส่วนหรือไม่หายเลย</li>
        <li>GitHub Actions รัน unit test และ integration test กับ MongoDB จริงทุก pull request</li>
      </ul>
      <p><code>Figma</code> <code>React</code> <code>TypeScript</code> <code>Node.js</code> <code>Express</code> <code>MongoDB</code></p>
      <p><a href="https://kickhub-web.onrender.com/home">Live site ↗</a></p>
    </td>
  </tr>
</table>

<p><sub>05 / E-COMMERCE · YEAR-2 PROJECT · SOLO</sub></p>

<table>
  <tr>
    <td width="36%" valign="top">
      <a href="https://github.com/namethzz/OTW">
        <img src="./assets/otw.webp" width="100%" alt="OTW protein supplement online store">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/namethzz/OTW">OTW (On The Whey) ↗</a></h3>
      <p><em>A protein-supplement online store with a storefront and an admin back office.</em></p>
      <p><strong>ส่วนที่ผมทำ</strong></p>
      <ul>
        <li>ทำคนเดียวทั้งหน้าร้าน หลังร้าน Admin และฐานข้อมูล MySQL ตอนเรียนปี 2</li>
        <li>ปีนี้กลับมาตรวจโค้ดเดิม เปลี่ยนไปเก็บรหัสผ่านแบบ hash และเปิดป้องกัน CSRF ทุกฟอร์ม</li>
      </ul>
      <p><strong>จุดเด่น</strong></p>
      <ul>
        <li>โค้ดส่วนลดตั้งได้ทั้งแบบเปอร์เซ็นต์และจำนวนเงิน กำหนดยอดขั้นต่ำ ช่วงวัน กลุ่มลูกค้า และจำนวนครั้งที่ใช้ได้</li>
        <li>ตอนกดสั่งซื้อ ระบบดึงราคาล่าสุด ตัดสต็อก และนับการใช้โค้ดใน transaction เดียว ถ้าของไม่พอ ระบบยกเลิกทั้งออเดอร์</li>
        <li>สินค้าที่มีออเดอร์อ้างอิงอยู่ Admin ลบไม่ได้ ระบบปิดการขายแทน ประวัติออเดอร์จึงไม่หาย</li>
      </ul>
      <p><code>C#</code> <code>ASP.NET Core MVC</code> <code>MySQL</code> <code>EF Core</code></p>
      <p><a href="https://otw-production.up.railway.app">Live site ↗</a></p>
    </td>
  </tr>
</table>

## Skills / ทักษะ

| Area / ด้าน | Tools / เครื่องมือ |
| :--- | :--- |
| **Design** | Figma · shadcn/ui · 21st.dev components · Tailwind CSS |
| **Data** | Python · Pandas · NumPy · SQL · Looker Studio · Google Colab |
| **AI / LLM** | RAG · ChromaDB · sentence-transformers (bge-m3) · Typhoon LLM API · FastAPI |
| **Frontend** | React · TypeScript · Vite · Recharts · PWA |
| **Backend** | C# · ASP.NET Core · Node.js · Express |
| **Databases** | MongoDB · MySQL · SQL Server · SQLite |
| **Delivery** | Git · Docker · GitHub Actions · Render · Vercel · Hugging Face Spaces · n8n |

**Learning now / กำลังเรียน:** time-series forecasting for THAI TAY prices, a repeatable EDA routine, SQL, and charts you can read at a glance.<br>
การพยากรณ์อนุกรมเวลาสำหรับราคาวัสดุใน THAI TAY, การทำ EDA เป็นขั้นตอน, SQL และการทำกราฟที่อ่านเข้าใจได้ในครั้งเดียว

## GitHub activity

<p align="center">
  <a href="https://github.com/namethzz">
    <img width="420" src="https://github-stats-extended.vercel.app/api?username=namethzz&show_icons=true&hide_rank=true&card_width=420&line_height=20&text_bold=false&custom_title=GitHub%20Activity&bg_color=14120F&title_color=F2A93B&text_color=C5BDAF&icon_color=F2A93B&border_color=2A2620&border_radius=16&hide_border=false&disable_animations=true" alt="Nameth's public GitHub activity">
  </a>
  &nbsp;
  <a href="https://github.com/namethzz?tab=repositories">
    <img width="360" src="https://github-stats-extended.vercel.app/api/top-langs/?username=namethzz&layout=compact&langs_count=6&card_width=360&custom_title=Most%20Used%20Languages&bg_color=14120F&title_color=F2A93B&text_color=C5BDAF&icon_color=F2A93B&border_color=2A2620&border_radius=16&hide_border=false&disable_animations=true" alt="Languages used in Nameth's public repositories">
  </a>
</p>

## Contact / ติดต่อ

Want to talk about an internship or a project? Email me at **[nameth.won@spumail.net](mailto:nameth.won@spumail.net)**.<br>
อยากคุยเรื่องฝึกงานหรือโปรเจกต์ ส่งอีเมลมาได้ครับ · [Portfolio](https://namethzz.github.io/nameth-portfolio/)
