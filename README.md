<p>
  <picture>
    <source media="(max-width: 600px)" srcset="./nameth-header-mobile.svg">
    <img src="./nameth-header.svg" width="100%" alt="Nameth Wongmongkol: Data Analytics & Full-Stack Development">
  </picture>
</p>

<p align="center">
  <strong>Computer Science &amp; Software Development · Sripatum University</strong>
  <br>
  <sub>Thailand &nbsp; · &nbsp; Open to internships in data analytics and software development</sub>
</p>

<p align="center">
  <a href="mailto:nameth.won@spumail.net">Get in touch ↗</a>
  &nbsp;&nbsp; / &nbsp;&nbsp;
  <a href="https://github.com/namethzz?tab=repositories">All repositories ↗</a>
</p>

<br>

## About

I build web applications end to end: the database, the API, and the screens people use on their phones. I also like the data side, cleaning messy files until a model or a chart can use them.

The five projects below run from my second year to my fourth. I went back to the older ones in 2026, fixed what I could, and wrote down what I got wrong the first time. Each README explains how the project works and what is still missing.

<br>

## Projects

<p><sub>YEAR 2 &nbsp; / &nbsp; 01</sub></p>

<table>
  <tr>
    <td width="42%" valign="top">
      <a href="https://github.com/namethzz/OTW"><img src="./assets/otw.webp" alt="OTW storefront home page"></a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/namethzz/OTW">OTW (On The Whey) ↗</a></h3>
      <p>An online store for whey and plant protein. Customers browse, fill a cart, apply promotion codes and request returns. Admins manage products, orders, promotions and refunds.</p>
      <p>I built it alone in year 2. In the 2026 review I hashed passwords, added CSRF checks, validated uploads, and moved checkout stock updates into one transaction so two buyers can't oversell. The README lists the mistakes I left in on purpose.</p>
      <p><code>C#</code> <code>ASP.NET Core MVC</code> <code>MySQL</code> <code>EF Core</code> <code>Docker</code></p>
      <p><a href="https://otw-production.up.railway.app">Live site ↗</a></p>
    </td>
  </tr>
</table>

<p><sub>YEAR 2 &nbsp; / &nbsp; 02</sub></p>

<table>
  <tr>
    <td width="42%" valign="top">
      <a href="https://github.com/namethzz/kickhub"><img src="./assets/kickhub.webp" alt="KickHub home page"></a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/namethzz/kickhub">KickHub ↗</a></h3>
      <p>Find people to play football with. Players search open games by date, budget and field, then ask to join. Hosts pick a mode (open "buffet" or fixed positions GK/DF/MF/FW), approve requests and chat with the team. Field owners list their own pitches.</p>
      <p>Google and Facebook sign-in, account deletion in one MongoDB transaction, and 101 automated tests that run on every pull request.</p>
      <p><code>React</code> <code>TypeScript</code> <code>Node.js</code> <code>Express</code> <code>MongoDB</code> <code>GitHub Actions</code></p>
      <p><a href="https://kickhub-web.onrender.com/home">Live site ↗</a></p>
    </td>
  </tr>
</table>

<p><sub>YEAR 3 &nbsp; / &nbsp; 03 &nbsp; · &nbsp; TEAM PROJECT</sub></p>

<table>
  <tr>
    <td width="42%" valign="top">
      <a href="https://chatbot-project-phi-nine.vercel.app"><img src="./assets/economic-crops-chat.webp" alt="Economic Crops Chat answering a question about coconut growing areas"></a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/namethzz/chatbot-project">Economic Crops Chat ↗</a></h3>
      <p>A Thai chatbot for 14 economic crops. You ask where a crop grows well, how to plant it, or which diseases hit it, and the bot answers from Thai government data with sources (RAG).</p>
      <p><strong>My part:</strong> the data. I turned 4,000+ CSV files into search documents: 45,746 land-suitability records across 77 provinces and 97 pest and disease entries. I fixed misplaced files, misspelled crop names and Thai characters that look the same but aren't.</p>
      <p><code>Python</code> <code>FastAPI</code> <code>ChromaDB</code> <code>bge-m3</code> <code>React</code> <code>Node.js</code> <code>MongoDB</code></p>
      <p><a href="https://chatbot-project-phi-nine.vercel.app">Live demo ↗</a> <sub>(demo mode with prepared answers)</sub></p>
    </td>
  </tr>
</table>

<p><sub>YEAR 4 &nbsp; / &nbsp; 04</sub></p>

<table>
  <tr>
    <td width="42%" valign="top">
      <a href="https://github.com/namethzz/Air-clean-"><img src="./assets/airclean.webp" alt="AirClean screens: comparing technician offers, nearby jobs, and membership payment by PromptPay"></a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/namethzz/Air-clean-">AirClean ↗</a></h3>
      <p>A marketplace for air-conditioner cleaning. A customer posts one request, nearby technicians send quotes from their own price sheets, and the customer picks one within an hour. Technicians see the real address only after they win the job.</p>
      <p>Four user roles, live technician tracking on a map, Web Push written from the RFCs with no library, and monthly technician fees paid by PromptPay QR with automatic slip checks against the bank.</p>
      <p><code>React</code> <code>TypeScript</code> <code>ASP.NET Core 8</code> <code>MongoDB</code> <code>PWA</code> <code>xUnit</code></p>
      <p><a href="https://aircare-connect-web.onrender.com">Live site ↗</a></p>
    </td>
  </tr>
