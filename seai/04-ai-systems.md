- Sources
  - https://ckaestne.github.io/seai/S2020/slides/05_system/systems.html
  - https://ckaestne.github.io/seai/F2020/slides/02_systems/systems.html
  - https://ckaestne.github.io/seai/F2019/slides/02_components/components.html

- AI is NOT for everyting
  - Complex patterns & environment and large data
  - Weigh risks

- AI systems are more than just models
  - Pipeline + infrastructure + user
  Systems-view (the big picture): components + interactions + environment = behavior - (system dynamics)

- Challenges
  - Lack of modularity & specifications
  - Data mess (collect, clean, process, manage)
  - All of the SE practices (versioning, debugging, deployment, teams)

- Components
  - Goal (objective, purpose)
  - Intelligent experience
  - Intelligence creation
  - Intelligence implementation
  - Intelligence orchestration

- Goal: the purpose of the system's existence (not the model)
  - Measurable: SET METRICS!
  - Achievable: Is this really possible?
  - Communicable: Explain this to your grandma
  - Compared to model accuracy
    - Is good enough good enough?
    - AI critical or gimmick?
    - Can experience fix it?
    - Other qualities...

- Experience: it's a balance
  - Present intelligence: do > ask > rank > suggest / notify
    - How forceful?
    - How often?
    - How useful?
    - How costly?
  - Collect data (telemetry)
    - Context
    - User actions
    - Outcome
    - Frequency, value, cost (as above)
  - Contain error impact
    - External failsafes > hard constraints > model
    - Influence (or restrict) user behavior
    - Be less forcecul, guidance for recovery

- Implementation and orchestration: it's still software
  http://papers.nips.cc/paper/5656-hidden-technical-debt-in-machine-learning-systems.- pdf
