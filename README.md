Applicant Brief

A free, private, single-file form that turns your grades, tests, budget and goals into one brief you can paste into any AI to research universities and your chances of getting in.

Live demo: add your GitHub Pages link here

Why this exists

Ask an AI "which universities should I apply to?" with no context and you get a generic list. Give it your curriculum, scores, English-test status, budget and career goal, and the answers get specific.

Most applicants leave things out because they don't know what matters. This form asks for the details that change a university list, especially for international students:

Which exam system and grading context you come from
SAT/ACT and English-test status (including the Duolingo English Test) and any waiver you hold
How much your family can pay, and whether you need financial aid
Your career goal, so the AI can weigh recruiting pipelines and alumni networks, not just rankings
What you get

You fill in the form and it builds a brief live beside it. The brief has three parts:

Instructions for the AI (optional). They tell it to check each school's official admissions pages, mark anything it can't confirm as "not verified", give chances as ranges with reasons, label schools Reach, Target or Safety, and flag schools you probably can't afford.
Your profile, written as plain text, only with the sections you filled in.
What you want from the AI: tick boxes for a school list, test and English requirements, chances, aid, program comparisons, a deadline timeline and essay angles, plus your own question.

A "Not provided yet" list at the end shows the AI what you left blank, so it asks instead of guessing.

How to use it
Open the page and fill in what you can. Skip anything you don't know.
Click Copy brief.
Paste it into the AI of your choice and send it.
Check every requirement, score and deadline it gives you against the school's own admissions page before acting on it.
Privacy

Everything runs in your browser. There is no server, no account and no analytics. Your answers are saved only in your browser's local storage so you don't lose a draft, and Clear everything erases them. Leave out passport numbers, home addresses and phone numbers. An AI chat does not need them.

Run it locally

No build step and no dependencies. Download the repo and open index.html in a browser.

Host it on GitHub Pages
Push this repo to GitHub.
Go to Settings → Pages.
Under Build and deployment, choose Deploy from a branch, pick main and / (root), and save.
Your page appears at https://<your-username>.github.io/<repo-name>/ after a minute or two.
Customize it

All the questions live in one SECTIONS array near the top of the script in index.html. To change what the form asks:

Edit a field's l (label), ph (placeholder) or o (select options)
Add key: 'Label' to a field to count it toward the "key details" meter
Add a new object to SECTIONS to create a new section
Edit INSTR to change the instructions sent to the AI
Ideas for later
Import and export a profile as a file so it can move between devices
A version for transfer students and graduate applicants
Translations (French and Kinyarwanda first)
Country presets for exam systems (NESA, WASSCE, KCSE, A-levels, IB)
Contributing

Pull requests are welcome, especially for exam systems and countries the form doesn't cover well yet. Keep it a single static file with no dependencies.

Disclaimer

This tool formats information. It does not predict admission decisions, and AI answers can be wrong or out of date. Confirm test policies, English requirements, deadlines and financial aid with each university before you rely on them.
