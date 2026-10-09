# studyPilot
A web app for students to upload unit materials and then ask questions, answered with cited responses, auto-generate quizzes and review flashcards on a spaced-repetition schedule.


studyPilot is a production RAG web app for university students to query their
course materials.

It makes scrolling through hundreds of lecture slides and notes easier,
as they can instead get notes, flashcards and quizzes with cited, source-backed answers

Some of the primary features include Semantic hybrid search, auto-generated
quizzes, and spaced-repetition flashcards

The core tech stack includes FastAPI, PostgreSQL with pgvector, Redis background workers,
Claude API, and React

It has been built with automated evaluation harnesses, infrastructure as Code and CI/CD pipelines.