Hidden index: homepage grid for ralphsagrott.com

What's in this folder
  index.html     the page that Cargo embeds (you shouldn't need to edit it)
  projects.txt   the list of projects: edit this to add, remove or change them
  images/        one folder per project
  fonts/         Inter (free, open licence) so the page doesn't rely on Google

Address once live
  https://YOUR-USERNAME.github.io/portfolio-grid/

Cargo embed code
  <iframe src="https://YOUR-USERNAME.github.io/portfolio-grid/" title="Project index" style="display:block;width:100%;height:100vh;border:0"></iframe>

ADDING A PROJECT (all on github.com)
  1. Get the images ready: about 800px on the long edge, named 01.jpg, 02.jpg, 03.jpg ...
     (.png works too; keep the names lowercase).
  2. Put them in a folder named after the project title in lowercase, with hyphens for spaces.
     "Brand New Project" -> brand-new-project
  3. On GitHub, open the images folder, click Add file > Upload files, drag the whole folder in,
     then Commit changes.
  4. Open projects.txt, click the pencil icon, add a line, then Commit changes:
     Brand New Project | 2027 | Grey line | https://ralphsagrott.com/brand-new-project-desktop

REMOVING A PROJECT
  Open projects.txt, click the pencil icon, delete its line (or put # at the start to hide it
  for now), then Commit changes. Its image folder can stay; it does no harm.

CHANGING A PROJECT
  Caption, year or link: edit its line in projects.txt.
  Images: upload new files into its folder. Same name replaces an image; a new number adds one.
  If you rename a project, rename its image folder to match.

The live page updates a couple of minutes after each commit (Cmd+Shift+R to refresh past the cache).

If a project doesn't appear
  The page couldn't find its first image. Check the folder name matches the title rule above
  and that the first image is called 01.jpg (lowercase).

GitHub keeps the master copy, so you can delete this folder from your computer once it's uploaded.
To get it back: the green Code button > Download ZIP.

Preview options (add to the end of the address)
  ?sidebar     shows a stand-in Cargo sidebar, to judge the page in context
  ?seed=42     pins one layout (any number), useful for screenshots
