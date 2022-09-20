# A ajouter dans le main.js

Example de JS
``` 

import {openModal} from 'modalbox'
document.querySelectorAll('.js-modal').forEach(a => {
    a.addEventListener('click', openModal)
})
```