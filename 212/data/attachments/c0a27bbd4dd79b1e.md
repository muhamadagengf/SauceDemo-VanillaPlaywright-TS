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
<launched> pid=3548
[pid=3548][err] /home/runner/.cache/ms-playwright/webkit-2359/minibrowser-wpe/bin/MiniBrowser: error while loading shared libraries: libevent-2.1.so.7: cannot open shared object file: No such file or directory
Call log:
  - <launching> /home/runner/.cache/ms-playwright/webkit-2359/pw_run.sh --inspector-pipe --headless --no-startup-window
  - <launched> pid=3548
  - [pid=3548][err] /home/runner/.cache/ms-playwright/webkit-2359/minibrowser-wpe/bin/MiniBrowser: error while loading shared libraries: libevent-2.1.so.7: cannot open shared object file: No such file or directory
  - [pid=3548] <gracefully close start>
  - [pid=3548] <kill>
  - [pid=3548] <will force kill>
  - [pid=3548] <process did exit: exitCode=127, signal=null>
  - [pid=3548] starting temporary directories cleanup
  - [pid=3548] finished temporary directories cleanup
  - [pid=3548] <gracefully close end>

```