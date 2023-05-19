# Hajimari

For apps to show up in Hajimari, ensure that the namespace is added to the `matchNames` list under `namespaceSelector`
```yaml
values:
  hajimari:
    namespaceSelector:
    matchNames:
      - default
      - ns1
      - ns2
  ```