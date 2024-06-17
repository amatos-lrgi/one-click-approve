Drag this link to your bookmark bar:
<a href="javascript:!function(){const e=document.querySelectorAll('input[type=radio]');for(const t of e)if('approve'==t.value){t.click();break}const t=document.querySelectorAll('button');for(const e of t)if(e.textContent.includes('Submit review')){e.click();break}}();">APPROVE</a>

```javascript
javascript:(
    function() {
        const inputs = document.querySelectorAll('input[type=radio]'); 
        for (const input of inputs) { 
            if (input.value=='approve') { 
                input.click(); break;
            }
        }
        const buttons = document.querySelectorAll('button');
        for (const button of buttons) { 
            if (button.textContent.includes('Submit review')) {   
                button.click(); 
                break; 
            }
        }
    }
)();
```

Minified with https://minify-js.com/. Note: replace `"` by `'`.