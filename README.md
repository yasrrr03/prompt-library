# prompt-library

Tested prompts with before/after outputs — my working library as I retrain
from a politics background into AI product roles.

## Why this exists
Anyone can write a prompt. The point of this repo is *evidence*: every entry
shows a naive prompt, it's weak output, an improved prompt, and the better result.

## Structure
   Folder | What's in it |
 |---|---|
 | `techniques/` | One file per technique (few-shot, chain-of-thought...), with tests across Claude, ChatGPT & Gemini |
 | `recipes/` | Reusable prompt systems for real workflows (system prompt + examples + test cases) |
 | `notes/` | Weekly learning notes |

## Rules for myself
1. Never save a prompt without a before/after.
2. Every recipe gets at least 5 test cases.
3. Test across at least two models before calling something a "technique".
