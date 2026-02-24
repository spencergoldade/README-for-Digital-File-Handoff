# About this digital design handoff template

This document is a **template** for handing off digital, product, and UX/UI design work to developers and other collaborators. It includes more detail and sections than you will typically use on a single project.

You are **not** expected to complete every section. Treat this as a menu: select the sections that are relevant for the product you’re shipping, remove the rest, and customize the language so it fits your team and tools.

It is intentionally provided to you in plain text so it can be accessible to clients and collaborators.

## Common ways to adapt this template:
- Strip it down to a lightweight handoff note for small features.
- Keep only the sections that align with your workflow (for example, “Design system & standards,” “Assets & exports,” and “Recommended testing”).
- Clone and maintain a studio-specific version so your team has a consistent, opinionated starting point.
- Fork, remix, etc.

## Project Overview
**Project Title:** [PROJECT_TITLE]
**Client/Organization:** [CLIENT_NAME]
**Designer/Studio:** [DESIGNER_OR_STUDIO_NAME]
**Primary Contact:** [DESIGNER_CONTACT_NAME]
**Email:** [DESIGNER_EMAIL]
**Slack/PM Channel (if applicable):** [CHANNEL_NAME_OR_URL]
**Date Prepared:** [DATE]

**Project Summary:**
[SHORT_DESCRIPTION_OF_PRODUCT_AND_SCOPE
E.G. "Responsive marketing site, key flows for signup, login, and dashboard."]

## Deliverable Summary
This package contains design deliverables intended for DIGITAL use
(web, mobile, or product UI), including source files and exportable
assets for implementation.

**Product / platform(s):**
- [WEB / IOS / ANDROID / DESKTOP / OTHER]
- **Supported breakpoints or platforms:** [E.G. MOBILE, TABLET, DESKTOP]

**Design stage:**
- [DISCOVERY WIREFRAMES / HI-FI VISUAL DESIGN / PRODUCTION-READY / DESIGN SYSTEM]

## Software & Access Requirements
Some files require specific tools or accounts to view or inspect
properly.

**Primary design tools used:**
- [E.G. Figma – VERSION, TEAM/ORG NAME]
- [Sketch – VERSION]
- [Adobe XD – VERSION]
- [Other: E.G. After Effects, Illustrator]

**Handoff / inspection tools:**
- Developers should use [FIGMA DEV MODE / ZEPLIN / ABSTRACT / OTHER]
  to inspect spacing, typography, colors, and exportable assets.

**Links and access:**
- **Main design file:** [URL_TO_MAIN_DESIGN_FILE]
- **Prototypes (if separate):** [URL_1], [URL_2]
- **Design system / component library:** [URL_TO_LIBRARY]
- **Documentation / spec doc:** [URL_TO_CONFLUENCE_NOTION_ETC]

**Note:**
- Some native/source files may not open correctly without the listed
  software or appropriate plan/access.
- For implementation, the online handoff/inspection links above
  should be considered the source of truth.

## Information Architecture & Flows
**High-level IA:**
- **Primary navigation structure:** [BRIEF_DESCRIPTION_OR_LINK_TO_SITEMAP]
- **Key sections / modules:** [LIST_OR_LINK]

**User flows covered in this handoff:**
- [FLOW_NAME] – [BRIEF_DESCRIPTION] – [ENTRY_POINT → EXIT_POINT]
- [FLOW_NAME] – [BRIEF_DESCRIPTION]
- [ADD_OR_REMOVE_LINES_AS_NEEDED]

**Flow documentation:**
- **User flow diagrams:** [URL_OR_FILE_REFERENCE]
- **Edge/empty/error states are documented for:**
  [LIST_OF_FLOWS_OR "SEE ANNOTATIONS IN DESIGN FILE"]

## Design System & Standards
**Design system:**
- **System name:** [DESIGN_SYSTEM_NAME]
- **Location:** [LINK_TO_LIBRARY_OR_FILE]
- **Status:** [MVP / IN_PROGRESS / MATURE]

**Tokens / styles:**
- **Color styles defined and applied across screens:** [YES/NO/MIXED]
- **Text styles defined and applied:** [YES/NO/MIXED]
- **Spacing and layout tokens (if any):** [BRIEF_NOTES]

**Component library:**
- **Core components:** [BUTTONS, INPUTS, MODALS, CARDS, NAVIGATION, ETC.]
- **States included:** [DEFAULT / HOVER / ACTIVE / DISABLED / ERROR / LOADING]
- **Platform considerations:** [WEB / IOS / ANDROID / OTHER]

## Accessibility & Content Notes
**Accessibility:**
- **Target guidelines:** [E.G. WCAG 2.1 AA, PLATFORM-SPECIFIC GUIDES]
- **Color contrast checked for key text and UI elements:** [YES/NO]
- Focus states and keyboard navigation considered (web): [YES/NO]
- Screen reader / semantic considerations documented here:
  [LINK_OR_NOTES]

**Copy:**
- **Source of approved copy:** [COPY_DOC_LINK / CMS_LINK]
- **Status:** [FINAL / REQUIRES_COPY_REVIEW]
- **Localization / translation considerations:**
  [E.G. "Designed to support long German labels up to X chars."]

## File Structure & Naming
**File naming convention:**
- **Pattern:** [PROJECT_KEY]_[FEATURE]_[PLATFORM]_v[VERSION]
  e.g. MARKETING_SIGNUP_WEB_v1.2

