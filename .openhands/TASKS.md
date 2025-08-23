# Task List

1. 🔄 Makefile and hooks: complete transition to uvx poetry run
Clean up PHONY; ensure no stale references
2. 🔄 Frontend hooks/scripts
Switch frontend/.husky/pre-commit to uvx poetry run
3. 🔄 Evaluation scripts migration (phase 1)
Replace 'poetry run' with 'uvx poetry run' in evaluation scripts
4. 🔄 Docs migration (phase 1): introduce uv-first commands
Update docs to use uvx poetry run for commands
5. 🔄 CI workflows migration (phase 1): use uvx poetry run
Install uv in workflows and run poetry via uvx

6. 🛠️ Fix pre-commit migration mode warning
Run: pre-commit install -f --hook-type pre-commit
