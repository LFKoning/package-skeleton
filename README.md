# Package Skeleton

## Goal

The goal of this repository is provide a minimal structure for build in proper python package.
This setup should guide the user in writing well-formatted code with documentation and tests.

The skeleton provides:

- A clear directory structure.
- Proper installation files; setup.py, requirements.txt, Makefile.
- Templates for documentation and a licence.
- Minimal dependencies for package development.

## Installation

The easiest way to get started is to just clone the repository:

```bash
git clone https://github.com/LFKoning/package-skeleton.git
```

Once the repo is on your drive, you should:

1. Rename the `src/my_package` and `tests/my_package` folders to something more descriptive.
2. Edit the `setup.py` to set things as author, package name, package description, et cetera.
3. Edit this `README.md` to describe your own package

Once all that is done, make sure you commit your changes:

```bash
git add -A
git commit -m "Initial commit of my package"
```

Then you should change the repository's remote to your own:

```bash
git remote set-url origin https://github.com/<username>/<repository>.git
```

Or if you are using SSH:

```bash
git remote set-url origin git@github.com:<username>/<repository>.git
```

To check if the changes were successful, type:

```bash
git remote -v
```

Finally, you should push your code into the repository

```bash
git push
```

Now you're all set to start building your own package!

## Want to contribute?

If you have questions or want to contribute to this project, see `CONTRIBUTING.md`