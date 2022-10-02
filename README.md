# abapGit builds archive

This repo holds built standalone versions of [abapGit](https://github.com/abapGit/abapGit).

Take the source code from `zabapgit_standalone.prog.abap` ([please look here for more details](https://docs.abapgit.org/guide-install.html#install-standalone-version)).

## Direct cloning

Alternatively, if you already have a version of abapGit in your system, you may want to pull the update directly from here. Clone this repo to your system and pull. A couple of precautions for this approach:
- please mind the program naming, the program in the repo is called `zabapgit_standalone`. Same is the recommendation for the first installation. So, supposedly, you want to copy your existing `zabapgit_standalone` to `zabapgit_backup` (or similar) first and run the clone **from there**. It will also keep your abapgit operational if anything goes wrong with the cloning or activation.
- the cloning will require from you to create a package. Create a local package (starting with $). Also **avoid starting** the package name from "abapgit..." if you ever plan to clone a full development version after. Better use something like `$standalone_abapgit`.
