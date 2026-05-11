# Contributing to NoraCivilis

Thank you for your interest in contributing to **NoraCivilis – A Civilization Operating System**.  
This project is built on a modular architecture with dozens of independent cognitive, strategic, and structural engines.  
To keep the system coherent and maintainable, please follow the guidelines below.

---

## 🧩 Project Structure

Each engine lives in its own directory and must follow these rules:

- Each engine must export a clear and documented interface.
- No engine should directly depend on another engine unless defined in the architecture map.
- All engines must return structured JSON outputs.
- All reasoning, memory, and strategy modules must be deterministic and reproducible.

---

## 🛠 How to Contribute

### 1. Fork the repository
Create your own fork and work on a separate branch.

### 2. Create a new branch
Use a descriptive name:
### 3. Follow the coding style
- Use clear function names.
- Add comments for all exported functions.
- Keep files small and modular.
- Avoid unnecessary dependencies.

---

## 🧪 Testing

Before submitting a pull request:

- Ensure your engine runs without errors.
- Validate JSON output format.
- Test integration with the core engine (if applicable).

---

## 📤 Submitting a Pull Request

Your PR must include:

- A clear description of the change.
- The engine(s) affected.
- Example input/output.
- Any architectural impact.

PRs that break the structure or naming conventions will be rejected.

---

## 🧭 Roadmap Alignment

If your contribution adds a new engine, ensure it aligns with the **NoraCivilis Roadmap**.  
Engines must fit into one of the following layers:

- Identity Layer  
- Mission Layer  
- Reasoning Layer  
- Memory Layer  
- Strategy Layer  
- Oversoul Layer  
- Abstraction Layer  

If unsure, open an Issue before coding.

---

## 🤝 Code of Conduct

Be respectful, constructive, and collaborative.  
This project is built for long-term evolution and requires clean, thoughtful contributions.

---

Thank you for helping build the future of **Civilization Operating Systems**.
