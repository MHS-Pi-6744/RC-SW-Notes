> [!Note]
> I have made a bunch of github teams and this whole thing kinda relies on those teams existing. If they don't... Uhh... Good luck I guess.

> [!Warning]
> These rules are NOT final and SHOULD be changed when needed

# FAQ

## Why?

To teach programmers good collaborative code management strategies

## When?

Usually during precomp & postcomp.

## What are GitHub Teams?

Teams are really cool. They allow categorization of users in an organization. This allows for finer grained control & easier management. 

# Protect The Main Branch

## Bypass List

`@Senior Developers`

## Target Branches

`Include Default Branch`

## Rules

- Restrict Deletions
- Require a Pull Request before merging
	- 3 Req'd Approvals 
	- Require Review from specific teams
		- `@Auto` - `*.auto, *path`
		- `@Junior Developers` - `*`
		- `@Senior Developers` - `*`
		- `@{Subsystem}` - `{Subsystem}.java`
		- ... Extend this to the subsystems and such
- Block force pushes