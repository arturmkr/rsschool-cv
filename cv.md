# Artur Mkrtychian

### Contacts:
- Discord: Artur (@arturmkr)

### About myself:
Learning JS Development

### Skills:
Java

### Code sample:
```javascript
function filterSelection(match) {
    let count = 0;
    document.querySelectorAll('.box').forEach(item => {
        let name = item.querySelector('.boxLabel').innerHTML;
        if(match === '') {
            item.querySelector('input[type=checkbox]').checked = false;
            return;
        }

        if (name.toUpperCase().indexOf(match.toUpperCase()) >= 0) {
            item.querySelector('input[type=checkbox]').checked = true;
            count++;
        } else {
            item.querySelector('input[type=checkbox]').checked = false;
        }
    });
    document.querySelector('.selectedValue span').innerHTML = count;
}
```

### Experience:
NDI

### Education:
High

### English:
B2
