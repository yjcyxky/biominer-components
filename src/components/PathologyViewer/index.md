---
title: PathologyViewer
group:
  path: /components/viewer
  title: Viewer
  order: 1
---

## PathologyViewer

### Default Parameters

```tsx
import React from 'react';
import { PathologyViewer } from 'biominer-components';

export default () => (
  <div style={{height: 500}}>
    <PathologyViewer style={{height: 500}} id="test-pathology" tileSources="https://openseadragon.github.io/example-images/highsmith/highsmith.dzi" />
  </div>
);
```

### Customized Parameters

```tsx
import React from 'react';
import { PathologyViewer } from 'biominer-components';

export default () => (
  <div style={{height: 500}}>
    <PathologyViewer id="test-pathology-1" tileSources="https://openseadragon.github.io/example-images/highsmith/highsmith.dzi" showNavigator={false} degrees={60} showRotationControl={false} />
  </div>
);
```

<API></API>