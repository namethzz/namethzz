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

**TH** ผมชื่อ **ณเมธ วงค์มงคล** เรียนวิทยาการคอมพิวเตอร์ที่มหาวิทยาลัยศรีปทุม (GPAX 3.79) ผมชอบงานที่เริ่มจากข้อมูลดิบที่ยังใช้ไม่ได้ แล้วจบที่ระบบที่คนเปิดใช้ได้จริง ทั้งการทำความสะอาดข้อมูล การทำ RAG และการสร้างเว็บแอปทั้งหน้าบ้านและหลังบ้าน ทุกโปรเจกต์ด้านล่างมีเว็บที่ deploy อยู่ กดลองได้เลย

**EN** I'm **Nameth Wongmongkol**, a Computer Science student at Sripatum University (GPAX 3.79). I like work that starts with raw data nobody can use and ends with a system people open in a browser: data cleaning, RAG pipelines, and full-stack apps. Every project below has a live deployment.

<p align="center">
  <sub>Looking for internships in / สนใจฝึกงานสาย</sub>
  <br>
  <strong>Data Engineer · AI Engineer · Data Scientist · Full-Stack Developer</strong>
</p>

## How I work / วิธีทำงานของผม

- **Understand the problem before writing code.** I talk to the people who will use the software, write down what they need, and keep asking why until I reach the cause.<br>
  **เข้าใจปัญหาก่อนเขียนโค้ด** ผมคุยกับคนที่จะใช้งานจริง จดว่าเขาต้องการอะไร แล้วถามต่อจนเจอต้นเหตุของปัญหา
- **Trace problems to the source.** In the crop chatbot, some CSV files sat in the wrong province folder. I read the province from the file name first and fall back to the folder.<br>
  **ตามหาต้นเหตุ** ไฟล์ CSV บางไฟล์ของแชตบอตพืชอยู่ผิดโฟลเดอร์จังหวัด ผมจึงอ่านจังหวัดจากชื่อไฟล์ก่อน ถ้าไม่มีค่อยดูจากชื่อโฟลเดอร์
- **Design for the customer.** Screens they understand at a glance, pages that load fast, and nothing that misleads them. THAI TAY shows a "demo data" tag on every price, estimate, and shared link until the forecast model exists.<br>
  **ออกแบบให้ลูกค้าใช้ได้จริง** หน้าจอที่ดูแล้วเข้าใจทันที โหลดเร็ว และไม่ทำให้ผู้ใช้เข้าใจผิด THAI TAY ติดป้าย "ข้อมูลตัวอย่าง" บนทุกราคา ใบประมาณ และลิงก์ที่ส่งต่อ จนกว่าโมเดลพยากรณ์จะเสร็จ
- **Check security and the details.** I re-read my year-2 e-commerce project, wrote down 20 mistakes, and fixed the 11 that touched security or data correctness.<br>
  **ใส่ใจความปลอดภัยและรายละเอียด** ผมอ่านโค้ดร้านค้าออนไลน์ที่ทำตอนปี 2 ใหม่ จดข้อผิดพลาดได้ 20 ข้อ แล้วแก้ 11 ข้อที่กระทบความปลอดภัยหรือความถูกต้องของข้อมูล

## Projects / โปรเจกต์

<p><sub>01 / APPLIED AI · DATA PREPARATION</sub></p>

