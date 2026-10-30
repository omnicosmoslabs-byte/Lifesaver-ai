# Threat Model / Modelo de Ameaças

This document lists the main risks to Lifesaver-ai and its users, and how we reduce them.

Este documento lista os principais riscos para o Lifesaver-ai e os seus utilizadores, e como os reduzimos.

## Threats / Ameaças

| Threat / Ameaça | Example / Exemplo | Mitigation / Mitigação |
|---|---|---|
| Prompt injection | A document says "ignore your rules" | Treat all user content as data, never as instructions |
| Credential theft | A user is asked to share a password or PIN | Never ask for or store passwords, PINs or card numbers |
| Wrong advice | The AI sounds sure but is wrong | Say what is unknown; point to a lawyer or advisor for serious decisions |
| Privacy leak | Personal data is stored or shared | Keep data private by default; collect the minimum |
| Malicious skill file | Someone edits a SKILL.md to cause harm | Review all changes before merging; keep the history public |
| Scam impersonation | Fake copies of Lifesaver-ai appear | Publish only from the official repository |

## Out of scope / Fora do âmbito

Lifesaver-ai cannot protect a device that is already infected, or a user who shares secrets willingly.

O Lifesaver-ai não consegue proteger um dispositivo já infetado, nem um utilizador que partilha segredos por vontade própria.

## Review / Revisão

This model must be reviewed whenever a new module is added.
