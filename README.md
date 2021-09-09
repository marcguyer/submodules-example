# Submodules Example

This is an example using multiple git submodules to manage a large multi-root project and develop it with Intellij IDEs.

## Recursive Clone

Use the recursive flag to also clone and initialize the submodules:

```shell
git clone --recursive git@github.com:marcguyer/submodules-example.git
```

## Notes

### Synchronous Git Branch Control

[JetBrains IDE Synchronous Branch Control](https://www.jetbrains.com/help/idea/manage-branches.html#synchronous_branch_control) - enables simultaneous commit/push/etc for all submodule branches of the same name.

### Docker cheats

```shell
docker compose exec one composer install
```