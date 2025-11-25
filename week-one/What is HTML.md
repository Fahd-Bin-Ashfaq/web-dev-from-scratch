
---

## 1. What is HTML?

**HTML (HyperText Markup Language)** is the standard language used to **structure content on the web**.

> **Real-Life Analogy:**  
> HTML = Structure of a house (walls, rooms, doors)  
> CSS = Decoration & paint  
> JavaScript = Electricity & appliances

---

## 2. HTML Tags

**Definition:** HTML tags tell the browser **how to display content**.

**Syntax:**
```html
<tagname>Content</tagname>
```
**Example:**
```html
<p>Hello World!</p>
```

---

## 3. Types of HTML Tags

### 3.1 Text Formatting Tags
| Tag      | Purpose                  | Real-Life Example              |
|----------|-------------------------|-------------------------------|
| `<h1>`-`<h6>` | Headings             | Page titles, article headings |
| `<p>`    | Paragraph               | Blog text, descriptions       |
| `<b>` / `<strong>` | Bold text       | Important notice              |
| `<i>` / `<em>` | Italic text       | Quotes, emphasis              |
| `<br>`   | Line break              | Address formatting            |
| `<hr>`   | Horizontal line         | Section separation            |

---

### 3.2 Container Tags
| Tag         | Purpose                       | Real-Life Example |
|-------------|-------------------------------|-----------------|
| `<div>`     | Generic block container       | Website layout   |
| `<span>`    | Inline container              | Highlight words  |
| `<section>` | Section of a page             | Services section |
| `<article>` | Independent content piece     | Blog post        |
| `<header>`  | Top section of a page         | Website header   |
| `<footer>`  | Bottom section of a page      | Contact info     |
| `<main>`    | Main content                  | Main article area|
| `<nav>`     | Navigation links              | Menu bar         |
| `<aside>`   | Sidebar content               | Ads or related links |

---

### 3.3 Link & Media Tags
| Tag       | Purpose                     | Real-Life Example           |
|-----------|-----------------------------|-----------------------------|
| `<a>`     | Hyperlink                  | Go to another webpage       |
| `<img>`   | Image                      | Profile picture             |
| `<video>` | Video                      | YouTube video               |
| `<audio>` | Audio                      | Podcast or music player     |
| `<iframe>` | Embed other webpage        | YouTube embedded video      |

---

### 3.4 Lists
| Tag      | Purpose                          | Example                     |
|----------|---------------------------------|-----------------------------|
| `<ul>`   | Unordered list                  | Grocery list                |
| `<ol>`   | Ordered list                    | Step-by-step tutorial       |
| `<li>`   | List item                       | Each item in a list         |

---

### 3.5 Tables
| Tag      | Purpose                          | Example                     |
|----------|---------------------------------|-----------------------------|
| `<table>` | Table container                | Student marks table         |
| `<tr>`    | Table row                      | Each student’s row          |
| `<td>`    | Table cell / data              | Individual marks            |
| `<th>`    | Table header                   | Column names                |
| `<thead>` | Table header section           | Top row                     |
| `<tbody>` | Table body section             | All rows of data            |
| `<tfoot>` | Table footer section           | Total / summary row         |

---

### 3.6 Forms
| Tag       | Purpose                          | Example                     |
|-----------|---------------------------------|-----------------------------|
| `<form>`  | Form container                  | Contact us form             |
| `<input>` | Input field                     | Name, email, password       |
| `<textarea>` | Multi-line input              | Message box                 |
| `<button>`  | Submit button                  | Send / submit button        |
| `<label>`   | Label for input                | Name: / Email:              |
| `<select>`  | Dropdown menu                  | Country selection           |
| `<option>`  | Option inside dropdown         | Pakistan, USA, India        |

**Input types to know:** text, email, password, number, checkbox, radio, file, submit.

---

## 4. Attributes You Must Know
- `id` — unique identifier  
- `class` — group multiple elements  
- `style` — inline CSS  
- `href` — link URL  
- `src` — image/video/audio source  
- `alt` — alternative text for images  
- `title` — tooltip  
- `value` — default value for input  
- `placeholder` — hint text for input  
- `type` — input type (text, email, password, etc.)  

---

## 5. Semantic vs Non-Semantic Tags

### Semantic Tags
- Describe **meaning of content**  
- Better for **SEO & accessibility**  
- Examples: `<header>`, `<footer>`, `<nav>`, `<section>`, `<article>`, `<main>`, `<aside>`  

