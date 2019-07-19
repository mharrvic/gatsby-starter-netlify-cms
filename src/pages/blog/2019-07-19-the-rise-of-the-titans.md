---
templateKey: blog-post
title: The Rise of the Titans
date: 2019-07-19T04:52:34.675Z
description: The quick brown fox jumps over the lazy dog
tags:
  - coffee
  - milo
  - bearbrand
---
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Etiam scelerisque sem finibus dui feugiat, ac feugiat leo auctor. Nunc mauris ex, ultrices sed pretium nec, pretium nec tortor. Aenean a tempus dui. Interdum et malesuada fames ac ante ipsum primis in faucibus. Nam volutpat congue pretium. Phasellus auctor justo in accumsan sodales. Curabitur lobortis urna quis neque ultricies elementum sed nec nisl. Sed vel blandit eros, quis laoreet nisl. Etiam quis metus at mauris convallis tristique. Cras fermentum, dolor in malesuada cursus, est tellus dignissim ipsum, vitae sodales mauris nunc in magna. Quisque quis ante lacus. Proin rhoncus eget felis sed suscipit. Vivamus ligula eros, venenatis et aliquam non, commodo in mauris. Sed cursus diam quis dolor rhoncus cursus. Nullam laoreet mi eu pretium condimentum. Aenean auctor mi ut aliquam accumsan.

`import React from "react";`

`import ReactDOM from "react-dom";`

`import NextApp from './NextApp';`

`import registerServiceWorker from './registerServiceWorker';`

`import {AppContainer} from 'react-hot-loader';`

`const render = Component => {`

`  ReactDOM.render(`

`    // Wrap App inside AppContainer`

`    <AppContainer>`

`      <NextApp/>`

`    </AppContainer>,`

`    document.getElementById('root')`

`  );`

`};`

`registerServiceWorker();`

`render(NextApp);`

`if (module.hot) {`

`  module.hot.accept('./NextApp', () => {`

`    render(NextApp);`

`  });`

`}`

``

![Coffe project](/img/chemex.jpg "The Great Coffee")

``
