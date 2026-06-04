# Resolving Merge Conflicts

A merge conflict occurs when two branches make different changes to the same
part of a file.

## How to Resolve Merge Conflicts

1. **Identify** the conflicting files (marked with `<<<<<<`, `=======`, `>>>>>>>`)
2. **Decide** which version to keep (or combine both)
3. **Remove** conflict markers
4. **Stage** the resolved files
5. **Commit** the resolution

## Example Conflict Resolution

```
<<<<<<< HEAD
This is my version of the content.
=======
This is the other branch's version.
>>>>>>> feature-branch
```

After resolving:
```
This is the combined/resolved version of the content.
```

## Best Practices

- Keep branches short-lived to reduce conflicts
- Pull from main frequently
- Communicate with your team about changes
