# Devlit Test Repository

**Purpose:**  
This repository is a **sandbox environment** for DevTeensSquad-X17 to experiment, prototype, and test code before merging into the main Devlit repo.

---

## Guidelines for Use

1. **Only experimental code here**  
   - Do not store production-ready features.
   - Use feature branches for new experiments:  
     `feature/<experiment-name>`

2. **Commit often**  
   - Keep a clear history of your tests.  
   - Use descriptive commit messages like:  
     `Add prototype for mission scoring logic`

3. **Keep the repo organized**  
   - Use folders for different experiments if needed:  
     ```
     test/
     ├── frontend-tests/
     └── backend-tests/
     ```

4. **No sensitive data**  
   - Environment variables, API keys, and secrets **must never** be pushed.

5. **Clean up regularly**  
   - Remove old or irrelevant tests to avoid clutter.

---

## Suggested Workflow

1. Create a **branch** for each experiment.  
2. Push and test code on that branch.  
3. Once verified, **merge only the final code** into the main Devlit repo.

---

## License

All test code follows the **MIT License**, same as the main project.
