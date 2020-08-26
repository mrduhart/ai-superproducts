- Sources
  - https://ckaestne.github.io/seai/F2019/slides/03_se_bootcamp/se.html#/

- Importance of process
  - Innovative (modern software) vs routine (established software), both need a **process: activities + results -> product**
  - A simple process (is it?)
    1. Discuss software to write
    2. Code
    3. Test: find issues
    4. Debug: find causes
    4. Fix
    5. Repeat (or end)
  - Process + coding + rework not linear
    - No process -> lots of trashing, lots of process eventually (by the end)
    - More process at beginning -> less trashing, less process by the end - survival mode
    - Earlier defects are more costly to correct later

- Automation
  - Routine is automated to avoid repetition
    - Copy/paste -> method -> lib
    - Common problems & SW -> frameworks
    - Data gathering -> list comprehension -> DB queries
    - ...
  - Version control is great
    - History, robustness, collaboration, clean files
    - Make good commits
    - Release management
    - Track source, docs, and configs (no generated files or private info)
  - Docs
    - Great code should not need it
      - Descriptive method & variable names
      - Constants vs magic numbers
    - ...but makes it better
      - Rationale vs code repetition
      - API interfaces
  - Builds
    - Command line steps -> scripts -> build tools
    - Test in other machines
  - Quality
    - Dynamic: Manual testing -> unit testing & coverage -> CI & CD
    - Static: Code inspection -> static analysis / formal verification
    - Process
  - Issue tracking
    - Manual -> tracking systems -> AI
    - Measurement: when, who, what, difficulty
    - Communication and accountability

- Planning, requirements, and design
  - Planning is everyting, the plan is nothing
    - Iterate and replan when something changes
    - Practice and calibration to estimate effort - IT IS DIFFICULT!
    - Milestones with objective deliverables vs progress estimates
  - Requirements
    - What vs how
    - Hard to establish and rectify, wrong requirements ruin result (Fred Brooks)
    - Functional vs **Quality (guide tradeoff)**
    - Remember qualities? Use, product, process
  - Measurement
    - Rule from model / theory -> numbers -> properties
    - Observations -> less uncertainty
    - Everyting is measurable: X is important -> X is detectable -> X is detectable in some amount -> X is measurable
    - Learn -> build -> measure: goal -> question -> metric (SCIENCE!!!)
  - Design
    - **Make tradeoff decisions (core of software engineering)**
    - Constraints, priorities, analysis w/o implementation

- Software lifecyles: Agile (vs stupid waterfall)
  - Phases: requirements, design, implementation, testing, maintenance
  - Waterfall: obsolete, bad at risk, too linear
  -
