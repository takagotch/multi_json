### multi_json
---
https://github.com/intridea/multi_json

```rb
require 'multi_json'

MultiJson.load('{"abc":"def"}')
MultiJson.load('{"abc":"def"}', :symbolize_keys => true)
MultiJson.dump({:abc => 'def'})
MultiJson.dump({:abc => 'def'}, :pretty => true)

begin
  MultiJson.load('{invalid json}')
rescue MutiJson::ParseError => exception
  exception.data
  exception.cause
end

spec.add_dependency 'multi_json', '~> 1.0'
```

```
```

```
```


