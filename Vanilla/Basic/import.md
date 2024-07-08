```export let apiKey = "aaaaaaa1111111";```  
```export let abc = "abc";```  
여러 개의 변수를 export 할 수 있음

```import { apiKey, abc } from "./util.js"```  
apiKey, abc라는 변수를 그대로 import함  
```import * as util from "./util.js"```  
util.js에서 제공하는 모든 대상이 객체에 결합되게 import함

```console.log(util.apiKey);```

```export default "aaaaaa1111111";```  
값 자체를 default로 export 하기 때문에 여러 개를 export 할 수 없음

```import apiKey from "./util.js"```  
값을 import해서 apiKey라는 이름에 할당해 사용해야 함

```console.log(apiKey);```  
