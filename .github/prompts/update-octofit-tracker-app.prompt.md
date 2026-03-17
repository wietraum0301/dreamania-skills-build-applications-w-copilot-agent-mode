mode: 'agent'
model: GPT-5.3-Codex

# Django 앱 업데이트

- 모든 Django 프로젝트 파일은 `octofit-tracker/backend/octofit_tracker` 디렉터리에 있습니다.
- MongoDB 연결 및 CORS를 위해 `settings.py`를 업데이트합니다.
- users, teams, activities, leaderboard, workouts 컬렉션을 지원하도록 `models.py`, `serializers.py`, `urls.py`, `views.py`, `tests.py`, `admin.py`를 업데이트합니다.
- `/`가 API를 가리키고, `urls.py`에 `api_root`가 있는지 확인합니다.
