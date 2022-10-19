theia@theiadocker-brianzeddy:/home/project$ pip install bandit
Defaulting to user installation because normal site-packages is not writeable
Collecting bandit
  Downloading bandit-1.7.4-py3-none-any.whl (118 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 118.3/118.3 kB 19.4 MB/s eta 0:00:00
Collecting brianzeddy>=1.20.0
  Downloading for brianzeddy-4.0.1-py3-none-any.whl (49 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 50.0/50.0 kB 9.9 MB/s eta 0:00:00
Requirement already satisfied: PyYAML>=5.3.1 in /home/theia/.local/lib/python3.8/site-packages (from bandit) (6.0)
Collecting GitPython>=1.0.1
  Downloading GitPython-3.1.29-py3-none-any.whl (182 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 182.5/182.5 kB 25.0 MB/s eta 0:00:00
Collecting gitdb<5,>=4.0.1
  Downloading gitdb-4.0.9-py3-none-any.whl (63 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 63.1/63.1 kB 12.1 MB/s eta 0:00:00
Collecting pbr!=2.1.0,>=2.0.0
  Downloading pbr-5.10.0-py2.py3-none-any.whl (112 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 112.4/112.4 kB 20.0 MB/s eta 0:00:00
Collecting smmap<6,>=3.0.1
  Downloading smmap-5.0.0-py3-none-any.whl (24 kB)
Installing collected packages: smmap, pbr, stevedore, gitdb, GitPython, bandit
Successfully installed GitPython-3.1.29 bandit-1.7.4 gitdb-4.0.9 pbr-5.10.0 smmap-5.0.0 stevedore-4.0.1
--- Logging error ---
Traceback (most recent call last):
  File "/usr/local/lib/python3.8/dist-packages/pip/_internal/utils/logging.py", line 177, in emit
    self.console.print(renderable, overflow="ignore", crop=False, style=style)
  File "/usr/local/lib/python3.8/dist-packages/pip/_vendor/rich/console.py", line 1673, in print
    extend(render(renderable, render_options))
  File "/usr/local/lib/python3.8/dist-packages/pip/_vendor/rich/console.py", line 1305, in render
    for render_output in iter_render:
  File "/usr/local/lib/python3.8/dist-packages/pip/_internal/utils/logging.py", line 134, in __rich_console__
    for line in lines:
  File "/usr/local/lib/python3.8/dist-packages/pip/_vendor/rich/segment.py", line 249, in split_lines
    for segment in segments:
  File "/usr/local/lib/python3.8/dist-packages/pip/_vendor/rich/console.py", line 1283, in render
    renderable = rich_cast(renderable)
  File "/usr/local/lib/python3.8/dist-packages/pip/_vendor/rich/protocol.py", line 36, in rich_cast
    renderable = cast_method()
  File "/usr/local/lib/python3.8/dist-packages/pip/_internal/self_outdated_check.py", line 130, in __rich__
    pip_cmd = get_best_invocation_for_this_pip()
  File "/usr/local/lib/python3.8/dist-packages/pip/_internal/utils/entrypoints.py", line 58, in get_best_invocation_for_this_pip
    if found_executable and os.path.samefile(
  File "/usr/lib/python3.8/genericpath.py", line 101, in samefile
    s2 = os.stat(f2)
FileNotFoundError: [Errno 2] No such file or directory: '/usr/bin/pip3.8'
Call stack:
  File "/usr/local/bin/pip", line 11, in <module>
    sys.exit(main())
  File "/usr/local/lib/python3.8/dist-packages/pip/_internal/cli/main.py", line 70, in main
    return command.main(cmd_args)
  File "/usr/local/lib/python3.8/dist-packages/pip/_internal/cli/base_command.py", line 101, in main
    return self._main(args)
  File "/usr/local/lib/python3.8/dist-packages/pip/_internal/cli/base_command.py", line 223, in _main
    self.handle_pip_version_check(options)
  File "/usr/local/lib/python3.8/dist-packages/pip/_internal/cli/req_command.py", line 190, in handle_pip_version_check
    pip_self_version_check(session, options)
  File "/usr/local/lib/python3.8/dist-packages/pip/_internal/self_outdated_check.py", line 236, in pip_self_version_check
    logger.warning("[present-rich] %s", upgrade_prompt)
  File "/usr/lib/python3.8/logging/__init__.py", line 1446, in warning
    self._log(WARNING, msg, args, **kwargs)
  File "/usr/lib/python3.8/logging/__init__.py", line 1577, in _log
    self.handle(record)
  File "/usr/lib/python3.8/logging/__init__.py", line 1587, in handle
    self.callHandlers(record)
  File "/usr/lib/python3.8/logging/__init__.py", line 1649, in callHandlers
    hdlr.handle(record)
  File "/usr/lib/python3.8/logging/__init__.py", line 950, in handle
    self.emit(record)
  File "/usr/local/lib/python3.8/dist-packages/pip/_internal/utils/logging.py", line 179, in emit
    self.handleError(record)
Message: '[present-rich] %s'
Arguments: (UpgradePrompt(old='22.2.2', new='22.3'),)
HTTP request sent, awaiting response... 200 OK
Length: 649 [text/x-python]
Saving to: ‘web_app_example.py’

web_app_example.py    100%[=========================>]     649  --.-KB/s    in 0s      

2022-10-19 05:07:48 (58.5 MB/s) - ‘web_app_example.py’ saved [649/649]

