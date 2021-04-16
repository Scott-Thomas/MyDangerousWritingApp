#To run#

Install yarn
Follow the instructions in dev.md
Run 'yarn start' in the top-level directory
(this runs a dev server environment, unoptimised for deployment.
This does not matter in your usecase.)


#To modify#

The timers are located in src/components/App.jsx
Look for fade: and kill: entries and adjust as desired.
There is no need to rebuild or recompile...
the dev environment runs directly from code.

Preconfigured word targets are set in 
src/components/WriteButton.jsx if you 
don't feel like setting a new target in
the browser bar every time.
