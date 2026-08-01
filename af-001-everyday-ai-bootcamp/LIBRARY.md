# LIBRARY.md

**Kit Type:** Training Kit  
**Status:** Active Development  
**Version:** 0.1  
**Repository:** AF-001 — Everyday AI Bootcamp  
**Repository Object:** ROOT_LIBRARY  
**Raw:** https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/LIBRARY.md  
**This File (Raw):** https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/LIBRARY.md  

---

# Repository Object Table

| FILE_HANDLE | LOCAL | RAW FILE |
|---|---|---|
| ROOT_README | README.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/README.md |
| ROOT_SETUP | SETUP.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/SETUP.md |
| ROOT_COURSE | COURSE.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/COURSE.md |
| ROOT_LIBRARY | LIBRARY.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/LIBRARY.md |
| ROOT_LICENSE | LICENSE.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/LICENSE.md |
| LESSONS_README | — | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/lessons/README.md |
| LESSON_01 | LESSON_01.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/lessons/LESSON_01.md |
| LESSON_02 | LESSON_02.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/lessons/LESSON_02.md |
| LESSON_03 | LESSON_03.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/lessons/LESSON_03.md |
| LESSON_04 | LESSON_04.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/lessons/LESSON_04.md |
| LESSON_05 | LESSON_05.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/lessons/LESSON_05.md |
| LESSON_06 | LESSON_06.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/lessons/LESSON_06.md |
| LESSON_07 | LESSON_07.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/lessons/LESSON_07.md |
| LESSON_08 | LESSON_08.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/lessons/LESSON_08.md |
| LESSON_09 | LESSON_09.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/lessons/LESSON_09.md |
| LESSON_10 | LESSON_10.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/lessons/LESSON_10.md |
| LESSON_11 | LESSON_11.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/lessons/LESSON_11.md |
| LESSON_12 | LESSON_12.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/lessons/LESSON_12.md |
| LESSON_13 | LESSON_13.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/lessons/LESSON_13.md |
| LESSON_14 | LESSON_14.md | https://raw.githubusercontent.com/agentforgeframework-cpu/-agentforge-dev/refs/heads/main/af-001-everyday-ai-bootcamp/lessons/LESSON_14.md |

---

# Availability Rule

A lesson is available for delivery only when:

1. its `FILE_HANDLE` appears in this table;
2. the file can be resolved through the active Repository Object Resolution Mode;
3. the retrieved file identity matches the expected lesson;
4. the lesson file has been read during the current course run.

A filename, course outline entry, prior summary, remembered lesson, or inferred sequence does not make a lesson active.

If a required Repository Object cannot be resolved or verified, follow the failure behavior in `SETUP.md` and stop.

---

# LOCAL Deployment Note

In a flat LOCAL deployment:

- root objects and lesson files may be supplied together;
- lesson `LOCAL` filenames are resolved directly from this table;
- `LESSONS_README` is intentionally excluded from the flat LOCAL course package and is marked with an em dash;
- do not require the folder README for course execution.

---

# RAW Deployment Note

In RAW mode:

- use the exact `RAW FILE` location listed here;
- do not substitute a GitHub page URL, search result, cached copy, or reconstructed path;
- retrieve each required lesson immediately before activation;
- follow the continuing lesson retrieval requirements in `SETUP.md`.

---

End of Library
