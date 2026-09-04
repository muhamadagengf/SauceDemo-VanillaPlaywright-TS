# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: Login.spec.ts >> Login Feature >> Login success with valid credential
- Location: tests/Login.spec.ts:6:7

# Error details

```
Error: browserType.launch: Target page, context or browser has been closed
Browser logs:

<launching> /home/runner/.cache/ms-playwright/webkit-2336/pw_run.sh --inspector-pipe --headless --no-startup-window
<launched> pid=3232
[pid=3232][err] /home/runner/.cache/ms-playwright/webkit-2336/minibrowser-wpe/bin/MiniBrowser: error while loading shared libraries: libevent-2.1.so.7: cannot open shared object file: No such file or directory
Call log:
  - <launching> /home/runner/.cache/ms-playwright/webkit-2336/pw_run.sh --inspector-pipe --headless --no-startup-window
  - <launched> pid=3232
  - [pid=3232][err] /home/runner/.cache/ms-playwright/webkit-2336/minibrowser-wpe/bin/MiniBrowser: error while loading shared libraries: libevent-2.1.so.7: cannot open shared object file: No such file or directory
  - [pid=3232] <gracefully close start>
  - [pid=3232] <kill>
  - [pid=3232] <will force kill>
  - [pid=3232] <process did exit: exitCode=127, signal=null>
  - [pid=3232] starting temporary directories cleanup
  - [pid=3232] finished temporary directories cleanup
  - [pid=3232] <gracefully close end>

```