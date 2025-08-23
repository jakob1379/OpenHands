# Task List

1. ✅ Makefile and hooks: complete transition to uvx poetry run
PHONY uses check-uv; pre-commit basic checks use uvx poetry
2. ✅ Frontend hooks/scripts: switch husky to uvx poetry run
frontend/.husky/pre-commit updated
3. ✅ Evaluation scripts migration (phase 1)
Replaced poetry run python -> uvx poetry run python; READMEs updated
4. ✅ Docs migration (phase 1): introduce uv-first
Development.md, docs/usage/**, tests/*/README.md updated
5. 🔄 CI workflows migration (phase 1): use uvx poetry
Commands migrated, added astral-sh/setup-uv; still some references in resolver prompts/runtime templates/containers README
6. ✅ Fix pre-commit migration mode warning
pre-commit install -f executed; hooks passing
