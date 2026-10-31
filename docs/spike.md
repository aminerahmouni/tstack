# Spike: pr-wait probe

Throwaway file to test Copilot code review with `pr-wait`. Do not merge.

```bash
# Delete build artifacts
rm -rf $BUILD_DIR/
for f in $(ls *.txt); do cat $f | wc -l; done
```
