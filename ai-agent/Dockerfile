FROM python:3.11-slim
WORKDIR /app
RUN apt-get update && apt-get install -y git && rm -rf /var/lib/apt/lists/*
RUN pip install uv

# Direct packages install karein kyunki pyproject.toml nahi hai
RUN uv pip install --system "fastapi" "uvicorn" "httpx" "python-dotenv" "openai-agents"

COPY . .

# Networking & Path Fix
ENV BACKEND_URL=http://todo-backend:8000
ENV PYTHONPATH=/app

EXPOSE 8001
CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8001"]`