frontend:
cd frontend
npm run dev

backend
cd backend  
uv init --bare
uv python pin 3.12
uv add -r requirements.txt
uv run uvicorn server:app --reload

if all oke just:
uv run uvicorn server:app --reload
