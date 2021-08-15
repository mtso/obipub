## Related config files
- `.obi_tool/package_resolution.json` - mapping file of package name to file location
- `obipub.toml`


- registry/
  |- packages/
  |- index/
- tool/
  <obipub code>

## Manually creating tarballs

// to zip
tar -czvf toml-0.0.1.tar.gz -C ~/.obipub-cache/hosted/toml-0.0.1/lib .
// to extract
tar -xf [source path] --directory [destination path]
