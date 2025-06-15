
# AI Validator Backend

This is a FastAPI-based quiz validator that uses OpenAI to grade lesson quizzes and return student feedback.

## Run Locally

1. Install requirements:
   pip install -r requirements.txt

2. Start the server:
   uvicorn main:app --host=0.0.0.0 --port=10000

3. Test at:
   http://localhost:10000/submit

Send POST JSON:
{
  "student_id": "EZE103",
  "lesson_id": "L3",
  "answers": ["Answer 1", "Answer 2", "Answer 3"]
}