<table>
  <tr>
    <td width="36%" valign="top">
      <a href="https://github.com/namethzz/chatbot-project">
        <img src="./assets/economic-crops-chat.webp" width="100%" alt="Economic Crops Chat answering a question about crops">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/namethzz/chatbot-project">Economic Crops Chat ↗</a></h3>
      <p>A Thai RAG chatbot for 14 economic crops, built by a team of two. It filters ChromaDB by crop, province, and question type, then has a Thai LLM (Typhoon) answer from the retrieved documents only. I prepared the data: 4,000+ government CSV files became 45,746 land-suitability records across 77 provinces, plus 97 pest and disease entries. Thai text caused most of the retrieval bugs. "ข้าวโพด" (corn) matched "ข้าว" (rice), and "เลย", "ตาก", "แพร่" are both provinces and everyday words.</p>
      <p>แชตบอต RAG ภาษาไทยเรื่องพืชเศรษฐกิจ 14 ชนิด ทำเป็นทีม 2 คน ผมดูแลข้อมูล แปลง CSV จากหน่วยงานรัฐกว่า 4,000 ไฟล์เป็นข้อมูลความเหมาะสมของพื้นที่ 45,746 รายการใน 77 จังหวัด และข้อมูลโรคและแมลง 97 รายการ พร้อมแก้ปัญหาภาษาไทยที่ทำให้ค้นผิด เช่น ตัว "เเ" ที่พิมพ์เป็นสระเอสองตัว</p>
      <p><code>Python</code> <code>Pandas</code> <code>FastAPI</code> <code>ChromaDB</code> <code>bge-m3</code> <code>React</code></p>
      <p><a href="https://chatbot-project-phi-nine.vercel.app">Live demo ↗</a></p>
    </td>
  </tr>
</table>

<p><sub>02 / DATA PRODUCT · PRICE FORECASTING (IN PROGRESS)</sub></p>

<table>
  <tr>
    <td width="36%" valign="top">
      <a href="https://github.com/namethzz/THAITAY">
        <img src="./assets/thaitay.webp" width="100%" alt="THAI TAY construction material price interface">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/namethzz/THAITAY">THAI TAY ↗</a></h3>
      <p>Price lookup for 287 structural building materials, keyed to Ministry of Commerce product codes. You add quantities, get a printable estimate, and share it as a LINE link that carries its own prices, so the page needs no server. Shops sell rebar by the ton while site crews count bars; the app converts between the two. The next step is a 1–3 month price forecast trained on MOC monthly open data.</p>
      <p>เว็บดูราคาวัสดุงานโครงสร้าง 287 รายการ อ้างอิงรหัสสินค้าของกระทรวงพาณิชย์ ใส่จำนวนแล้วได้ใบประมาณราคาที่พิมพ์หรือส่งลิงก์ทาง LINE ได้ ขั้นต่อไปคือโมเดลพยากรณ์ราคาล่วงหน้า 1–3 เดือนจากข้อมูลเปิดรายเดือนของกระทรวงพาณิชย์</p>
      <p><code>React</code> <code>TypeScript</code> <code>Recharts</code> <code>Python</code> <code>Pandas</code></p>
      <p><a href="https://thaitay.vercel.app">Live demo ↗</a></p>
    </td>
  </tr>
</table>

<p><sub>03 / FULL-STACK · SERVICE MARKETPLACE</sub></p>

<table>
  <tr>
    <td width="36%" valign="top">
      <a href="https://github.com/namethzz/Air-clean-">
        <img src="./assets/airclean.webp" width="100%" alt="AirClean air-conditioner cleaning service screens">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/namethzz/Air-clean-">AirClean ↗</a></h3>
      <p>Customers post one air-con cleaning request, nearby technicians send quotes, and the customer picks one. Technicians see the exact address only after the customer chooses them. Technicians pay a membership fee by PromptPay, and the backend checks each slip with the bank.</p>
      <p>ลูกค้าส่งคำขอล้างแอร์ครั้งเดียว ช่างใกล้บ้านเสนอราคา ลูกค้าเลือกเอง ช่างเห็นที่อยู่จริงหลังลูกค้าเลือกแล้วเท่านั้น ช่างจ่ายค่าสมาชิกผ่าน PromptPay และระบบตรวจสลิปกับธนาคาร</p>
      <p><code>React</code> <code>TypeScript</code> <code>ASP.NET Core 8</code> <code>MongoDB</code> <code>PWA</code></p>
      <p><a href="https://aircare-connect-web.onrender.com">Live site ↗</a></p>
    </td>
  </tr>
</table>

<p><sub>04 / FULL-STACK · COMMUNITY APP</sub></p>