**Example:**
```html
<header>
  <h1>My Website</h1>
</header>
<nav>
  <ul>
    <li>Home</li>
    <li>About</li>
  </ul>
</nav>
```

### Non-Semantic Tags
- **No meaning**, used only for layout  
- Examples: `<div>`, `<span>`  

**Example:**
```html
<div>
  <div>My Website</div>
  <div>Navigation menu</div>
</div>
```

---

## 6. Real-Life Beginner Questions (With Answers)

**Q1:** What is the difference between `<b>` and `<strong>`?  
**A:** `<b>` = bold only, `<strong>` = bold + semantic importance  

**Q2:** Difference between `<i>` and `<em>`?  
**A:** `<i>` = italic, `<em>` = italic + emphasizes meaning  

**Q3:** Can HTML run without CSS?  
**A:** Yes, CSS just makes it visually appealing  

**Q4:** Difference between `<div>` and `<span>`?  
**A:** `<div>` = block (new line), `<span>` = inline (same line)  

**Q5:** Why use `<alt>` in `<img>`?  
**A:** For accessibility & if image fails to load  

**Q6:** Difference between `<ul>` and `<ol>`?  
**A:** `<ul>` = bullets, `<ol>` = numbers  

**Q7:** What is a semantic tag?  
**A:** Tags that describe **the meaning** of content  

---

## 7. Real-Life Examples

- **Blog page:** `<header>`, `<article>`, `<footer>`  
- **Portfolio:** `<section>` for skills, `<div>` for layout  
- **E-commerce product page:** `<img>` for product photo, `<a>` for links, `<button>` for add-to-cart  

---

## 8. Beginner Tips

- Always **close your tags** properly  
- Use **semantic tags** whenever possible  
- Indent nested tags for clarity  
- Practice by creating **mini webpages** like:  
  - Personal bio page  
  - Hobby page  
  - Product table  
  - Simple contact form  

---

# 📝  Practical Exercises

---

## 1️⃣ Text Formatting Tags  
**Tags:** `<h1>-<h6>`, `<p>`, `<b>`, `<i>`, `<br>`, `<hr>`  

### **Practice Questions**

1. **Create a Personal Intro Page**  
   - Use `<h1>` for your main heading (e.g., Your Name)  
   - Use `<h2>` for a subheading (e.g., Your Profession)  
   - Add a paragraph `<p>` introducing yourself  
   - Make one word **bold** (`<b>`) and one word *italic* (`<i>`) inside the paragraph  

2. **Line Breaks & Horizontal Line**  
   - Use `<br>` to separate sentences in your paragraph  
   - Add `<hr>` to separate heading and paragraph  

3. **Mini Blog Post (Challenge)**  
   - Write a paragraph about your favorite hobby  
   - Use `<h3>` for the hobby name  
   - Make one sentence bold and one italic  

---

## 2️⃣ Lists & Links  
**Tags:** `<ul>`, `<ol>`, `<li>`, `<a>`  

### **Practice Questions**

1. **Unordered List**  
   - Create a list of 5 of your favorite foods using `<ul>` and `<li>`  

2. **Ordered List**  
   - Create a step-by-step guide for making tea using `<ol>` and `<li>`  

3. **Links**  
   - Add a link to your favorite website using `<a href="">`  
   - Make the link open in a new tab using `target="_blank"`  

4. **Combined Exercise**  
   - Create a small webpage about your daily routine  
   - Use `<h2>` for the title  
   - Add an ordered list of your daily tasks  
   - Add a link to a website you use every day  

---

## 3️⃣ Images & Attributes  
**Tags:** `<img>` with `src`, `alt`, `title`  

### **Practice Questions**

1. **Profile Picture**  
   - Add an image of your choice using `<img>`  
   - Add an `alt` text describing the image  
   - Add a `title` that shows on hover  

2. **Gallery Exercise**  
   - Create a mini image gallery with 3 images  
   - Add proper `alt` and `title` for each image  

3. **Combined Practice**  
   - Create a webpage about your favorite movie  
   - Add the movie poster using `<img>`  
   - Add a paragraph with `<p>` describing the movie  
   - Make the movie title bold and italic inside the paragraph  

---

> ✅ **Tip for Beginners:**  
> - Always close your tags correctly  
> - Test your webpage in a browser after every change  
> - Use semantic names in your file like `index.html`  

