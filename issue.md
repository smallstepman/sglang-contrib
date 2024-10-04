[code improvment suggestion] project structure and typing 
I'd like to probe if you're open to the following changes:
- rename `python/` dir to `src/` (industry standard, especially given python is the only language used here)
- add `mypy` to pre-commit-hooks with `strict` mode enabled (see https://mypy.readthedocs.io/en/stable/faq.html#would-my-project-benefit-from-static-typing). This will force to define types for each and every parameter in: all functions signature's, all class variables, and some variables inside function bodies. Mypy strict has become a standard for many teams. Whenever we use anything from sglang package, we get a lot of errors regarding typing, this would fix that.
<img width="982" alt="image" src="https://github.com/user-attachments/assets/2ebd6603-db57-4d89-b59b-c6437cf6abfc">


I'm open to contributing 
