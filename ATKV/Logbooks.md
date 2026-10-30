<style>
.reflection-card {
  position: relative;
  border-radius: 18px;
  overflow: hidden;
  background: radial-gradient(circle at top, rgba(66, 185, 131, 0.14), transparent 55%), linear-gradient(180deg, #ffffff 0%, #f8fafc 100%);
  border: 1px solid #e5e7eb;
  box-shadow: 0 40px 70px -50px rgba(15, 23, 42, 0.9);
  margin: 2rem 0;
}

.reflection-card-content {
  position: relative;
  z-index: 1;
  display: flex;
  flex-direction: column;
  gap: 16px;
  padding: 32px;
}

.reflection-header {
  display: flex;
  align-items: flex-start;
  justify-content: space-between;
  gap: 18px;
}

.reflection-title-group {
  display: flex;
  flex-direction: column;
  gap: 6px;
}

.reflection-subtitle {
  text-transform: uppercase;
  letter-spacing: 7px;
  font-size: 10px;
  color: #94a3b8;
}

.reflection-title {
  font-size: 26px;
  font-weight: 700;
  color: #0f172a;
}

.reflection-index {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  width: 48px;
  height: 48px;
  border-radius: 14px;
  background: linear-gradient(135deg, #42b983 0%, #527d7a 100%);
  color: #ffffff;
  box-shadow: 0 24px 50px -24px rgba(66, 185, 131, 0.95);
}

.reflection-table {
  width: 100%;
  border-collapse: separate;
  border-spacing: 0;
  border-radius: 14px;
  overflow: hidden;
  border: 1px solid #e2e8f0;
  background: #ffffff;
}

.reflection-table thead th {
  text-align: left;
  padding: 14px 22px;
  background: linear-gradient(90deg, rgba(66, 185, 131, 0.12) 0%, rgba(248, 250, 252, 1) 100%);
  color: #0f766e;
  font-weight: 700;
  text-transform: uppercase;
  letter-spacing: 6px;
  font-size: 10px;
}

.reflection-table tbody tr:not(:last-child) td {
  border-bottom: 1px solid #f1f5f9;
}

.reflection-table tbody td {
  padding: 18px 22px;
  color: #475569;
  line-height: 1.9;
  vertical-align: top;
}

.reflection-table tbody td:first-child {
  width: 140px;
  font-weight: 700;
  color: #1e293b;
}
</style>

<div class="reflection-card">
  <div class="reflection-card-content">
    <div class="reflection-header">
      <div class="reflection-title-group">
        <span class="reflection-subtitle">ATKV</span>
        <h2 class="reflection-title">Agile Logbooks – Reflection</h2>
      </div>
      <div class="reflection-index">
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" fill="none" viewBox="0 0 24 24" stroke-width="1.8" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" d="M12 6.042A8.967 8.967 0 006 3.75c-1.052 0-2.062.18-3 .512v14.25A8.987 8.987 0 016 18c2.305 0 4.408.867 6 2.292m0-14.25a8.966 8.966 0 016-2.292c1.052 0 2.062.18 3 .512v14.25A8.987 8.987 0 0018 18a8.967 8.967 0 00-6 2.292m0-14.25v14.25"/></svg>
      </div>
    </div>
    <table class="reflection-table">
      <thead>
        <tr>
          <th>Element</th>
          <th>Reflection</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Situation</td>
          <td>Throughout the ATKV project, I had to keep track of my daily work, tasks completed, blockers, and contributions to the team. The logbook was used to record this consistently.</td>
        </tr>
        <tr>
          <td>Task</td>
          <td>My task was to update my logbook daily with accurate information about what I worked on, what I learned, any challenges I faced, and how I worked with the team.</td>
        </tr>
        <tr>
          <td>Action</td>
          <td>At the end of each working day, I reviewed what I had done and recorded it in the logbook. I noted the tasks I completed, any blockers I encountered, the steps I took to resolve them, and what I planned to do the next day.</td>
        </tr>
        <tr>
          <td>Result</td>
          <td>Keeping the logbook helped me stay accountable and organised. It allowed me to track my progress over time, reflect on what I was learning, and have accurate records to refer to during stand-ups and reviews. It also helped me see how much I was growing throughout the project.</td>
        </tr>
      </tbody>
    </table>
  </div>
</div>
