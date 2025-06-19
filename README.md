<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Engly – Smart Search for English Teachers</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <header>
    <h1>Engly</h1>
    <p class="tagline">Built by teachers. Curated for classrooms.</p>
  </header>

  <main>
    <section class="search-area">
      <h2>Find the perfect activity, fast.</h2>
      <form id="search-form">
        <input type="text" id="search-input" placeholder="e.g. present simple, A2 listening..." />
        <div class="filters">
          <select id="cefr-filter">
            <option value="">CEFR Level</option>
            <option>A1</option>
            <option>A2</option>
            <option>B1</option>
            <option>B2</option>
            <option>C1</option>
            <option>C2</option>
          </select>

          <select id="age-filter">
            <option value="">Age Group</option>
            <option>Young Learners</option>
            <option>Teens</option>
            <option>Adults</option>
          </select>

          <select id="type-filter">
            <option value="">Material Type</option>
            <option>Worksheet</option>
            <option>Video</option>
            <option>Game</option>
            <option>Reading</option>
            <option>Speaking Activity</option>
          </select>

          <button type="submit">Search</button>
        </div>
      </form>
    </section>

    <section class="results">
      <h3>Sample Resources</h3>
      <ul id="results-list">
        <li>
          <strong>Present Simple Quiz</strong> (A2, Teens, Worksheet)  
          <p>A printable PDF quiz with 10 fill-in-the-blank questions. Ideal for review day.</p>
          <a href="#">Download</a>
        </li>
        <!-- Add more sample results here -->
      </ul>
    </section>

    <section class="feedback">
      <h4>Help shape Engly</h4>
      <p>Was this useful? What would you like to see next?</p>
      <form id="feedback-form">
        <textarea placeholder="Your thoughts..."></textarea>
        <button type="submit">Send Feedback</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2025 Engly. Built with ❤️ for English teachers everywhere.</p>
  </footer>
</body>
</html>
