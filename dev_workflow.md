# Development Workflow

**Updated:** _Sun, 6 Oct 2019_

## Roles

- Bootcamp Organizers
- NGO stakeholders
- Product Lead
- Tech Lead
- UI/UX Designers
- Dev Coaches
- Curriculum Coaches

## Development Team Organization

1. **REACH Front-End Team**
    - 2x Coaches
    - 2x Participant

2. **UN Women Front-End Team**
    - 2x Coaches
    - 2x Participants

3. **Donation Management System Backend Team**
    - 2x Coaches
    - 2x Participants

## Iteration Planning Meeting (IPM)

- **Period:** Every 2 weeks (1 hour)
- **Participants:**
    - NGO stakeholders
    - Product Lead
    - Tech Lead
    - Dev Coaches
    - Bootcamp participants
    - UI/UX Designers (optional)

- **What:**
    - Go through user stories prioritized for this iteration by Product Lead (in consultation with NGO stakeholders & Tech Lead).
    - Product Lead to share about the requirements, acceptance criteria (what's in scope) and what's out of scope.
    - User Story Estimation - estimate complexity of work needed with a number scale.

## Coding Sessions

- **Period:** Every week (whole day & during weekdays (as needed))
- **Participants:**
    - Dev Coaches
    - Bootcamp participants
- **What:**
    - Form a development pair (1 coaches + 1 participant).
    - Development pair picks up next user story from the Trello board.
    - Talk to Product Lead if they needed more details about the business context.
    - Talk to Tech Lead if they needed more details on the tech / architecture considerations.
    - Move Trello story card from **`Scheduled`** to **`Started`** column.
    - Create a `feature` branch (I recommend using the Trello card number as the prefix).
    - Write test & code. Repeat as many times as needed.
    - Make sure to make as many Git commit to feature branch as needed.
    - Push to GitHub repo as often as you can.
    - When done with the feature, create a Pull Request from the `feature` branch to `master` branch.
    - Code review with Tech Lead or other coaches.
    - Tech Lead or other coaches approves the PR and merges the branch to `master`.
    - `master` branch merge should kick off a Continuous Integration / Continuous Delivery (CI/CD) pipeline to deploy the code to `staging` environment.
    - Move Trello story card from **`Started`** to **`Finished`** column.

## Story Review & Acceptance

- **Period:** As needed when during the Bootcamp sessions
- **Participants:**
    - Product Lead
    - Tech Lead
    - Dev Coaches
    - Bootcamp participants
    - NGO stakeholders (optional)
- **What:**
    - When user stories are done, Product Lead can review the feature once they are deployed to staging.
    - Backend stories are accepted by the front-end devs / coaches
    - Front-end stories are accepted by the Product lead / NGO stakeholders

## Level-Up Workshop

- **Period:** Every 2 weeks (1.5 hours)
- **Participants:**
    - Curriculum Coaches
    - Bootcamp participants
    - Dev Coaches (optional)

- **What:**
    - These are the topics that we feel that the Bootcamp participants should learn to help prepare them for building the Donor Management App for the NGOs. These could be CS fundamentals, data structures or basic knowledge they will need in writing the NodeJS applications.

## Retrospective

- **Period:** Every 4 weeks (1 hour)
- **Participants:**
    - NGO stakeholders
    - Product Lead
    - Tech Lead
    - Dev Coaches
    - UI/UX Designers
    - Bootcamp participants

- **What:**
    - After a number of iterations (sprint), we usually wind down the period of intense product development with a “Retrospective”.
    - Its a kind of post-mortem / evaluation on the sprint.
    - This is a good time to make mid-course corrections in your project and processes.
    - Allow your team to understand each other’s working style better.
    - **Retro Prime Directive:**

        > "Regardless of what we discover, we understand and truly believe that everyone did the best job they could, given what they knew at the time, their skills and abilities, the resources available, and the situation at hand."
    - We fill up a board with post-its on these 3 columns:
        - 😀 - What went well? What pleases you?
        - 🙁 - What didn’t go so well? What made you unhappy?
        - 😑 - What confuses you? Questions you might still have?
        - 📝 - Action Items - What we should do about these ideas?

    - **Process:**
        - Each person take a post-it pad & marker.
        - Take next 10 minutes and jot down thoughts and comments for each of the 3 columns. One post-it for each thought.
        - Stick on Retro Board together. We’ll group similar post-its.
        - Go through together and you are encouraged to discuss freely.
        - Distill out action items as we go along.

## Timeline (Tentative)

| Week | Date        | Program  |
|:----:|-------------|:---------|
| 1    | 19 Oct 2019 | Kick-off, Setup (repo & CI/CD), Workshop 1 |
| 2    | 26 Oct 2019 | IPM, Workshop 2, Coding Session |
| 3    | 2 Nov 2019  | Coding Session |
| 4    | 9 Nov 2019  | IPM, Workshop 3, Coding Session |
| 5    | 16 Nov 2019 | Retro, Coding Session |
| 6    | 23 Nov 2019 | IPM, Workshop 4, Coding Session |
| 7    | 30 Nov 2019 | Coding Session |
| 8    | 7 Dec 2019  | IPM, Workshop 5, Coding Session |
| 9    | 14 Dec 2019 | Retro, Coding Session |
| -    | 21 Dec 2019 | Holiday Break |
| -    | 28 Dec 2019 | Holiday Break |
| 10   | 5 Jan 2020  | IPM, Workshop 6, Coding Session |
| 11   | 11 Jan 2020 | Coding Session |
| 12   | 18 Jan 2020 | IPM, Workshop 7, Coding Session |
| 13   | 25 Jan 2020 | Retro, Coding Session |
