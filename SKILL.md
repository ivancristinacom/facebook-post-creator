---
name: facebook-post-creator
description: Generates structured Facebook posts using a Dual Engine (Curated Teaser & Long-Form Deep Dive). Enforces mandatory bold headlines, dynamic multilingual localization, a 6-pillar editorial, legal, algorithmic compliance protocol, and an interactive visual concept generation gate.
---
# Facebook Post Creator (Dual Engine, Full Compliance, Multilingual & Interactive Visual Generation)

## Description
This skill generates structured Facebook posts across any domain utilizing a Dual Engine architecture. It strictly enforces a comprehensive 6-Pillar Compliance Protocol to protect against copyright infringement, algorithmic penalties, and factual hallucinations (Strict Grounding), while dynamically adapting to the user's conversation language. It also enforces a strict hierarchical layout starting with an authoritative headline, creates a tailored image concept, and implements an interactive human-in-the-loop gate before image generation.

## 🔀 1. Dual Engine Model: Format Routing
- **Mode A: Curated Teaser (Protective Summary):** For external links/videos. Max 3 bullet points, rigorous synthesis, explicit link to the original resource to drive traffic.
- **Mode B: Long-Form Deep Dive (Comprehensive Narrative):** For original thoughts/internal reflections. Unrestricted length, narrative depth (paragraphs), optional link. Expressive freedom applies ONLY to storytelling, never to inventing facts.

## 🛡️ 2. Editorial, Legal, Algorithmic & Visual Compliance Protocol (6 Pillars)
1. **Fair Use & Substantial Re-elaboration:** Extract ONLY "bare facts" (data, dates, events, public quotes) from third-party sources. Never copy the narrative structure, tone, or expressive synthesis of copyrighted articles. CC BY-NC-SA 4.0 applies to outbound original text, not as a shield for plagiarism.
2. **Hierarchical Fact-Checking (Anti-Echo Chamber):** Prioritize primary sources (official documents, press releases, technical standards). If data is only found on secondary aggregators, express explicit caution or exclude it.
3. **Logical Input Validation (Beyond Grammar):** Validate the substance of the user prompt before correcting syntax. If the prompt contains historically or technically false premises, flag the factual incongruence instead of stylistically polishing an error.
4. **Reputational Security (Brand & Privacy Guard):** Maintain objective neutrality. Mention third-party brands only for reporting purposes without implying unauthorized partnerships. Anonymize internal or sensitive corporate data.
5. **Meta Policy (Anti-Algorithmic Penalty):** No "Engagement Bait" (e.g., do not ask "Like or share"). The first comment question must be organic. If maximizing reach is required, omit external links in the main body and place them exclusively in the first comment.
6. **Visual Compliance & Interactive Approval Gate:** The visual concept must avoid registered trademarks, fake UI elements (e.g., play buttons), or clickbait metaphors. Image generation MUST NOT trigger automatically; the agent must always provide the visual concept/prompt and explicitly ask for user confirmation before executing any image generation tool.

## 🌐 3. Dynamic Language, Label Localization & Hierarchical Structure
The generated post MUST strictly respect this sequential order and match the language used in the prompt/chat. Default to Italian if ambiguous.

1. **Title / Headline (Mandatory - First line):**
   - Generate an engaging, authoritative title summarizing the core topic.
   - Must be formatted in **bold text**.
   - NEVER use Markdown `#` headers (as Facebook does not render them natively).
2. **Localized Header:**
   - IT: `📍 Luogo: [Città, Regione/Provincia, Nazione]` | `📅 Data: [Mese AAAA]`
   - EN: `📍 Location: [City, Region/Province, Country]` | `📅 Date: [Month YYYY]`
3. **Post Body:**
   - Execute Mode A (Teaser) or Mode B (Long-form) content here.
   - If covering the skill's capabilities, include both editorial logic and visual curation.
   - Media Labels (Mode A only):
     - IT: `🎬 Servizio video completo ([Fonte]):` / `📄 Articolo completo ([Fonte]):`
     - EN: `🎬 Full video report ([Source]):` / `📄 Full article ([Source]):`
4. **Localized Footer & Signature:**
   - IT: `Curato con il supporto di Gemini (AI) e revisionata da **ivancristina.com**`
   - EN: `Curated with the support of Gemini (AI) and reviewed by **ivancristina.com**`
   - **Source Attribution:**
     - IT: `🔗 **Fonte originale:** ...`
     - EN: `🔗 **Original source:** ...`
   - **First Comment Tip:**
     - IT: `💡 **Consiglio per il primo commento:**`
     - EN: `💡 **Tip for the first comment:**`

## 🔍 4. Domain Lexicon
- Naturally adopt the technical jargon and specialized vocabulary of the targeted industry (e.g., DevOps, escapement, terroir) in the target language.

## 🎨 5. Visual Concept & Interactive Image Approval Gate (Mandatory)
After generating the post, output a dedicated visual concept section in English:
- **Aspect Ratio:** Specify `4:5` (mobile feed) or `1:1` (square).
- **Style:** Modern editorial aesthetic, clean layout, no clichés (no gears, circuit boards, fishhooks).
- **Text Constraint:** Instruct: "Render only the exact headline text. Do not add any other words, names, dates, times, locations, contact details, or placeholder fields."
- **Interactive Approval Rule:** Conclude by asking the user for explicit confirmation before generating the image (e.g., asking if they approve the concept or want style modifications). Do not execute the image generation tool autonomously.