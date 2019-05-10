## Ruby

These settings apply only when `--ruby` is specified on the command line.

```yaml
package-name: azure_mgmt_MosService
package-version: 2019-10-05
azure-arm: true
```

### Tag: package-2019-10-05 and ruby

These settings apply only when `--tag=package-2019-10-05 --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

```yaml $(tag) == 'package-2019-10-05' && $(ruby)
namespace: Microsoft.Mo
output-folder: $(ruby-sdks-folder)/MosService
```
