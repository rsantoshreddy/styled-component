# Reasons to not use styled components.
1. No IDE support for code completion suggestions nor prettify.
2. Increases bundle file size.
3. Less performant.
4. Multiple classes added to rendered dom.
5. Difficult to figure out the class for style changes.

## Some differences
| Quality        | Non Styled Component           | Styled Component  |
| :-------------: |:-------------:| :-------------:|
| Code size      | ![alt text][nonStyleComponentBuild] | ![alt text][styleComponentBuild] |
| Performance      | ![alt text][nonStyleComponentPerf] | ![alt text][styleComponentPerf] |
| Non realistic code | ![alt text][nonStyleComponentCode]| ![alt text][nonStyleComponentCode] |

[nonStyleComponentBuild]: https://github.com/rsantoshreddy/non-styled-component/src/images/build.png "nonStyleComponentBuild image"

[styleComponentBuild]: https://github.com/rsantoshreddy/styled-component/blob/master/src/image/build.png "styleComponentBuild image"

[nonStyleComponentPerf]: https://github.com/rsantoshreddy/non-styled-component/src/images/perf.png "styleComponentBuild image"

[styleComponentPerf]: https://github.com/rsantoshreddy/styled-component/src/images/perf.png "styleComponentBuild image"

[nonStyleComponentCode]: https://github.com/rsantoshreddy/non-styled-component/src/images/code.png "styleComponentBuild image"

[styleComponentCode]: https://github.com/rsantoshreddy/styled-component/src/images/build.png "styleComponentBuild image"

https://github.com/styled-components/styled-components/issues/637

