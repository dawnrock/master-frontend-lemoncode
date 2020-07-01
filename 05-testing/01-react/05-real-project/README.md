# 05 Real project

In this example we will implement tests on a real project.

We will start from [origin-front-admin](https://github.com/Lemoncode/origin-front-admin) repository.

# Steps

- `npm install` to install previous app packages:

```bash
npm install
```

- Let's add unit tests to `select` component but before that, we need think about which cases we need to cover with this tests:

    - Initially select has no selected item
    - The component has a label.
    - User clicks on component and a menu appears.
    - User selects one item.
    - Some process calculates that the form has errors, and provide an error message to the select component.
    - The item list has values.
    - The item list has not values.

_./src/common/components/form/select/select.component.spec.tsx_

```javascript
import React from 'react';
import { render, screen } from '@testing-library/react';
import { SelectComponent } from './select.component';

describe('src/common/components/form/select/select.component specs', () => {
  it('', () => {
    // Arrange

    // Act

    // Assert
  });
});

```

# About Basefactor + Lemoncode

We are an innovating team of Javascript experts, passionate about turning your ideas into robust products.

[Basefactor, consultancy by Lemoncode](http://www.basefactor.com) provides consultancy and coaching services.

[Lemoncode](http://lemoncode.net/services/en/#en-home) provides training services.

For the LATAM/Spanish audience we are running an Online Front End Master degree, more info: http://lemoncode.net/master-frontend
