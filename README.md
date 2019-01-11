# gitzip

### Description
It can make sub-folder/sub-directory of github repository as zip and download it.

### Usage of download link via Parameters

##### Parameters

|Name|Type|Description|
|:---:|:---:|:---|
|download|string|The URL of the Github repository.|
|token|string|Your github token. If it is not assigned, Gitzip would use token from cookie.|

##### Examples
 * https://j0nk0.github.io/gitzip/?download=/j0nk0/gitzip
 * https://j0nk0.github.io/gitzip/?download=j0nk0/gitzip
 * https://j0nk0.github.io/gitzip/?download=https://github.com/j0nk0/gitzip/tree/gh-pages
 * https://j0nk0.github.io/gitzip/?download=/j0nk0/gitzip&token=12345yourtoken6789
 * https://j0nk0.github.io/gitzip/?download=/d3/d3/tree/master/test&token=12345yourtoken6789
 * https://j0nk0.github.io/gitzip/?download=https://github.com/d3/d3/tree/master/test&token=12345yourtoken6789

