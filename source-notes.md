# Source notes for stavrosmavrommatis.com portfolio

Built from the source materials available locally on 2026-06-12.

## Files inspected

- `/Users/aiagent/OneDrive/00_inbox/cvs.zip`
  - Extracted and read the PDF CVs inside `02_2025/`.
  - Useful evidence: FilmPulse website/content/event work, MatchPoint/JA entrepreneurship, IB/education, HubSpot, Young Filmmakers.
  - Deliberately excluded DiL/DFG family-business material because it is not to be used as real employment for Stavros.
- `/Users/aiagent/OneDrive/00_inbox/pictures-of-me.zip`
  - Extracted three lecture photos and created editorial crops for hero/supporting images.
- `/Users/aiagent/OneDrive/00_inbox/pyxi.zip`
  - Downloaded from OneDrive, inspected archive listing, extracted key documents and visual deliverables.
  - Read: internship agreement, role description, weekly internship summaries, Culture Edit ownership plan, consultancy agreement.
  - Selected employer-safe visual proof from Culture Edit marketing, email, partner-app and Instagram story deliverables.
- `/Users/aiagent/OneDrive/00_inbox/IB.zip`
  - Downloaded full 14.87GB archive from OneDrive, inspected archive listing, selectively extracted Company Program, Visual Arts and Computer Science evidence.
  - Read MatchPoint business plan, JA/ESP support material, IB Visual Arts curatorial/process portfolio PDFs, and inspected a small visual contact sheet.
  - Decision: include IB as credible foundation and MatchPoint as an early entrepreneurship proof point; keep darker/immature visual art assets off the front page.
- `/Users/aiagent/OneDrive/Documents/Reference/jobs/stavros-mavrommatis-cv-general.html`
  - Used current Pyxi/Culture Edit proof points.
- `/Users/aiagent/OneDrive/Documents/Reference/jobs/london-job-goal-prompt-intake.md`
  - Used source profile, job-positioning lanes, strongest proof points, and current CV evidence.
- `/Users/aiagent/OneDrive/Documents/Reference/jobs/stavros-mavrommatis-cv-latest.pdf`
  - Copied into the site as the downloadable CV.
- `/Users/aiagent/OneDrive/00_inbox/BUSINESS OF THE CREATIVE INDUSTRIES.zip`
  - Waited for the 32.89GB OneDrive/rclone download to complete, verified the final local ZIP size matched the OneDrive remote size, and listed it with `unzip -l` into `/tmp/stavros-portfolio-source/boci_unzip_l.txt`.
  - Archive inventory: 1,051 employer-relevant/non-`__MACOSX` entries after ignoring `.DS_Store`, including 331 PDFs, 186 Pages packages, 134 JPGs, 51 PPTX files, 32 DOCX files, 19 MP4 files and 71 MOV files.
  - Selectively extracted 162 promising files into `/tmp/stavros-portfolio-source/business_creative_industries_selected` rather than unpacking the full archive. This included FilmPulse/Kaleidoscope group-project files, the final VFX/AI dissertation, YouthFlick business-plan files, marketing/branding essay evidence, creative leadership feedback, first-year AI content-pitch slides, and Off The Record production evidence.
  - Created BOCI visual triage sheets: `/tmp/stavros-portfolio-source/boci_pdf_contact_sheet.jpg`, `/tmp/stavros-portfolio-source/boci_image_contact_sheet.jpg`, and `/tmp/stavros-portfolio-source/boci_video_contact_sheet.jpg`.
  - Strongest additions used on the site: FilmPulse final presentation, FilmPulse brand/communications plan, 9,113-word VFX/AI dissertation cover, YouthFlick business-plan page, and first-year AI documentary pitch slide.
  - Useful supporting evidence read but not surfaced directly: FilmPulse individual report says Stavros handled marketing/content creation, domain setup, website drafting/maintenance, digital assets, presentation graphics and festival logistics; the VFX dissertation is titled `The Business of Visual Effects: How Studio Power, Unionization, and Emerging AI Threats Impact the Working Conditions and Recognition of VFX Artists`; the YouthFlick plan positions a creative film incubator with budget/milestone planning; creative leadership rubric feedback repeatedly marked the work as `Excellent`.
  - Deliberately excluded: Board of Examiners/private assessment documents, Turnitin receipts, raw rubrics/marked feedback as public artifacts, lecture decks and sample essays by other students, downloaded academic source PDFs, other students' portrait/contact-sheet images, raw `Off The Record` video/script assets, receipts, ethics forms, and anything with private/admin metadata.

## Strongest proof selected

- Pyxi / Culture Edit: launched from inception, curated 15+ events, drove 70 paid ticket purchases, £600+ in two months, worked across engineering/marketing/ops, managed acquisition campaigns, KPI/CPA/conversion reporting.
- Pyxi ownership-plan evidence: positioned Culture Edit as a growth/revenue driver; documented 2,953 total leads, 294 Culture Edit leads, 194 usable Culture Edit leads, 9 early experiences, 8-experience/month strategy, HubSpot email marketing, Meta ad tests, budget discipline, weekly dashboards and operational fixes.
- Pyxi ops internship: venue/partner/user comms, guest logistics, app testing, bug spotting, QR feedback process changes, Slack channel setup, CRM email setup, marketing automation, UGC/video editing, promotional stories and workflow standardisation.
- FilmPulse / University of York: marketing/content creation role, domain setup, website drafting and maintenance, digital assets/presentation graphics, festival logistics, screening and networking event with 50+ attendees, Screen Yorkshire partnership, and 3+ hours of documentary material organised.
- BOCI / research: 9,113-word final dissertation on studio power, unionisation, public perception and emerging AI threats in visual-effects work; YouthFlick creative film-incubator business plan with milestones, budget and launch sequencing; first-year AI documentary pitch demonstrating early interest in AI/media packaging.
- MatchPoint / Junior Achievement: IB-era student venture for finding sports venues and teammates; business plan evidence includes forecasted year-one net profit of €19,893.86 and breakeven at 8 sports centres, plus ESP/JA entrepreneurship context.
- IB Visual Arts / Computer Science: inspected as creative/technical foundation; strongest conclusion is breadth of early visual thinking and software/business exposure, not front-page visuals.
- Education: BA Business of the Creative Industries, University of York, 2:1; IB 39/45, 7/7 Business Management, Anatolia College.
- Certifications/tools: HubSpot Sales Hub, Excel, CRM/automation, reporting, Adobe/CapCut/Premiere, web/content systems.

## Design reference

Pinterest reference: AIYA Brand/Project Proposal Template.
Key style translated rather than copied:
- editorial one-page proposal feel;
- huge black uppercase section headers;
- cream/lavender background blocks;
- black testimonial band;
- thin micro-navigation labels;
- pill-shaped step labels;
- image grid with muted editorial photo treatment;
- large serif explanatory copy paired with heavy grotesk display type;
- purple accent adapted from the requested accent color.


## 2026-06-14 update

- User supplied `logos.zip`; extracted Pyxi, FilmPulse, University of York and MatchPoint logos.
- Normalised the supplied marks into same-size transparent PNG canvases, all white for the Work section: `assets/work-logo-pyxi.png`, `assets/work-logo-filmpulse.png`, `assets/work-logo-york.png`, `assets/work-logo-matchpoint.png`.
- Added Off The Record as a Study video sample using the full-length source video `/tmp/stavros-portfolio-source/off-record/off_the_record.mp4` (15:10.96). The site uses a web-optimised full-duration encode at `assets/off-the-record-full.mp4`, not a trimmed edit.
