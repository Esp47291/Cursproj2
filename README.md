# Курс-проект: интеграция с hh.ru

Мини-CLI, который подключается к публичному API hh.ru, 
сохраняет вакансии в JSON и позволяет сортировать их по зарплате.

## Установка

```bash
git clone <repo-url> && cd course_project
python -m venv .venv
source .venv/bin/activate      # Windows: .venv\Scripts\activate
pip install -e .[dev]          # prod + dev-зависимости