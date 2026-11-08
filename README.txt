Sarthi - Magic Bus Mobilization Assistant (Mankhurd Centre)
===========================================================

HOW TO OPEN
Double-click index.html. It opens in any modern web browser on a phone,
tablet, or desktop computer. Sarthi is fully self-contained in a single
offline-native file with zero external dependencies, CDN links, or libraries.

CORE CAPABILITIES & RECENT ENHANCEMENTS
---------------------------------------

1. "Today" Mobilizer Home Screen
   - Default route (#today) tailored for morning field mobilization.
   - Four large quick-action cards: Take attendance, Log a visit by voice,
     Follow-ups due, and Message a guardian.
   - Shows today's scheduled community sessions and top 3 urgent follow-ups.
   - Full Supervisor Dashboard accessible anytime from the menu.

2. Visual Dashboard & Inline SVG Charts
   - Four lightweight, responsive SVG charts drawn without external libraries:
     * Attendance Trend Line per community over recent sessions
     * Risk-Level Donut breakdown (High, Medium, Low, Dropped)
     * Community Coverage Strips (Active, At-risk, Dropped proportions)
     * Monthly Enrolment and Retention bar chart
   - Responsive scaling down to 320px phone viewports.
   - Accessible screen-reader text summaries underneath each chart.

3. Child Profile Cards
   - Redesigned beneficiary cards in People view (#people):
     * Circular initials avatar with Magic Bus theme colors
     * Bold name, WCAG AA status badge, and risk level pill
     * Community pocket, program track, and preferred outreach language
     * Mini 8-session attendance strip with trend label
     * Real-time "Contacted X days ago" counter
     * One-tap quick action buttons: Call, Message, Add note, Dropout/Reinstate
     * Expandable one-tap history with past session dates and engagement notes timeline.

4. Gentle Motion & Animation (< 300ms)
   - Snappy 200ms screen transition fade when navigating routes.
   - Popping checkmark feedback animation on saving notes, attendance, or beneficiaries.
   - Smooth card and accordion open/close transitions.
   - Full @media (prefers-reduced-motion: reduce) compliance turns off all animations.

5. First-Use Walkthrough & Screen Help
   - Guided 3-step walkthrough modal explaining Today, Voice log, and the Risk board.
   - Step dots indicator, Skip, Previous, and Next/Finish controls.
   - Automatically shown on first visit; accessible anytime via the Help icon in the top header.
   - Screen-level help icons next to every title provide a two-line explanation of each screen.

6. Offline & Demo Status Banners + Action Queue
   - Top notification banner bar:
     * "Demo mode": Clear banner explaining local browser storage
     * "Offline mode": Auto-detects network disconnection; actions are queued
     * "Sync complete": Confirms queued actions synced when connection is restored
   - Background offline action queue records operations when disconnected and syncs on reconnect.

7. Simplified 5-Group Navigation & Mobile FAB
   - Desktop sidebar organized into 5 intuitive groups:
     Home, People, Field work, Plan, and Reports.
   - Clean 5-item bottom navigation bar on mobile phones.
   - Floating Action Button (FAB) on phones with quick actions (Voice log, Feedback, Attendance),
     automatically hidden on Attendance and Voice screens.

8. Fast Attendance Marker
   - "Mark all present" and "Clear all" buttons for rapid single-tap logging.
   - High-contrast card toggle rows with clear Present/Absent status pills.
   - Real-time running tally ("14 of 18 present").
   - Confirmation summary dialog before saving attendance.
   - Past session date preservation maintains chronological integrity.

9. Step-by-Step Guided Forms
   - 3-step wizards with progress indicators for Add Beneficiary, Log Feedback, and Add Community.
   - Essential fields first, secondary fields behind step 2, and review summary before submission.

10. Multilingual Interface Switcher
    - One-tap language toggle in header: English (EN), हिन्दी (Hindi), and मराठी (Marathi).
    - Persistent language preference saved in browser storage.
    - Centralized translations dictionary (T_UI) covering all menus, labels, and help tooltips.

SCREENS
-------
Today (#today), Supervisor Dashboard (#dashboard), Beneficiaries (#people),
Communities (#communities), Take Attendance (#attendance), Risk Board (#risk),
AI Comms (#messages), Session Planner (#planner), Field Map (#team),
Voice Log (#field), Feedback (#feedback), Knowledge Base (#kb), Reports (#reports).

DATA & PRIVACY
--------------
All sample names, mobile numbers, and community pockets in Mankhurd are demonstration
placeholders. Festival dates in the timing check are fixed approximations; confirm before
scheduling community workshops.
