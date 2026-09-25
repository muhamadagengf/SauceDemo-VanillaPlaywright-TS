# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: Login.spec.ts >> Login Feature >> Login failed with wrong username
- Location: tests/Login.spec.ts:40:7

# Error details

```
Error: browserType.launch: Target page, context or browser has been closed
Browser logs:

<launching> /home/runner/.cache/ms-playwright/webkit-2359/pw_run.sh --inspector-pipe --headless --no-startup-window
<launched> pid=3488
[pid=3488][err] /home/runner/.cache/ms-playwright/webkit-2359/minibrowser-wpe/bin/MiniBrowser: error while loading shared libraries: libevent-2.1.so.7: cannot open shared object file: No such file or directory
Call log:
  - <launching> /home/runner/.cache/ms-playwright/webkit-2359/pw_run.sh --inspector-pipe --headless --no-startup-window
  - <launched> pid=3488
  - [pid=3488][err] /home/runner/.cache/ms-playwright/webkit-2359/minibrowser-wpe/bin/MiniBrowser: error while loading shared libraries: libevent-2.1.so.7: cannot open shared object file: No such file or directory
  - [pid=3488] <gracefully close start>
  - [pid=3488] <kill>
  - [pid=3488] <will force kill>
  - [pid=3488] exception while trying to kill process: Error: kill ESRCH
  - [pid=3488] <process did exit: exitCode=127, signal=null>
  - [pid=3488] starting temporary directories cleanup
  - [pid=3488] finished temporary directories cleanup
  - [pid=3488] <gracefully close end>

```