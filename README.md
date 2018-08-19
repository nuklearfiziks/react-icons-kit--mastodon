# react-icons-kit--mastodon

None of the official kits in react-icons-kit had a Mastodon icon so I 
made one using the SVG on [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Mastodon_Logotype_(Simple).svg).

```js
import { Icon } from 'react-icons-kit'
import { mastodon } from './mastodon-icon'

const Icon = () => (<Icon icon={mastodon} size={48} />);
```

I haven't published this to npm because I'm not sure what to name the package. Please discuss in issue queue.
