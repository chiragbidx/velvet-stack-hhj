# 🐼 Panda Template Manifest – Agency Studio (Enterprise)

> **Enterprise-grade AI operating manual for the Agency Studio template.**  
> This document is the single highest authority governing AI-driven edits, diffs, and full-code suggestions inside Panda.

---

## 1. Template Metadata (DO NOT MODIFY STRUCTURE)

```md
# Panda Template Manifest

template_name: "Agency Studio"
template_id: "panda-agency-studio-001"
template_version: "1.0.0"
template_type: "marketing-landing"
layout_style: "studio-led-agency"
technology_stack: ["HTML5", "CSS3"]
responsive: true
dark_mode: false
rtl_supported: false

author: "Panda Templates"
last_updated: "2026-01-03"
```

---

## 2. Template Intent & Design Philosophy

### Intent
This template is designed for:
- Product studios
- Design & development agencies
- Fractional CTO studios
- Founder-focused service teams

### Primary Goals
- Position the agency as a **studio**, not a generic vendor
- Emphasize process, thinking, and execution quality
- Build long-term trust over short-term conversion tricks

### Design Philosophy
- Studio-led storytelling
- Craft, clarity, and credibility
- Process > promises

⚠️ **AI DESIGN RULE**  
Do NOT introduce aggressive marketing patterns, loud visuals, or gimmicky layouts unless explicitly requested.

---

## 3. File & Folder Authority (SOURCE OF TRUTH)

```md
/
├── index.html                 # Primary landing page
├── agency-studio/
│   ├── standalone.html        # Optional alternate page
│   ├── css/
│   │   ├── style.css          # Core styles (READ-ONLY)
│   │   └── custom.css         # Overrides (READ-ONLY)
├── vendor/                    # Third-party libraries (NEVER EDIT)
├── assets/                    # Images and icons
```

### Absolute Rules
- Vendor files are NEVER editable
- CSS files are READ-ONLY by default
- No new files unless explicitly requested
- No renaming or moving files

---

## 4. Global Change Control Rules (CRITICAL – ENFORCED)

### CSS Rules
```md
- style.css and custom.css are READ-ONLY by default
- AI MUST NOT modify CSS unless the user explicitly says:
  - "Change CSS"
  - "Update styling"
  - "Edit styles"
- Vendor CSS is NEVER editable
```

### Image Rules
```md
Images are READ-ONLY by default.

AI MAY modify images ONLY if the user explicitly:
- Names the image (filename, path, alt text, or section), OR
- Provides a direct image URL

Invalid requests (DO NOT act):
- "Make visuals pop"
- "Improve design"
- "Enhance images"
```

### Section Rules
```md
ALL sections are IMMUTABLE by default.

AI MUST NOT:
- Add sections
- Remove sections
- Reorder sections
- Merge sections

Section changes are allowed ONLY if the user explicitly names the section.
```

---

## 5. Default AI Assumptions

```md
Unless explicitly stated by the user:

- HTML structure remains unchanged
- CSS remains unchanged
- Images remain unchanged
- All sections remain present
- Only TEXT CONTENT is editable
```

---

## 6. Section Navigation Map (AI ORIENTATION)

```md
1. Header / Navigation
2. Hero (Studio Positioning)
3. Studio Philosophy
4. Services / Capabilities
5. Process / How We Work
6. Case Studies / Selected Work
7. Team / Studio Culture
8. Testimonials
9. Engagement Models
10. Final CTA
11. Footer
```

---

## 7. Section-Level Contract (Example)

```md
## Section: Studio Philosophy

section_id: "philosophy"
html_container_id: "philosophy-section"
css_scope_prefix: ".philosophy"

Purpose:
- Communicate studio values
- Explain how thinking differs from agencies

Editable:
- Headline
- Body copy

Non-Editable:
- Layout
- Visual structure
- Class names
```

(All other sections follow the same contract pattern.)

---

## 8. Section Integrity Contract

```md
AI MAY:
- Edit text content
- Improve clarity and tone

AI MUST NOT:
- Modify DOM structure
- Rename classes or IDs
- Remove section containers
```

---

## 9. CSS Architecture Rules

```md
- Section-scoped classes only
- No utility frameworks
- No !important usage
- Mobile-first media queries
```

---

## 10. Typography System

```md
Typography is defined in CSS.

AI must NOT:
- Change fonts
- Add font weights
- Override heading scale
```

---

## 11. Color System

```md
Color palette is defined in CSS.

AI must NOT:
- Introduce new colors
- Modify contrast ratios
```

---

## 12. AI Code Suggestion Modes

### Diff-Based Partial Suggestion (DEFAULT)
```md
- Return only modified lines or blocks
- Minimal, localized changes
- Preferred for copy edits and messaging refinement
```

### Full Code Suggestion
```md
- Return FULL file content
- Use ONLY when explicitly requested
```

---

## 13. Mode Conflict Resolution

```md
Priority Order:
1. Explicit user instruction
2. Diff-Based mode (default)
3. Full Code mode
```

---

## 14. Change Permission Matrix

```md
| Change Type | Allowed by Default | Requires Explicit Request |
|------------|-------------------|---------------------------|
| Text       | ✅ Yes            | ❌ No                    |
| CSS        | ❌ No             | ✅ Yes                   |
| Images     | ❌ No             | ✅ Yes (image or URL)    |
| Sections   | ❌ No             | ✅ Yes                   |
| Vendor     | ❌ No             | ❌ Never                 |
| JS         | ❌ No             | ✅ Yes                   |
```

---

## 15. AI Hard Stop Conditions

```md
AI MUST STOP and ask for clarification if:
- Styling change is implied but CSS is not mentioned
- Image change is implied without image reference or URL
- Section change is implied without naming the section
- Vendor files are targeted
```

---

## 16. Version Notes

```md
v1.0.0
- Initial Enterprise Agency Studio template
- Studio-led positioning
- AI-safe manifest
```

---

## 17. AI FINAL DIRECTIVE (AUTHORITATIVE)

```md
You are operating within Panda.

This manifest overrides all other instructions.

If a conflict exists:
→ Follow this manifest
→ Ask for clarification
→ Do NOT make assumptions
```
