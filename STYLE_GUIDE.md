# Educational Documents Style Guide (Standard v1.0)

This guide defines the mandatory structure and formatting for English learning documents in the `@documents/` folder. Use this as a reference for generating or refactoring content.

---

## 🎯 General Principles
*   **Target Level:** Pre-Intermediate / Intermediate.
*   **Tone of Voice:** Professional, supportive, and focused on "Polite English" (softeners).
*   **Languages:** Headlines and English content (definitions, examples) are in **English**. Explanations and translations are in **Ukrainian**.
*   **Formatting:** Use standard GitHub-Flavored Markdown.

---

## 🏗 Document Structure (The Template)

Every document MUST follow this exact section order:

### 1. Title
`# [Lesson Title]` (e.g., `# 01. Connecting with Others`)

### 2. Vocabulary & Definitions
`## 1. Vocabulary & Definitions`
A markdown table with three columns:
| Word/Phrase | Definition in English | Переклад |
| :--- | :--- | :--- |
| **Term** | Simple English explanation | Український переклад |

### 3. Vocabulary Hooks (Optional)
`## 2. Vocabulary Hooks`
Use blockquotes (`>`) for mnemonic sentences or interesting quotes from the lecture.
> **Example Hook:** "It is rude to be selfish..."

### 4. Grammar Essentials
`## 3. Grammar Essentials`
*   **Focus:** Formulas and clear usage rules.
*   **Structure:**
    *   **Formula:** `Subject + Verb + ...`
    *   **Usage:** When to use this rule (in Ukrainian).
    *   **Examples:** Use italics for examples (*Example: I am living in Canada now.*).

### 5. Written Practice
`## 4. Written Practice`
*   Show completed exercises from the slides.
*   Use bold for the answers within sentences.
*   *Example:* 1. How are you **doing**?

### 6. Speaking & Discussion Guide
`## 5. Speaking & Discussion Guide`
*   Question followed by tiered "Polite Style" responses.
*   **Q: [Question]?**
    *   **Positive:** "Actually, I'd say..."
    *   **Neutral:** "To be honest, it depends..."
    *   **Negative:** "I'm afraid I don't..."

### 7. Professional Scenarios (Dialogues)
`## 6. Professional Scenarios`
*   Short dialogues (Context + Script).
*   **Role A:** "Text..."
*   **Role B:** "Response using grammar/vocabulary from the lesson."

### 8. Polite English Cheat Sheet
`## 7. Polite English Cheat Sheet`
A summary table of "softeners" specific to the topic.
| Phrase / Softener | When to use it (Context) |
| :--- | :--- |
| **Actually** | To correct someone gently or add info. |

---

## 🛑 Rules for AI (Prompting Instructions)
1.  **No Chitchat:** Do not add introductory or concluding remarks (e.g., "Here is your document").
2.  **Surgical Edits:** Maintain existing content while adjusting it to this structure.
3.  **Strict Markdown:** Ensure all tables are properly aligned and headers use the correct level (`#`, `##`, `###`).
4.  **Formatting:** Always use **bold** for keywords and *italics* for example sentences.
