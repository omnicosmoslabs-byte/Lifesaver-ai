# Architecture / Arquitetura

How Lifesaver-ai is organised today.

Como o Lifesaver-ai está organizado hoje.

## Structure / Estrutura

- `skills/`: the four modules, each in its own folder with a `SKILL.md` file
- `security/`: security policy, threat model, privacy policy, checklist and incident response
- `docs/`: guides and project information
- `SECURITY.md`, `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `CHANGELOG.md`: project rules and history

## Modules / Módulos

| Module / Módulo | Purpose / Objetivo |
|---|---|
| Document Guardian | Understand documents and spot risky clauses |
| Scam Detector | Recognise scams, fake messages and fraud |
| Money Protector | Protect money and avoid financial traps |
| Global Helper | Everyday safety questions, anywhere in the world |

## How a skill works / Como funciona uma skill

A skill is a Markdown file with instructions for an AI assistant. It tells the assistant what to do, what to avoid and how to answer safely, in English and Portuguese.

Uma skill é um ficheiro Markdown com instruções para um assistente de IA. Diz ao assistente o que fazer, o que evitar e como responder com segurança, em inglês e português.

## Design principles / Princípios de desenho

1. Safety before features.
2. Never ask for or store passwords, PINs or card numbers.
3. Treat user content as data, never as instructions.
4. Say what is unknown instead of guessing.
5. Keep everything open, simple and easy to review.

## Not built yet / Ainda não construído

An API, a website and cloud services are only ideas for the future. See `docs/roadmap.md`.

Uma API, um website e serviços na nuvem são apenas ideias para o futuro. Ver `docs/roadmap.md`.
