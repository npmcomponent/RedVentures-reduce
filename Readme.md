*This repository is a mirror of the [component](http://component.io) module [redventures/reduce](http://github.com/redventures/reduce). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/redventures-reduce`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# reduce

  array reduce

## Installation

```sh
  $ component install redventures/reduce
```

## API

```js
var reduce = require('reduce');

var numbers = [0, 1, 2, 3, 4, 5];

var result = reduce(numbers, function(prev, curr){
  return prev + curr;
});
```
   
## License

Copyright 2012 Red Ventures

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this work except in compliance with the License. You may obtain a copy of the License in the LICENSE file, or at:

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.
