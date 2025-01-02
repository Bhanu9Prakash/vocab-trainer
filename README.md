## Language Vocabulary Practice

A **single-page** application for managing languages, words, quizzes, and statistics with a user-friendly, **mobile-ready** interface. This app simulates a multi-page experience (home and language views) without requiring multiple HTML files.

### Features

1. **Add & Manage Languages**  
   - Create new languages, each with its own word list and stats.
   - Store **language-level notes** for easy reference.

2. **Word List & Tag System**  
   - Create words with foreign and English text, custom tags, and personal notes.
   - **Color-coded tags** for visual clarity, searchable and filterable.

3. **Quizzes (Multiple Modes)**  
   - **Multiple Choice** (Foreign → English)  
   - **Translation** (User-typed answers)  
   - **Bidirectional** (Randomly tests Foreign → English or English → Foreign)

4. **Statistics & Badges**  
   - Track practice streak, total sessions, average score, and category-wise accuracy.
   - Earn badges for milestones (e.g., 100 words, high accuracy, consistent practice).

5. **Responsive UI & Accessibility**  
   - Uses **CSS media queries** for mobile-friendly layout.  
   - **Focus trapping** in modals; `inert` attribute replaces `aria-hidden` to avoid accessibility conflicts.

6. **Data Persistence**  
   - Data stored in `localStorage`; can **export** and **import** as JSON.  
   - Per-language notes, words, stats, and tag colors remain consistent between sessions.

### Usage

1. **Open `index.html`** in your browser.  
2. **Create a Language** using the “Add New Language” form.  
3. **Click** the language card to open its view:
   - **Update Language Notes** in the **Language Notes** card.
   - **Add Words** with tags and notes.
   - **Search/Filter** words by tags or keywords.
   - **Start Practice** to quiz yourself in different modes.
4. **View Stats** for each language (streak, accuracy charts, badges).
5. **Export** or **Import** JSON data for backup or sharing.

### File Structure

- **`index.html`**  
  Contains all HTML, CSS, and JavaScript logic in one place.  
  - **Home/Menu View** and **Language View** are in separate `<div>` sections toggled via JavaScript.

### Contributing

Feel free to:
- Add more quiz modes (listening, writing, etc.).  
- Customize the UI, color scheme, or badge criteria.  
- Improve the logic for advanced stats or tag management.

