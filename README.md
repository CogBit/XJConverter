# XJConverter

![XJConverter](https://img.shields.io/badge/XJConverter-XML%20to%20JSON-blue)
![Platform](https://img.shields.io/badge/Platform-Windows-green)
![License](https://img.shields.io/badge/License-MIT-orange)

**XJConverter** is a lightweight command-line tool that converts **XML files to JSON files** quickly and efficiently.

---

## 🛠 Features

* Convert any well-formed XML file to JSON.
* Simple command-line usage — no GUI required.
* Specify output file path for JSON.
* Fast and reliable for small to medium-sized XML files.
* Preserves nested XML structures and attributes.

---

## 💻 Usage

Open a command prompt and run:

```bash
XJConverter.exe <InputXMLFile.xml> <OutputJSONFile.json>
```

### Example

```bash
XJConverter.exe sample.xml output.json
```

* `sample.xml` → The XML file you want to convert.
* `output.json` → The path and name of the resulting JSON file.

### Example Workflow with Full Paths

```bash
XJConverter.exe C:\Users\Name\Documents\data.xml C:\Users\Name\Documents\data.json
```

This converts `data.xml` to `data.json` in the same folder.

---

## ⚡ Requirements

* Windows OS (tested on Windows 10/11)
* .NET runtime installed (if required by your build)

---

## 📦 Download / Releases

You can download the latest release for **free** from [Gumroad](https://cogbit.gumroad.com/l/xjconverter).

> **Note:** XJConverter is completely free to use! You can support development if you want, but there is no cost to use the tool.

---

## 📖 How It Works

XJConverter parses the input XML file, converts its elements into JSON objects, and writes the result to the specified output path.

* Preserves nested structures.
* Handles XML attributes and elements correctly.

---

## 🔧 Tips

* Ensure your XML file is **well-formed** to avoid conversion errors.
* Use **full file paths** if files are in different directories.
* For large XML files, allow extra time for parsing.

---

## 💡 Optional Command-Line Flags (Future Enhancements)

* `-v` → Verbose mode for detailed logs
* `-i` → Ignore specific XML nodes
* `-p` → Pretty-print JSON output

---

## 📬 Feedback & Support

If you encounter issues, have questions, or want new features, please open an **issue** in this repository.

---

## 📣 Support & Donations

If you like this tool and want to support development:

* [Support on Gumroad (optional)](https://cogbit.gumroad.com/l/xjconverter)

> XJConverter itself is completely free!

---

Feel free to copy this into your GitHub repository's `README.md` file. If you need assistance with setting up your GitHub repository or have any other questions, feel free to ask!
