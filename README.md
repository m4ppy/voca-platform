# voca-platform

A lightweight, personal vocabulary management and learning platform.

Voca Platform helps users organize English vocabulary with Korean meanings and practice memorization through simple vocabulary tests.

The project starts as a local application, with plans to support web deployment in the future.

## Features

### 1. Vocabulary Management
- Add, edit, and delete English words.
- Store Korean meanings for each word.
- Assign parts of speech (noun, verb, adjective, adverb, etc.).
- Support multiple meanings for a single word.
- View and manage saved vocabulary.

### 2. Vocabulary Groups
- Create custom vocabulary groups.
- Add and remove words from groups.
- Organize vocabulary by topic, purpose, or study session.

### 3. Vocabulary Test
- Generate vocabulary tests from selected groups.
- Display only one language at a time:
  - **English → Korean:** Show an English word and recall its Korean meanings.
  - **Korean → English:** Show a Korean meaning and recall the English word.
- Reveal the answer to check memorization.

## Vocabulary Structure

Each vocabulary entry contains:

| Field | Description | Example |
|---|---|---|
| Word | English vocabulary | document |
| Part of Speech | Grammatical category | Verb, Noun |
| Meanings | Korean definitions | 기록하다, 문서 |
| Groups | Assigned vocabulary groups | TOEIC, Business |

A word can have multiple parts of speech, each with its own meanings.

## Development Roadmap

### v0 — Local MVP
- [ ] Vocabulary CRUD
- [ ] Multiple meanings and parts of speech
- [ ] Vocabulary group management
- [ ] English-to-Korean vocabulary tests
- [ ] Korean-to-English vocabulary tests
- [ ] Local data persistence

### Future
- [ ] Web deployment
- [ ] User authentication
- [ ] Cloud data synchronization
- [ ] Vocabulary test history and progress tracking
- [ ] Additional learning features

## Tech Stack

The initial implementation will prioritize simplicity, lightweight architecture, and ease of maintenance.

react ts + node js

## Project Status

**v0 — Prototype**

Currently designed for personal use and local development.

## License

No license specified.
