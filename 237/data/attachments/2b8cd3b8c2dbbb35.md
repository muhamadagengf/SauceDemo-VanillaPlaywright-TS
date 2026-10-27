# Instructions

- Following Playwright test failed.
- Explain why, be concise, respect Playwright best practices.
- Provide a snippet of code with the fix, if possible.

# Test info

- Name: Checkout.spec.ts >> Checkout Feature >> User can add 3 products and checkout successfully
- Location: tests/Checkout.spec.ts:9:7

# Error details

```
Error: browserType.launch: Target page, context or browser has been closed
Browser logs:

<launching> /home/runner/.cache/ms-playwright/webkit-2370/pw_run.sh --inspector-pipe --headless --no-startup-window
<launched> pid=3557
[pid=3557][err] /home/runner/.cache/ms-playwright/webkit-2370/minibrowser-wpe/bin/MiniBrowser: error while loading shared libraries: libicudata.so.74: cannot open shared object file: No such file or directory
Call log:
  - <launching> /home/runner/.cache/ms-playwright/webkit-2370/pw_run.sh --inspector-pipe --headless --no-startup-window
  - <launched> pid=3557
  - [pid=3557][err] /home/runner/.cache/ms-playwright/webkit-2370/minibrowser-wpe/bin/MiniBrowser: error while loading shared libraries: libicudata.so.74: cannot open shared object file: No such file or directory
  - [pid=3557] <gracefully close start>
  - [pid=3557] <kill>
  - [pid=3557] <will force kill>
  - [pid=3557] <process did exit: exitCode=127, signal=null>
  - [pid=3557] starting temporary directories cleanup
  - [pid=3557] finished temporary directories cleanup
  - [pid=3557] <gracefully close end>

```