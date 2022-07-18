# Regex-Quiz


## Regex Study
<pre>
<code>
test
</code>
</pre>


### Task 1: Word Boundaries
- `regular expression`: \b[wW][oO][rR][dD]\b
- `substitution`:

### Task 2: Capitalizing!
- `regular expression`: /\bi\b/g
- `substitution`: I

### Task 3: Uppercase Consonants
- `regular expression`: /[^AEIOUa-z_\W\d]/g
- `substitution`:

### Task 4: Retrive Numbers
- `regular expression`: /\d+/g
- `substitution`:

### Task 5: White Space
- `regular expression`: /\s{4,}/g
- `substitution`:

### Task 6: Broken Keyboard
- `regular expression`: /(.)\1{2}/g
- `substitution`: $1

### Task 7: Vaildation IP
- `regular expression`: /^(?:(?:25[0-5]|2[0-4]\d|1\d{2}|[1-9]\d|\d)\.){3}(?:25[0-5]|2[0-4]\d|1\d{2}|[1-9]\d|\d)$/
- `substitution`: 
 
### Task 8: Html Tags
- `regular expression`: /<[^>]*|[^<]*>/g
- `substitution`: 

### Task 9: Match an E-Mail
- `regular expression`: /^[^\.\s@()<>,;:\\\"\[\]]+\.?[^\.\s@()<>,;:\\"\[\]]+@([a-zA-Z][a-zA-Z\d-]*?(?<!-)\.)+[a-zA-Z]{2,6}$/i
- `substitution`: 

### Task 10: Followed by #
- `regular expression`: /([^\s])(?=#)/g
- `substitution`: 

### Task 11: Vaildate Floating Point Numbers
- `regular expression`: /^[-+]?(\d+[,.]|\d*[.,]?\d+)(e[-+]?\d+)?$/i
- `substitution`: 

### Task 12: Match any numbers between 0-100
- `regular expression`: /\b(?<!-)(?:\d{1,2}|100)\b/g
- `substitution`: 

### Task 13: Match alternating 0S and 1S in any order
- `regular expression`: /\b(?!\d*(\d)\1)[10]+\b/g
- `substitution`: 

### Task 14: Spam Filter
- `regular expression`: /^(?!.*(?:not allowed|filter|mirc).*).*(?:http:\/\/|www\.|porn|credit card).*$/i
- `substitution`: 

### Task 15: Not Surrounded By Digits
- `regular expression`: /(?!(?<=\d)\.(?=\d))\./g
- `substitution`: -

### Task :
- `regular expression`: 
- `substitution`: 

### Task :
- `regular expression`: 
- `substitution`: 

### Task :
- `regular expression`: 
- `substitution`: 

### Task :
- `regular expression`: 
- `substitution`: 

### Task :
- `regular expression`: 
- `substitution`: 

### Task :
- `regular expression`: 
- `substitution`: 

### Task :
- `regular expression`: 
- `substitution`: 
