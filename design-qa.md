# Programme detail redesign QA

final result: passed

Source: /workspace/scratch/innovation-reference-clean.jpg, Harvard Innovation Strategy course page.
Implementation: /workspace/scratch/escp-course-comparison.jpg and /workspace/scratch/escp-faculty-redesign.jpg.
Combined comparison: /workspace/scratch/programme-layout-comparison.jpg. Both desktop captures 1348 x 926 pixels, same browser viewport, normalized to 674 x 463 each for composition comparison. Top-of-page state, overlays closed. Mobile responsive rendering inspected in a 390 x 844 iframe (375 CSS px content width after scrollbar), no horizontal overflow.

Typography: large sans-serif title, tight leading, consistent heading hierarchy and readable body. ESCP navy and existing Arial are intentional brand adaptations. Layout: split title/media hero, rounded enrolment bar, two-column overview, outcome cards, syllabus accordions and portrait faculty section. Composition matches the supplied reference direction; the shorter ESCP copy and direct contact card intentionally replace Harvard copy/email collection.
Colors: ESCP navy/light blue replaces Harvard crimson/orange. Contrast and visible focus styles retained.
Assets: subject imagery retained for programmes per user preference. Fourteen real portraits downloaded from official ESCP sources; identities and programme relationships tracked in faculty-sources.json. Portraits displayed at 160px to avoid unnecessary upscaling. Geopolitics faculty remains explicitly unannounced. Additional named contributors without verified portraits remain text only.
Copy: ESCP programme information and official application links retained. No Harvard biographies, testimonials or dates copied. No invented faculty portraits.

Interactions verified in browser: section navigation, opening a syllabus module, opening CPF FAQ, video modal and close, source and application link targets. Embedded Vimeo playback is blocked in this cloud browser; a direct official-programme fallback link was added. Console inspection found extension metadata errors only, no page script error in inspected logs. Nine source pages checked for JavaScript syntax and local assets/links.

Comparison history: first top reference capture contained a timed email overlay; dismissed and recaptured before comparison. Initial large faculty portraits magnified low-resolution sources; corrected to compact circular portraits and inspected again. Remaining differences are intentional ESCP branding/content choices. No actionable P0/P1/P2 issue remains.

Follow-up P3: supply faculty confirmation/portraits for forthcoming Geopolitics and remaining industry contributors when available. No mobile reference screenshot was captured; mobile adaptation checked for usability rather than exact reference fidelity.
