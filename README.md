<html lang="th">
<head>
  <meta charset="UTF-8" />
  <title>Thai Local Learning Resources Map</title>
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <meta
    name="description"
    content="A smart directory of local learning centers across Thailand, mapped to the Basic Education Core Curriculum B.E. 2551 (Revised B.E. 2560)."
  />
  <style>
    :root {
      font-family: system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI",
        sans-serif;
      color-scheme: light dark;
    }

    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      padding: 0;
      background: #f5f7fb;
      color: #111827;
      display: flex;
      justify-content: center;
      min-height: 100vh;
    }

    .page {
      width: 100%;
      max-width: 960px;
      padding: 24px 16px 40px;
    }

    .card {
      background: #ffffff;
      border-radius: 18px;
      padding: 24px 20px 28px;
      box-shadow: 0 18px 45px rgba(15, 23, 42, 0.12);
      border: 1px solid rgba(148, 163, 184, 0.35);
    }

    .badge {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      padding: 4px 10px;
      border-radius: 999px;
      background: #e0f2fe;
      color: #0369a1;
      font-size: 12px;
      font-weight: 600;
      letter-spacing: 0.02em;
      text-transform: uppercase;
      margin-bottom: 10px;
    }

    .badge-dot {
      width: 7px;
      height: 7px;
      border-radius: 999px;
      background: #22c55e;
      box-shadow: 0 0 0 4px rgba(34, 197, 94, 0.25);
    }

    h1 {
      font-size: clamp(26px, 3vw, 32px);
      margin: 0 0 6px;
      color: #0f172a;
    }

    .subtitle {
      font-size: 14px;
      color: #6b7280;
      margin-bottom: 18px;
    }

    .pill-row {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-bottom: 22px;
    }

    .pill {
      font-size: 12px;
      padding: 4px 10px;
      border-radius: 999px;
      border: 1px solid #e5e7eb;
      background: #f9fafb;
      color: #4b5563;
    }

    .grid {
      display: grid;
      grid-template-columns: 1.4fr 1fr;
      gap: 24px;
      align-items: flex-start;
    }

    @media (max-width: 768px) {
      .grid {
        grid-template-columns: 1fr;
      }
      .card {
        padding: 20px 16px 22px;
      }
    }

    h2 {
      font-size: 18px;
      margin: 0 0 10px;
      color: #111827;
    }

    p {
      font-size: 14px;
      line-height: 1.7;
      margin: 0 0 8px;
    }

    ul {
      padding-left: 1.25rem;
      margin: 0 0 8px;
    }

    li {
      font-size: 14px;
      line-height: 1.6;
      margin-bottom: 4px;
    }

    .section {
      margin-top: 18px;
    }

    .section + .section {
      margin-top: 14px;
      padding-top: 14px;
      border-top: 1px dashed #e5e7eb;
    }

    code {
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas,
        "Liberation Mono", "Courier New", monospace;
      font-size: 13px;
      background: #0f172a;
      color: #e5e7eb;
      padding: 3px 7px;
      border-radius: 6px;
    }

    .code-block {
      background: #020617;
      color: #e5e7eb;
      border-radius: 10px;
      padding: 10px 12px;
      font-family: ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas,
        "Liberation Mono", "Courier New", monospace;
      font-size: 13px;
      margin: 8px 0;
      overflow-x: auto;
      border: 1px solid #1f2937;
    }

    .code-line {
      white-space: pre;
    }

    .tag {
      display: inline-block;
      font-size: 12px;
      padding: 3px 8px;
      border-radius: 999px;
      background: #eef2ff;
      color: #4338ca;
      margin-bottom: 6px;
    }

    .small-note {
      font-size: 12px;
      color: #9ca3af;
      margin-top: 6px;
    }

    .link-row {
      display: flex;
      flex-wrap: wrap;
      gap: 8px;
      margin-top: 10px;
    }

    .btn-link {
      display: inline-flex;
      align-items: center;
      gap: 6px;
      padding: 6px 12px;
      border-radius: 999px;
      border: 1px solid #d1d5db;
      background: #f9fafb;
      color: #111827;
      text-decoration: none;
      font-size: 13px;
    }

    .btn-link span.icon {
      font-size: 14px;
    }

    .footer {
      margin-top: 14px;
      font-size: 11px;
      color: #9ca3af;
      text-align: right;
    }
  </style>
