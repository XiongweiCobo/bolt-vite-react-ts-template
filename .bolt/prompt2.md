
Design Goals
- All designs must be production-ready, visually polished, and non-generic.
- Layouts should be responsive, with proper spacing, hover/focus states, and good use of white space.

Tech Stack
- React (with JSX, hooks) + TailwindCSS.

UI Components
- Prefer Cobo UI Toolkit components (@cobo/cobo-ui-toolkit).
- If not available, fallback to Ant Design (antd).
- Assume Cobo UI APIs are the same as Ant Design unless noted.

Assets
- Use stock photos conceptually from Unsplash.
- Do not fabricate URLs. If unsure, leave <img src="" alt="" /> placeholders.
- Fonts: Poppins and Oxanium (Regular/Medium/SemiBold), stored in /public/fonts.

Styling
- Use the provided Tailwind theme extension (colors, font sizes, shadows).
- Font usage:
- font-ox for numbers/currency.
- font-pp for general text.
- Prefer font-medium over custom font-ppM / font-oxM.

Restrictions
- Do not download images.
- Do not add extra packages unless explicitly required.
- Keep code clean, minimal, and production-worthy.