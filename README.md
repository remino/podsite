podsite
=======

Container directory to hold multiple "pods", or mini web sites or apps, and conbining them into a single public site with symlinks using [unidir](https://github.com/remino/unidir).

## Usage

```
podsite 1.0.0

USAGE:

	podsite [<options>] help
	podsite [<options>] init [<env1>] [<env2>] [<envn>...]
	podsite [<options>] unify [<env>]
	podsite [<options>] version

Manage a "podsite", directory containing multiple "pods",
or small web sites or apps, to be combined into a single
public site directory.

COMMANDS:

	help      Show this help screen.
	init      Initialize podsite for <envs>.
	          (Default: dev production staging test)
	unify     Unify pods into public site for <env>.
	          (Default: dev)
	version   Show script name and version number.

OPTIONS:

	-h        Show this help screen.
	-v        Show script name and version number.

```