</head>
<body>
  <main class="page">
    <section class="card">
      <div class="badge">
        <span class="badge-dot"></span>
        AI-Powered Education Tool
      </div>

      <h1>Thai Local Learning Resources Map</h1>
      <div class="subtitle">
        แผนที่แหล่งเรียนรู้ท้องถิ่นทั่วประเทศไทย เชื่อมโยงกับหลักสูตรแกนกลางการศึกษาขั้นพื้นฐาน พ.ศ. 2551
        (ปรับปรุง พ.ศ. 2560)
      </div>

      <div class="pill-row">
        <div class="pill">React + Vite</div>
        <div class="pill">Node.js</div>
        <div class="pill">@google/genai</div>
        <div class="pill">Local Learning Resources</div>
      </div>

      <div class="grid">
        <!-- Left: project description -->
        <div>
          <div class="section">
            <h2>แนวคิดของระบบ</h2>
            <p>
              ระบบนี้ออกแบบมาเพื่อเป็น <strong>“สมุดหน้าเหลือง” ด้านการเรียนรู้ท้องถิ่น</strong>
              ช่วยให้ครูและนักเรียนสามารถค้นหาแหล่งเรียนรู้ใกล้ตัว เช่น
              ศูนย์การเรียนรู้ชุมชน พิพิธภัณฑ์ ห้องสมุด แหล่งวัฒนธรรม หรือสถานประกอบการ
              แล้วเชื่อมโยงกับสาระการเรียนรู้และตัวชี้วัดในหลักสูตรแกนกลางฯ
            </p>
            <p>
              สามารถนำไปใช้วางแผนทัศนศึกษา จัดโครงงานฐานสมรรถนะ
              และกิจกรรมการเรียนรู้นอกห้องเรียนได้อย่างเป็นระบบ
            </p>
          </div>

          <div class="section">
            <h2>การประยุกต์ใช้ในโรงเรียน</h2>
            <ul>
              <li>ครูใช้ค้นหาแหล่งเรียนรู้ที่สอดคล้องกับหน่วยการเรียนรู้/โครงงาน</li>
              <li>นักเรียนใช้สำรวจแหล่งเรียนรู้ใกล้บ้านเพื่อทำโครงงานหรือ Portfolio</li>
              <li>ผู้บริหารใช้วางแผนความร่วมมือกับชุมชนและเครือข่ายภายนอก</li>
            </ul>
          </div>
        </div>

        <!-- Right: how to run -->
        <div>
          <div class="section">
            <span class="tag">Developers</span>
            <h2>วิธีรันโปรเจกต์ในเครื่อง (Run Locally)</h2>
            <p>1) ติดตั้ง Node.js ให้เรียบร้อย</p>
            <p>2) เปิดโฟลเดอร์โปรเจกต์ แล้วรันคำสั่งต่อไปนี้ใน Terminal:</p>

            <div class="code-block">
              <div class="code-line">npm install</div>
              <div class="code-line">npm run dev</div>
            </div>

            <p>3) ตั้งค่า API key ของ Gemini ในไฟล์ <code>.env.local</code> ตัวอย่างเช่น:</p>

            <div class="code-block">
              <div class="code-line">GEMINI_API_KEY=YOUR_API_KEY_HERE</div>
            </div>

            <p class="small-note">
              จากนั้นเปิดเบราว์เซอร์ตาม URL ที่ Vite แสดง (เช่น
              <code>http://localhost:5173</code>) เพื่อใช้งานแอปพลิเคชัน
            </p>
          </div>

          <div class="section">
            <h2>ลิงก์ที่เกี่ยวข้อง</h2>
            <div class="link-row">
              <a
                class="btn-link"
                href="https://ai.studio/apps/drive/1NN5VJ3xOmOQC1I3Yi_bow5Eg044ypsDu"
                target="_blank"
                rel="noopener noreferrer"
              >
                <span class="icon">⚙️</span>
                <span>เปิดใน AI Studio</span>
              </a>
            </div>
          </div>
        </div>
      </div>

      <div class="footer">
        แม่แบบ HTML นี้สร้างจากข้อมูล metadata ของโปรเจกต์และ README เพื่อใช้เป็นหน้าแนะนำระบบหรือหน้า
        landing page สามารถแก้ไขข้อความ สี และสไตล์ได้ตามต้องการ
      </div>
    </section>
  </main>
</body>
</html>
