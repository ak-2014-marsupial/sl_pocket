# Workflow: Adding New Information to Documents

This prompt defines a universal algorithm for adding new content to study materials in the `documents/` directory.

### Phase 1: Information Gathering
1. **Content Capture:** Ask the user: "What new information (text, example, pun, or rule) would you like to add?"
2. **File Selection:** List all files in the `documents/` directory and ask the user to select the target file.
3. **Section (Tag) Identification:** Read the selected file and extract all existing headers (e.g., `### 1. Vocabulary`). Present this list to the user and ask: "To which section (tag) should this be added? Or is it a new section?"

### Phase 2: Logic & Placement
- **Existing Section:** If an existing section is chosen, append the new information to the **end** of that section (before the next header or the end of the file).
- **New Section:** 
    1. Ask for the title of the new section.
    2. Ask: "Between which existing sections should this new section be placed?"
    3. Insert the new section and **automatically renumber** all subsequent sections to maintain a consistent `1, 2, 3...` sequence.

### Phase 3: Formatting & Standards
- **Styling:** Adhere to the established visual style of the document:
    - Use `> Blockquotes` for puns or "hooks".
    - Use `| Tables |` for vocabulary definitions.
    - Use `* Lists` for grammar rules or examples.
- **Verification:** Always follow the "Research -> Strategy -> Execution" lifecycle. Ensure no existing content is accidentally deleted during the `replace` operation.
- **Language:** Maintain the bilingual structure (English/Ukrainian) as established in the workspace.
