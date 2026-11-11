# Maintaining yichen-codex-chatgpt

## Resolve the source and installed copy

Read [maintenance.json](maintenance.json) for the release repository, branch, and Skill path. Verify the checkout's Git remote, fetch the listed branch, and record the resolved commit. Locate the installed [SKILL.md](SKILL.md) and resolve any symlink before comparing its directory with the source package. Use the repository's [read-only comparison procedure](https://github.com/finnlyu41-tech/yichen-skills/blob/main/docs/skill-maintenance.md#只读差异检查) for tracked files. Check separately for extra local files and preserve private configuration and local changes.

If either source or installed content has diverged, identify the difference and work from an isolated checkout. If the release source is unavailable, record the pending check and retain the installed version.

## Edit and verify

Keep this Skill's routing, collaboration protocol, and runtime contract in its source and linked references. Keep cross-Skill conventions in the applicable personal rules library. Keep credentials, local runtime configuration, browser sessions, and task evidence outside the public package. Follow the scope of the current authorization for source changes and any separate approval required to expose a project or exercise a live route.

For maintenance changes, validate the manifest, check the entry point and local references, and run the repository's applicable contract checks. Use [routing examples](examples/routing-prompts.md) to check any affected workflow and [setup](references/setup.md) to determine the prerequisites for a live test. Record static validation and live behavior separately.

## Sync an approved release

Verify the merged commit on the listed branch. Back up the affected installed files and check for concurrent edits before applying the verified package changes. Compare the installed files with that commit and rerun the package check against the actual installed directory. Where AI_Rule is available, run `rule_route.py package` from its tools directory with the package directory as the argument. Record the commit, the installed path, and the checks performed.
