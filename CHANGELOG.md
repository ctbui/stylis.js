## 0.6.4 (December 05, 2016)

- improvements to parsing, do away with the little regex that was used.
- handle edge cases with `@keyframes` nested in `@root` block

## 0.6.3 (December 04, 2016)

- patch `h1, &:before{}` pseudo selectors in multiple selectors

## 0.6.2 (December 04, 2016)

- patch flat css `stylis('#id', 'color:red;')` to act as a block `stylis('#id', '&{color:red;}')`