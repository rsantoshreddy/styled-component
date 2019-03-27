# Reasons to not use styled components.
1. No IDE support for code completion suggestions nor prettify.
2. Increases bundle file size.
3. Less performant.
4. Multiple classes added to rendered dom.
5. Difficult to figure out the class for style changes.

## Some differences
| Quality        | Non Styled Component           | Styled Component  |
| :-------------: |:-------------:| :-------------:|
| Code size      | ![nonStyleComponentBuild] | ![styleComponentBuild] |
| Performance      | ![nonStyleComponentPerf] | ![styleComponentPerf] |
| Non realistic code | ![nonStyleComponentCode]| ![styleComponentCode] |

[nonStyleComponentBuild]: https://github.com/rsantoshreddy/non-styled-component/blob/master/src/images/build.png "nonStyleComponentBuild image"

[styleComponentBuild]: https://github.com/rsantoshreddy/styled-component/raw/master/src/image/build.png "styleComponentBuild image"

[nonStyleComponentPerf]: https://github.com/rsantoshreddy/non-styled-component/blob/master/src/images/Screenshot%20from%202019-03-28%2001-08-43.png "styleComponentBuild image"

[styleComponentPerf]: https://github.com/rsantoshreddy/styled-component/blob/master/src/image/perf.png "styleComponentBuild image"

[nonStyleComponentCode]: https://github.com/rsantoshreddy/non-styled-component/blob/master/src/images/code.png "styleComponentBuild image"

[styleComponentCode]: https://github.com/rsantoshreddy/styled-component/blob/master/src/image/code.png "styleComponentBuild image"

https://github.com/styled-components/styled-components/issues/637
