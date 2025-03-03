Code tunnel action
==================


This action runs Code in the tunneled mode that sets up `https://vscode.dev/tunnel/[hostname]` for your browser.

```yaml
    - name: Code tunnel
      if: ${{ failure() }}
      uses: gbraad-actions/code-tunnel-action@v1
```

> [!CAUTION]
> This actions might expose your secrets when used in an unmonitored workflow.