<table>
  <tr>
    <td width="36%" valign="top">
      <a href="https://github.com/namethzz/kickhub">
        <img src="./assets/kickhub.webp" width="100%" alt="KickHub football meetup platform">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/namethzz/kickhub">KickHub ↗</a></h3>
      <p>Players find pickup football games by date, budget, and pitch. Hosts approve join requests and chat with their team; pitch owners list their own venues. Account deletion runs in a MongoDB transaction, so it removes all of a user's data or none of it. Unit and integration tests run against a real MongoDB in GitHub Actions on every pull request.</p>
      <p>เว็บหาคนเตะฟุตบอล ค้นปาร์ตี้ตามวัน งบ และสนาม หัวตี้อนุมัติคำขอและคุยกับทีมในแชต การลบบัญชีใช้ MongoDB transaction ข้อมูลจึงหายครบทุกส่วนหรือไม่หายเลย และ GitHub Actions รัน test กับ MongoDB จริงทุก pull request</p>
      <p><code>React</code> <code>TypeScript</code> <code>Node.js</code> <code>Express</code> <code>MongoDB</code></p>
      <p><a href="https://kickhub-web.onrender.com/home">Live site ↗</a></p>
    </td>
  </tr>
</table>

<p><sub>05 / E-COMMERCE · CODE REVIEW OF MY OWN WORK</sub></p>

<table>
  <tr>
    <td width="36%" valign="top">
      <a href="https://github.com/namethzz/OTW">
        <img src="./assets/otw.webp" width="100%" alt="OTW protein supplement online store">
      </a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/namethzz/OTW">OTW (On The Whey) ↗</a></h3>
      <p>A protein-supplement store I built alone in year 2: catalog, cart, promo codes, orders, and returns. The README lists what I got wrong back then, from plain-text passwords to a cart that accepted negative quantities. Checkout now re-reads prices from the database and reserves stock and promo usage in one transaction.</p>
      <p>ร้านเวย์โปรตีนออนไลน์ที่ผมทำคนเดียวตอนปี 2 README บอกว่าตอนนั้นผมพลาดอะไรบ้าง เช่น เก็บรหัสผ่านแบบข้อความธรรมดา และตะกร้ารับจำนวนติดลบ ตอนนี้ Checkout ดึงราคาล่าสุดจากฐานข้อมูล แล้วตัดสต็อกกับนับการใช้โค้ดใน transaction เดียว</p>
      <p><code>C#</code> <code>ASP.NET Core MVC</code> <code>MySQL</code> <code>EF Core</code></p>
      <p><a href="https://otw-production.up.railway.app">Live site ↗</a></p>
    </td>
  </tr>
</table>

## Skills / ทักษะ

| Area / ด้าน | Tools / เครื่องมือ |
| :--- | :--- |
| **Data** | Python · Pandas · NumPy · SQL · Looker Studio · Google Colab |
| **AI / LLM** | RAG · ChromaDB · sentence-transformers (bge-m3) · Typhoon LLM API · FastAPI |
| **Frontend** | React · TypeScript · Vite · Tailwind CSS · Recharts |
| **Backend** | C# · ASP.NET Core · Node.js · Express |
| **Databases** | MongoDB · MySQL · SQL Server · SQLite |
| **Delivery** | Git · Docker · GitHub Actions · Render · Vercel · Hugging Face Spaces · n8n |

**Learning now / กำลังเรียน:** time-series forecasting for THAI TAY prices, a repeatable EDA routine, SQL, and charts people read in one glance.<br>
การพยากรณ์อนุกรมเวลาสำหรับราคาวัสดุใน THAI TAY, การทำ EDA เป็นขั้นตอน, SQL และการทำกราฟที่อ่านเข้าใจในครั้งเดียว

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

Internship or project chat, email me: **[nameth.won@spumail.net](mailto:nameth.won@spumail.net)**<br>
อยากคุยเรื่องฝึกงานหรือโปรเจกต์ ส่งอีเมลมาได้ครับ · [Portfolio](https://namethzz.github.io/nameth-portfolio/)
