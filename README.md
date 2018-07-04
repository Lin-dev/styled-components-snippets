# Styled-Components Snippets for Atom

View the [Styled-Components documentation](https://www.styled-components.com/docs) here.

I'll add to this over time. Submit PR's if you like. Tag me on them.

## Snippets so far

### Imports

| Prefix  | Output                                              |
| ------- | --------------------------------------------------- |
| `imsc`  | `import styled from 'styled-components';`           |
| `imscn` | `import styled from 'styled-components/native';`    |
| `imscg` | `import { injectGlobal } from 'styled-components';` |
| `imsct` | `import { withTheme } from 'styled-components';`    |

### Creation

| Prefix      | Example Output / Description                                                                          |
| ----------- | ----------------------------------------------------------------------------------------------------- |
| `sc`        | `const ${1} = styled.${2}` / Styled-Component                                                         |
| `exsc`      | `export const ${1} = styled.${2}` / Export styled-component                                           |
| `scc`       | `const Styled${1} = styled(${1})` / Styled-Component from existing component                          |
| `exscc`     | `export const Styled${1} = styled(${1})` / Export styled-component from existing component            |
| `scext`     | `const Extended${1} = ${1}.extends` / Styled-Component extends                                        |
| `exscext`   | `export const Extended${1} = ${1}.extends` / Export styled-component extends                          |
| `scf`       | Add both 'imsc' and 'sc' to a new styles.js file                                                      |
| `scattrs`   | `const ${1} = styled.${2}.attrs({ ${3}: ${4} })${5}` / Styled-Component with attributes               |
| `exscattrs` | `export const ${1} = styled.${2}.attrs({ ${3}: ${4} })${5}` / Export styled-component with attributes |

### Props

| `scp` | `${props => props.${1}};` / Use props inside styled-component |
| `scpt` | `${({ theme }) => theme.${1}};` / Use props.theme inside styled-component |

### Misc

| Prefix          | Example Output / Description                                            |
| --------------- | ----------------------------------------------------------------------- |
| `inr`           | `innerRef={x => this.${1} = x}` / shorthand                             |
| `innerRef`      | `innerRef={x => this.${1} = x}` / longhand                              |
| `injectGlobal`  | `injectGlobal` / Create injectGlobal var                                |
| `ThemeProvider` | `<ThemeProvider theme={${1}}> ${2} </ThemeProvider>`                    |
| `sct`           | `const theme = { ${1}: '${2}' }` / Create styled-component theme object |

###### The MIT License

Copyright (c) 2018 @jonkwheeler

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
