# Prototype
An easy place to put scattered WIP files.

**Workflow:**
1. Branch from `main` with a descriptive name: `prototype/<idea>-<author>`
2. Develop in your branch. Use whatever structure makes sense there.
3. When the idea matures, promote it:
   - If it becomes a model → move to `models/`
   - If it becomes a core module → move to `core/`
   - If it becomes a benchmark → move to `benchmarks/`
4. Merge the promotion into `main`, one addition at a time
5. I recomend deleting the prototype branch or prefix with `archive/` e.g. `archive/prototype/<idea>-<author>`

**Never commit directly to `main` under `prototypes/`.**
