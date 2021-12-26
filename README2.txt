Windows PowerShell
Copyright (C) Microsoft Corporation. All rights reserved.

Install the latest PowerShell for new features and improvements! https://aka.ms/PSWindows

PS C:\Users\mrxgr> vue create
Usage: create [options] <app-name>

create a new project powered by vue-cli-service

Options:
  -p, --preset <presetName>       Skip prompts and use saved or remote preset
  -d, --default                   Skip prompts and use default preset
  -i, --inlinePreset <json>       Skip prompts and use inline JSON string as preset
  -m, --packageManager <command>  Use specified npm client when installing dependencies
  -r, --registry <url>            Use specified npm registry when installing dependencies (only for npm)
  -g, --git [message]             Force git initialization with initial commit message
  -n, --no-git                    Skip git initialization
  -f, --force                     Overwrite target directory if it exists
  --merge                         Merge target directory if it exists
  -c, --clone                     Use git clone when fetching remote preset
  -x, --proxy <proxyUrl>          Use specified proxy when creating project
  -b, --bare                      Scaffold project without beginner instructions
  --skipGetStarted                Skip displaying "Get started" instructions
  -h, --help                      output usage information

  Missing required argument <app-name>.

PS C:\Users\mrxgr> vue create project-for-devil


Vue CLI v4.5.15
? Please pick a preset: Default (Vue 3) ([Vue 3] babel, eslint)


Vue CLI v4.5.15
✨  Creating project in C:\Users\mrxgr\project-for-devil.
⚙️  Installing CLI plugins. This might take a while...


added 1276 packages, and audited 1277 packages in 1m

84 packages are looking for funding
  run `npm fund` for details

28 vulnerabilities (17 moderate, 11 high)

To address issues that do not require attention, run:
  npm audit fix

To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details.
🚀  Invoking generators...
📦  Installing additional dependencies...


added 73 packages, and audited 1350 packages in 11s

91 packages are looking for funding
  run `npm fund` for details

30 vulnerabilities (19 moderate, 11 high)

To address issues that do not require attention, run:
  npm audit fix

To address all issues (including breaking changes), run:
  npm audit fix --force

Run `npm audit` for details.
⚓  Running completion hooks...

📄  Generating README.md...

🎉  Successfully created project project-for-devil.
👉  Get started with the following commands:

 $ cd project-for-devil
 $ npm run serve

PS C:\Users\mrxgr> cd project-for-devil
PS C:\Users\mrxgr\project-for-devil> npm run serve

> project-for-devil@0.1.0 serve
> vue-cli-service serve

 INFO  Starting development server...
98% after emitting CopyPlugin

 DONE  Compiled successfully in 6828ms                                                                      8:02:47 p.m.


  App running at:
  - Local:   http://localhost:8080/
  - Network: http://10.0.0.129:8080/

  Note that the development build is not optimized.
  To create a production build, run npm run build.