**Structure inside design tool:**
- **Pages/sections:**
  - [01 – FOUNDATIONS (COLORS, TYPE, GRID)]
  - [02 – COMPONENTS]
  - [03 – FLOWS – SIGNUP]
  - [04 – FLOWS – ACCOUNT]
  - [05 – EXPERIMENTS / ARCHIVE]

**Versioning:**
- **Current version:** [vX.Y]
- **Previous major versions archived in:** [FOLDER_OR_LINK]

## Assets & Exports
**Exportable assets included:**
- **Icon set:** [FOLDER_ORCOMPONENT_SET_NAME, FORMAT (SVG/PNG/WEBP)]
- **Logos/brand marks:** [FOLDER_ORCOMPONENT_SET_NAME]
- **Illustrations/imagery:** [FOLDER_ORCOMPONENT_SET_NAME]

**Export details:**
- **Default export format for implementation:**
  [E.G. SVG FOR ICONS, PNG OR WEBP FOR IMAGERY, 1X/2X SCALES]
- **Asset naming convention:**
  [E.G. icon/16/primary-button__[STATE] ]

If developers need additional export sizes or formats:
- Please request via [PREFERRED_CHANNEL] so we can update the
  design source rather than editing exports manually.

## Implementation Guidance
**Intended implementation details:**
- **Target tech stack / framework:**
  [E.G. REACT + TAILWIND, SWIFTUI, ANDROID JETPACK COMPOSE]
- **Layout grid assumptions:**
  [E.G. 12-COLUMN GRID, 8PX BASE SPACING]
- **Supported browsers/devices (as discussed with devs):**
  [TARGET_BROWSERS_AND_MINIMUM_OS_VERSIONS]

**Interaction notes:**
- Animations, transitions, and micro-interactions are documented in:
  [LINK_TO_ANIMATIONS_PAGE_OR_PROTOTYPE]
- **Error, empty, and loading states are documented for:**
  [LIST_OF_KEY_COMPONENTS_OR_FLOWS]

## Recommended Testing Before Release
To reduce implementation issues and mismatches, the following tests
are strongly recommended before launch:

Design vs. build review:
- **Compare implemented screens against:**
  [LINK_TO_FINAL_DESIGN_FILE/PROTOTYPE]
- Conduct a joint review session with design + dev to resolve
  discrepancies.

**Cross-device / cross-browser checks:**
- **Test on agreed target browsers and OS versions:**
  [LIST_OF_TARGETS]
- **Verify responsive behavior at key breakpoints:**
  [E.G. 360PX, 768PX, 1024PX, 1440PX]

**Functional and interaction checks:**
- **Validate that all flows listed above are:**
  - Reachable from expected entry points.
  - Handling edge/error/empty states as designed.

**Accessibility checks:**
- **Run basic automated checks and spot checks with:**
  [E.G. LIGHTHOUSE, AXE, PLATFORM_SPECIFIC_TOOLS]
- Validate keyboard navigation and focus states (web).
- Validate minimum tap target sizes and readable text (mobile).

**Performance and content:**
- Confirm that images are optimized and appropriate formats are used.
- Confirm all copy, numbers, and legal text are up to date and approved.

## Usage, Modification & Maintenance
**Source of truth:**
- The following is considered the current source of truth for design:
  [LINK_TO_PRIMARY_DESIGN_FILE_OR_DOC]

**Future changes:**
- Any changes to UX, visuals, copy, or flows after this handoff
  should be:
  - Discussed with [DESIGNER_OR_TEAM_NAME], and
  - Reflected back into the design source to avoid drift.

**Third-party modification:**
- Direct modification of design files by third parties may result
  in inconsistencies or lost components. Where possible, please
  request changes through the design team.

## Limitation Of Liability & Disclaimer
By using these design files and documentation, the client and
implementation team acknowledge and agree to the following:

- The designer has provided digital design deliverables and guidance
  based on the requirements, constraints, and information supplied
  at the time of the project.

- The client and/or their implementation team are responsible for:
  - Ensuring the designs are implemented correctly in code and
    adapted to their technical stack, infrastructure, and data.
  - Performing appropriate functional, security, performance,
    accessibility, and compliance testing before release.
  - Reviewing and approving the final implemented product prior
    to launch.

- **The designer does not guarantee:**
  - That the implementation will be free from defects, security
    vulnerabilities, or compatibility issues in all environments.
  - Specific business outcomes (e.g. conversion lifts, revenue,
    engagement) resulting from the use of these designs.

- To the maximum extent permitted by applicable law, the designer
  is not liable for:
  - Any indirect, incidental, special, consequential, or punitive
    damages arising from the use, implementation, or misuse of
    these deliverables.
  - Costs associated with rework, code changes, delays, outages,
    or lost data arising after this handoff.

- If any issues are discovered during development or testing,
  the client agrees to notify the designer promptly so that
  adjustments can be discussed in good faith (which may be
  subject to a separate scope and fee).

This README does not replace a formal services contract or
master services agreement. Parties should refer to their signed
agreement for full legal terms.

## Version History
**Version:** [V1.0]
**Date:** [DATE]
**Prepared by:** [DESIGNER_NAME]

**Change log:**
- [DATE] – [SUMMARY_OF_CHANGES]
- [DATE] – [SUMMARY_OF_CHANGES]
