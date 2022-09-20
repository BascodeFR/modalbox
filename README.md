# A ajouter dans le main.js

## Example dde code HTML

```
<aside id="register" class="modal register" aria-hidden="true" role="true" aria-labelledby="title-modal" style="display:none;">
        <div class="modal-wrapper pane js-modal-stop">
            <h2 id="title-modal" class="modal-title"> S'inscrire </h2>
            <hr/>
            <input type="text" class="fields"/>
            <a href="f" class="js-modal-close">test</a>
        </div>
    
</aside>

```

## Example de JS
``` 

import {openModal} from 'modalbox'
document.querySelectorAll('.js-modal').forEach(a => {
    a.addEventListener('click', openModal)
})
```