</table>

<p><sub>YEAR 4 &nbsp; / &nbsp; 05 &nbsp; · &nbsp; IN PROGRESS</sub></p>

<table>
  <tr>
    <td width="42%" valign="top">
      <a href="https://thaitay.vercel.app"><img src="./assets/thaitay.webp" alt="THAI TAY home page with a steel price card"></a>
    </td>
    <td valign="top">
      <h3><a href="https://github.com/namethzz/THAITAY">THAI TAY ↗</a></h3>
      <p>Know construction material prices three months ahead. You type a structural material such as rebar or ready-mix concrete, see the latest price and a 1 to 3 month forecast, then add it to a cost estimate you can print or send over LINE.</p>
      <p>The web app works today with 287 materials in 9 categories. The forecasting model and the backend are next, so every price on the site today is labeled as demo data.</p>
      <p><code>React</code> <code>TypeScript</code> <code>Vite</code> <code>Python</code> <code>Pandas</code></p>
      <p><a href="https://thaitay.vercel.app">Live demo ↗</a></p>
    </td>
  </tr>
</table>

<br>

## Skills & tools

| Area | Technologies |
| :--- | :--- |
| **Data & analysis** | Python · Pandas · NumPy · SQL · Looker Studio |
| **Frontend** | React · TypeScript · JavaScript · Vite · Tailwind CSS · Razor |
| **Backend** | C# · ASP.NET Core · Node.js · Express · FastAPI |
| **Databases** | MongoDB · MySQL · SQL Server · ChromaDB · SQLite |
| **Deploy** | Docker · GitHub Actions · Render · Vercel · Railway |

### Tools

<p>
  <img src="https://img.shields.io/badge/Git-101A24?style=for-the-badge&amp;logo=git&amp;logoColor=9AD9BF" alt="Git" />
  &nbsp;
  <img src="https://img.shields.io/badge/Docker-101A24?style=for-the-badge&amp;logo=docker&amp;logoColor=9AD9BF" alt="Docker" />
  &nbsp;
  <img src="https://img.shields.io/badge/GitHub_Actions-101A24?style=for-the-badge&amp;logo=githubactions&amp;logoColor=9AD9BF" alt="GitHub Actions" />
  &nbsp;
  <img src="https://img.shields.io/badge/Postman-101A24?style=for-the-badge&amp;logo=postman&amp;logoColor=9AD9BF" alt="Postman" />
  &nbsp;
  <img src="https://img.shields.io/badge/n8n-101A24?style=for-the-badge&amp;logo=n8n&amp;logoColor=9AD9BF" alt="n8n" />
  &nbsp;
  <img src="https://img.shields.io/badge/Google_Colab-101A24?style=for-the-badge&amp;logo=googlecolab&amp;logoColor=9AD9BF" alt="Google Colab" />
</p>

<br>

## Currently learning

- **Machine learning for time series**, to forecast material prices in THAI TAY
- **SQL**: queries and database fundamentals
- **Data visualization**: charts and dashboards people can read at a glance

<br>

## GitHub Stats

<p align="center">
  <a href="https://github.com/namethzz">
    <img width="420" src="https://github-stats-extended.vercel.app/api?username=namethzz&amp;show_icons=true&amp;hide_rank=true&amp;card_width=420&amp;line_height=20&amp;text_bold=false&amp;custom_title=GitHub%20Activity&amp;bg_color=101A24&amp;title_color=9AD9BF&amp;text_color=BBC9CF&amp;icon_color=9AD9BF&amp;border_color=26333E&amp;border_radius=16&amp;hide_border=false&amp;disable_animations=true" alt="Nameth's public GitHub activity" />
  </a>
  &nbsp;
  <a href="https://github.com/namethzz?tab=repositories">
    <img width="360" src="https://github-stats-extended.vercel.app/api/top-langs/?username=namethzz&amp;layout=compact&amp;langs_count=6&amp;card_width=360&amp;custom_title=Most%20Used%20Languages&amp;bg_color=101A24&amp;title_color=9AD9BF&amp;text_color=BBC9CF&amp;icon_color=9AD9BF&amp;border_color=26333E&amp;border_radius=16&amp;hide_border=false&amp;disable_animations=true" alt="Language usage in Nameth's public repositories" />
  </a>
</p>

<br>

## Let's connect

<p align="center">
  <sub>Open to internships in data analytics and software development.</sub>
</p>

<p align="center">
  <a href="mailto:nameth.won@spumail.net">
    <img src="https://img.shields.io/badge/Email_me-9AD9BF?style=for-the-badge&amp;logo=gmail&amp;logoColor=0B1118" alt="Email Nameth" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/namethzz?tab=repositories">
    <img src="https://img.shields.io/badge/All_repositories-101A24?style=for-the-badge&amp;logo=github&amp;logoColor=9AD9BF" alt="Nameth's repositories" />
  </a>
</p>

<p align="center">
  <sub>
    <a href="mailto:nameth.won@spumail.net">nameth.won@spumail.net</a>
    &nbsp; / &nbsp;
    <a href="https://github.com/namethzz">@namethzz</a>
  </sub>
</p>
