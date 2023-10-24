graph TD
  A[Start] -->|Clone| B(Git Clone)
  B -->|Branch| C(Git Checkout -b feature/branch_name)
  C -->|Work| D(Work, work, work)
  D -->|Stage| E(Git Add)
  E -->|Commit| F(Git Commit)
  F -->|Merge| G(Git Checkout develop; Git Merge feature/branch_name)
  G -->|Deploy| H(Git Push origin develop)
  H -->|End| I[End]
