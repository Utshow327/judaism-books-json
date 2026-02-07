

# Judaism JSON Dataset

Tanakh datraset,A structured, machine-readable version of the **Tanakh** (Hebrew Bible). This repository provides the sacred scriptures of Judaism in a JSON format, designed for developers building apps for study, liturgy, or academic research.

## 📜 About the Tanakh

The Tanakh is an acronym derived from the names of its three divisions:

1. **T**orah (Instruction/Law)
2. **N**evi'im (Prophets)
3. **K**etuvim (Writings)

This dataset includes the complete collection of 24 books, organized for easy parsing and integration.

---

## 🚀 Usage

### CDN Access

You can fetch the data directly into your web application using the following CDN link:

```text
https://cdn.jsdelivr.net/gh/Traves-Theberge/sacred-scriptures-mcp@main/data/tanakh.json

```

### Data Structure

The JSON is structured hierarchically to allow for easy navigation through books and chapters:

```json
{
  "book": "Genesis",
  "chapters": [
    {
      "chapter_number": 1,
      "verses": [
        { "verse_number": 1, "text": "..." }
      ]
    }
  ]
}

```

---

## 🛠 Features

* **Format:** Pure JSON.
* **Organization:** Divided by the traditional three sections (Torah, Nevi'im, Ketuvim).
* **Accessibility:** Ready for use in React, Vue, Python, or any modern development environment.



## 👋 Contributing

Contributions are welcome! If you find a typo in the text or an error in the JSON structure, please open an Issue or submit a Pull Request.

---

Would you like me to help you write a specific **License** file (like MIT or CC0) to go along with this README?
