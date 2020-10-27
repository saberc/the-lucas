```
apiVersion: entando.org/v1
kind: EntandoDeBundle
metadata:
  name: the-lucas
  labels:
    plugin: 'true'
    widget: 'true'
spec:
  details:
    name: thelucas-bundle
    description: This is the theLucas bundle
    dist-tags:
      latest: v0.0.9
    versions:
      - v0.0.1
      - v0.0.2
      - v0.0.3
      - v0.0.4
      - v0.0.5
      - v0.0.6
      - v0.0.7
      - v0.0.8
      - v0.0.9
  tags:
    - version: v0.0.1
      shasum: e986aa2c426987b979ab68a4de71e5ac587d735f
      integrity: e986aa2c426987b979ab68a4de71e5ac587d735f
      tarball: 'https://github.com/firegloves-bundles/the-lucas.git'
    - version: v0.0.2
      shasum: e986aa2c426987b979ab68a4de71e5ac587d735f
      integrity: e986aa2c426987b979ab68a4de71e5ac587d735f
      tarball: 'https://github.com/firegloves-bundles/the-lucas.git'
      description: 'plugin decriptor WITHOUT deploymentBaseName property'
    - version: v0.0.3
      shasum: e986aa2c426987b979ab68a4de71e5ac587d735f
      integrity: e986aa2c426987b979ab68a4de71e5ac587d735f
      tarball: 'https://github.com/firegloves-bundles/the-lucas.git'
      description: 'plugin decriptor WITH deploymentBaseName property'
    - version: v0.0.4
      shasum: e986aa2c426987b979ab68a4de71e5ac587d735f
      integrity: e986aa2c426987b979ab68a4de71e5ac587d735f
      tarball: 'https://github.com/firegloves-bundles/the-lucas.git'
      description: 'CMS contents available'
    - version: v0.0.5
      shasum: e986aa2c426987b979ab68a4de71e5ac587d735f
      integrity: e986aa2c426987b979ab68a4de71e5ac587d735f
      tarball: 'https://github.com/firegloves-bundles/the-lucas.git'
      description: 'CMS contents WITHOUT plugin'
    - version: v0.0.6
      shasum: e986aa2c426987b979ab68a4de71e5ac587d735f
      integrity: e986aa2c426987b979ab68a4de71e5ac587d735f
      tarball: 'https://github.com/firegloves-bundles/the-lucas.git'
      description: 'kerruba plugin image (shorter than max length) NO CONTENTS'
    - version: v0.0.7
      shasum: e986aa2c426987b979ab68a4de71e5ac587d735f
      integrity: e986aa2c426987b979ab68a4de71e5ac587d735f
      tarball: 'https://github.com/firegloves-bundles/the-lucas.git'
      description: 'only plugin and widgets, with deploymentBaseName, ingressPath and permissions (NOT existing perms)'
    - version: v0.0.8
      shasum: e986aa2c426987b979ab68a4de71e5ac587d735f
      integrity: e986aa2c426987b979ab68a4de71e5ac587d735f
      tarball: 'https://github.com/firegloves-bundles/the-lucas.git'
      description: 'only plugin and widgets, with deploymentBaseName, ingressPath and permissions (existing perms)'
    - version: v0.0.9
      shasum: e986aa2c426987b979ab68a4de71e5ac587d735f
      integrity: e986aa2c426987b979ab68a4de71e5ac587d735f
      tarball: 'https://github.com/firegloves-bundles/the-lucas.git'
      description: 'one more version'
```