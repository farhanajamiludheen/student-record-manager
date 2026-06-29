<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Student Record Manager</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&family=Space+Grotesk:wght@500;700&display=swap');

    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    :root {
      --bg: #0f1117;
      --surface: #1a1d27;
      --card: #21253a;
      --accent: #6c63ff;
      --accent2: #a78bfa;
      --danger: #f87171;
      --success: #34d399;
      --text: #e2e8f0;
      --muted: #94a3b8;
      --border: #2e3350;
    }

    body {
      font-family: 'Inter', sans-serif;
      background: var(--bg);
      color: var(--text);
      min-height: 100vh;
      padding: 2rem 1rem;
    }

    header {
      text-align: center;
      margin-bottom: 2.5rem;
    }

    header h1 {
      font-family: 'Space Grotesk', sans-serif;
      font-size: 2rem;
      font-weight: 700;
      background: linear-gradient(135deg, var(--accent), var(--accent2));
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      margin-bottom: 0.4rem;
    }

    header p {
      color: var(--muted);
      font-size: 0.9rem;
    }

    .stats {
      display: flex;
      gap: 1rem;
      justify-content: center;
      flex-wrap: wrap;
      margin-bottom: 2rem;
    }

    .stat-card {
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 12px;
      padding: 1rem 1.5rem;
      text-align: center;
      min-width: 120px;
    }

    .stat-card .num {
      font-family: 'Space Grotesk', sans-serif;
      font-size: 1.8rem;
      font-weight: 700;
      color: var(--accent2);
    }

    .stat-card .label {
      font-size: 0.75rem;
      color: var(--muted);
      margin-top: 0.2rem;
    }

    .container {
      max-width: 900px;
      margin: 0 auto;
    }

    .form-card {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 16px;
      padding: 1.5rem;
      margin-bottom: 2rem;
    }

    .form-card h2 {
      font-family: 'Space Grotesk', sans-serif;
      font-size: 1rem;
      font-weight: 600;
      margin-bottom: 1rem;
      color: var(--accent2);
    }

    .form-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 1rem;
      margin-bottom: 1rem;
    }

    .field label {
      display: block;
      font-size: 0.75rem;
      color: var(--muted);
      margin-bottom: 0.4rem;
      font-weight: 500;
    }

    .field input, .field select {
      width: 100%;
      background: var(--card);
      border: 1px solid var(--border);
      border-radius: 8px;
      color: var(--text);
      padding: 0.6rem 0.8rem;
      font-size: 0.875rem;
      font-family: 'Inter', sans-serif;
      outline: none;
      transition: border-color 0.2s;
    }

    .field input:focus, .field select:focus {
      border-color: var(--accent);
    }

    .field select option { background: var(--card); }

    .btn-row {
      display: flex;
      gap: 0.75rem;
      flex-wrap: wrap;
    }

    button {
      font-family: 'Inter', sans-serif;
      font-weight: 600;
      font-size: 0.85rem;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      padding: 0.6rem 1.2rem;
      transition: opacity 0.2s, transform 0.1s;
    }

    button:hover { opacity: 0.85; }
    button:active { transform: scale(0.97); }

    .btn-primary { background: var(--accent); color: #fff; }
    .btn-danger  { background: var(--danger); color: #fff; }
    .btn-success { background: var(--success); color: #0f1117; }
    .btn-outline {
      background: transparent;
      border: 1px solid var(--border);
      color: var(--muted);
    }

    .search-row {
      display: flex;
      gap: 0.75rem;
      margin-bottom: 1rem;
      flex-wrap: wrap;
    }

    .search-row input {
      flex: 1;
      min-width: 180px;
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 8px;
      color: var(--text);
      padding: 0.6rem 0.9rem;
      font-size: 0.875rem;
      font-family: 'Inter', sans-serif;
      outline: none;
    }

    .search-row input:focus { border-color: var(--accent); }

    table {
      width: 100%;
      border-collapse: collapse;
      font-size: 0.85rem;
    }

    thead tr {
      background: var(--card);
    }

    th {
      padding: 0.75rem 1rem;
      text-align: left;
      font-size: 0.72rem;
      font-weight: 600;
      color: var(--muted);
      text-transform: uppercase;
      letter-spacing: 0.05em;
      cursor: pointer;
      user-select: none;
    }

    th:hover { color: var(--accent2); }

    td {
      padding: 0.75rem 1rem;
      border-bottom: 1px solid var(--border);
    }

    tr:hover td { background: var(--surface); }

    .badge {
      display: inline-block;
      padding: 0.2rem 0.6rem;
      border-radius: 999px;
      font-size: 0.72rem;
      font-weight: 600;
    }

    .badge-pass { background: rgba(52,211,153,0.15); color: var(--success); }
    .badge-fail { background: rgba(248,113,113,0.15); color: var(--danger); }
    .badge-avg  { background: rgba(108,99,255,0.15);  color: var(--accent2); }

    .action-btn {
      background: none;
      border: none;
      cursor: pointer;
      font-size: 1rem;
      padding: 0.2rem 0.4rem;
      border-radius: 6px;
      transition: background 0.2s;
    }

    .action-btn:hover { background: var(--border); }

    .table-wrap {
      background: var(--surface);
      border: 1px solid var(--border);
      border-radius: 16px;
      overflow: hidden;
    }

    .table-header {
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 1rem 1.5rem;
      border-bottom: 1px solid var(--border);
    }

    .table-header h2 {
      font-family: 'Space Grotesk', sans-serif;
      font-size: 1rem;
      font-weight: 600;
      color: var(--accent2);
    }

    .empty {
      text-align: center;
      padding: 3rem;
      color: var(--muted);
      font-size: 0.875rem;
    }

    .toast {
      position: fixed;
      bottom: 1.5rem;
      right: 1.5rem;
      background: var(--card);
      border: 1px solid var(--border);
      color: var(--text);
      padding: 0.75rem 1.2rem;
      border-radius: 10px;
      font-size: 0.85rem;
      font-weight: 500;
      box-shadow: 0 8px 30px rgba(0,0,0,0.4);
      opacity: 0;
      transform: translateY(10px);
      transition: all 0.3s;
      z-index: 999;
      pointer-events: none;
    }

    .toast.show { opacity: 1; transform: translateY(0); }
  </style>
</head>
<body>
<div class="container">

  <header>
    <h1>Student Record Manager</h1>
    <p>A student record management system built with HTML and CSS, with database design concepts based on SQL</p>
  </header>

  <div class="stats">
    <div class="stat-card"><div class="num" id="stat-total">0</div><div class="label">Total Students</div></div>
    <div class="stat-card"><div class="num" id="stat-avg">—</div><div class="label">Average Grade</div></div>
    <div class="stat-card"><div class="num" id="stat-pass">0</div><div class="label">Passing</div></div>
    <div class="stat-card"><div class="num" id="stat-fail">0</div><div class="label">Failing</div></div>
  </div>

  <div class="form-card">
    <h2>➕ Add / Edit Student</h2>
    <div class="form-grid">
      <div class="field"><label>Student ID</label><input id="f-id" placeholder="e.g. STU001" /></div>
      <div class="field"><label>Full Name</label><input id="f-name" placeholder="e.g. Farhana" /></div>
      <div class="field"><label>Course</label>
        <select id="f-course">
          <option value="">Select course</option>
          <option>Full Stack Development</option>
          <option>Data Science</option>
          <option>Web Design</option>
          <option>SQL & Databases</option>
          <option>Cybersecurity</option>
        </select>
      </div>
      <div class="field"><label>Grade (%)</label><input id="f-grade" type="number" min="0" max="100" placeholder="e.g. 85" /></div>
      <div class="field"><label>Email</label><input id="f-email" placeholder="e.g. student@email.com" /></div>
      <div class="field"><label>Year</label>
        <select id="f-year">
          <option value="">Select year</option>
          <option>Year 1</option><option>Year 2</option><option>Year 3</option><option>Year 4</option>
        </select>
      </div>
    </div>
    <div class="btn-row">
      <button class="btn-primary" onclick="addOrUpdate()">Save Student</button>
      <button class="btn-outline" onclick="clearForm()">Clear</button>
    </div>
  </div>

  <div class="table-wrap">
    <div class="table-header">
      <h2>📋 Student Records</h2>
      <div class="search-row" style="margin:0">
        <input id="search" placeholder="🔍 Search by name, ID or course..." oninput="renderTable()" />
        <button class="btn-outline" onclick="exportCSV()">Export CSV</button>
        <button class="btn-danger" onclick="clearAll()">Clear All</button>
      </div>
    </div>
    <div style="overflow-x:auto">
      <table>
        <thead>
          <tr>
            <th onclick="sortBy('id')">ID ↕</th>
            <th onclick="sortBy('name')">Name ↕</th>
            <th onclick="sortBy('course')">Course ↕</th>
            <th onclick="sortBy('year')">Year ↕</th>
            <th onclick="sortBy('grade')">Grade ↕</th>
            <th>Status</th>
            <th>Email</th>
            <th>Actions</th>
          </tr>
        </thead>
        <tbody id="table-body"></tbody>
      </table>
      <div class="empty" id="empty-msg" style="display:none">No students found. Add one above! 👆</div>
    </div>
  </div>

</div>

<div class="toast" id="toast"></div>

<script>
  let students = JSON.parse(localStorage.getItem('students') || '[]');
  let editingId = null;
  let sortKey = null;
  let sortAsc = true;

  const sampleData = [
    { id:'STU001', name:'Aisha Rahman', course:'Full Stack Development', grade:88, email:'aisha@mail.com', year:'Year 2' },
    { id:'STU002', name:'Rohan Mehta', course:'Data Science', grade:72, email:'rohan@mail.com', year:'Year 3' },
    { id:'STU003', name:'Priya Singh', course:'SQL & Databases', grade:55, email:'priya@mail.com', year:'Year 1' },
    { id:'STU004', name:'Liam Chen', course:'Web Design', grade:91, email:'liam@mail.com', year:'Year 4' },
    { id:'STU005', name:'Fatima Al-Zahra', course:'Cybersecurity', grade:43, email:'fatima@mail.com', year:'Year 2' },
  ];

  if (students.length === 0) { students = sampleData; save(); }

  function save() { localStorage.setItem('students', JSON.stringify(students)); }

  function getStatus(g) {
    if (g >= 75) return ['Pass', 'badge-pass'];
    if (g >= 50) return ['Average', 'badge-avg'];
    return ['Fail', 'badge-fail'];
  }

  function renderTable() {
    const q = document.getElementById('search').value.toLowerCase();
    let data = students.filter(s =>
      s.name.toLowerCase().includes(q) ||
      s.id.toLowerCase().includes(q) ||
      s.course.toLowerCase().includes(q)
    );

    if (sortKey) {
      data.sort((a, b) => {
        let av = a[sortKey], bv = b[sortKey];
        if (sortKey === 'grade') return sortAsc ? av - bv : bv - av;
        return sortAsc ? String(av).localeCompare(String(bv)) : String(bv).localeCompare(String(av));
      });
    }

    const tbody = document.getElementById('table-body');
    const empty = document.getElementById('empty-msg');

    if (data.length === 0) { tbody.innerHTML = ''; empty.style.display = 'block'; }
    else {
      empty.style.display = 'none';
      tbody.innerHTML = data.map(s => {
        const [label, cls] = getStatus(s.grade);
        return `<tr>
          <td>${s.id}</td>
          <td><strong>${s.name}</strong></td>
          <td>${s.course}</td>
          <td>${s.year}</td>
          <td><strong>${s.grade}%</strong></td>
          <td><span class="badge ${cls}">${label}</span></td>
          <td style="color:var(--muted);font-size:0.8rem">${s.email}</td>
          <td>
            <button class="action-btn" title="Edit" onclick="editStudent('${s.id}')">✏️</button>
            <button class="action-btn" title="Delete" onclick="deleteStudent('${s.id}')">🗑️</button>
          </td>
        </tr>`;
      }).join('');
    }
    updateStats();
  }

  function updateStats() {
    const total = students.length;
    const grades = students.map(s => s.grade);
    const avg = total ? Math.round(grades.reduce((a,b) => a+b, 0) / total) : null;
    const pass = students.filter(s => s.grade >= 50).length;
    const fail = total - pass;
    document.getElementById('stat-total').textContent = total;
    document.getElementById('stat-avg').textContent = avg !== null ? avg + '%' : '—';
    document.getElementById('stat-pass').textContent = pass;
    document.getElementById('stat-fail').textContent = fail;
  }

  function addOrUpdate() {
    const id     = document.getElementById('f-id').value.trim();
    const name   = document.getElementById('f-name').value.trim();
    const course = document.getElementById('f-course').value;
    const grade  = parseInt(document.getElementById('f-grade').value);
    const email  = document.getElementById('f-email').value.trim();
    const year   = document.getElementById('f-year').value;

    if (!id || !name || !course || isNaN(grade) || !email || !year) {
      showToast('⚠️ Please fill in all fields!'); return;
    }
    if (grade < 0 || grade > 100) { showToast('⚠️ Grade must be 0–100!'); return; }

    if (editingId) {
      const i = students.findIndex(s => s.id === editingId);
      students[i] = { id, name, course, grade, email, year };
      editingId = null;
      showToast('✅ Student updated!');
    } else {
      if (students.find(s => s.id === id)) { showToast('⚠️ ID already exists!'); return; }
      students.push({ id, name, course, grade, email, year });
      showToast('✅ Student added!');
    }
    save(); clearForm(); renderTable();
  }

  function editStudent(id) {
    const s = students.find(s => s.id === id);
    if (!s) return;
    document.getElementById('f-id').value = s.id;
    document.getElementById('f-name').value = s.name;
    document.getElementById('f-course').value = s.course;
    document.getElementById('f-grade').value = s.grade;
    document.getElementById('f-email').value = s.email;
    document.getElementById('f-year').value = s.year;
    editingId = id;
    window.scrollTo({ top: 0, behavior: 'smooth' });
    showToast('✏️ Editing student — make changes and save!');
  }

  function deleteStudent(id) {
    students = students.filter(s => s.id !== id);
    save(); renderTable(); showToast('🗑️ Student deleted!');
  }

  function clearForm() {
    ['f-id','f-name','f-grade','f-email'].forEach(i => document.getElementById(i).value = '');
    document.getElementById('f-course').value = '';
    document.getElementById('f-year').value = '';
    editingId = null;
  }

  function clearAll() {
    if (!confirm('Clear ALL student records?')) return;
    students = []; save(); renderTable(); showToast('🗑️ All records cleared!');
  }

  function sortBy(key) {
    if (sortKey === key) sortAsc = !sortAsc;
    else { sortKey = key; sortAsc = true; }
    renderTable();
  }

  function exportCSV() {
    const headers = ['ID','Name','Course','Year','Grade','Status','Email'];
    const rows = students.map(s => {
      const [label] = getStatus(s.grade);
      return [s.id, s.name, s.course, s.year, s.grade + '%', label, s.email];
    });
    const csv = [headers, ...rows].map(r => r.join(',')).join('\n');
    const a = document.createElement('a');
    a.href = 'data:text/csv,' + encodeURIComponent(csv);
    a.download = 'students.csv';
    a.click();
    showToast('📥 CSV exported!');
  }

  function showToast(msg) {
    const t = document.getElementById('toast');
    t.textContent = msg;
    t.classList.add('show');
    setTimeout(() => t.classList.remove('show'), 2500);
  }

  renderTable();
</script>
</body>
</html>
