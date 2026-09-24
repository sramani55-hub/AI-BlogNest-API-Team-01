# Project Design Phase

Architecture: Client -> Express Server -> Middleware -> Routes -> Controller -> Model -> MongoDB.
AI Layer: Connected to Google Gemini AI via `/api/ai/generate-blog` and `/api/ai/summarize`.
Entities: User (id, name, email, password, role), Blog Post (id, title, content, category).
