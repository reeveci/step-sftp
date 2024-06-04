# Reeve CI / CD - Pipeline Step: SFTP

This is a [Reeve](https://github.com/reeveci/reeve) step for transferring files using SFTP.

## Configuration

See the environment variables mentioned in [Dockerfile](Dockerfile).

If no script file is specified using `SCRIPT`, `input` is used to specify the commands to be executed, e.g.:

```yaml
input: |
  put localfile.txt
  get remotefile.txt
```
