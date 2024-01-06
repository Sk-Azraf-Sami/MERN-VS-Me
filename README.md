# MERN-VS-Me

### Invalid options object. Dev Server has been initialized using an options object that does not match the API schema 

**Solve:** My issue was I was on the 'MARH_S_118' so some internet worked, but this must have blocked whatever npm needs....connecting to the proper wifi (Example: eduroam) fixed it.
[link](https://stackoverflow.com/questions/70374005/invalid-options-object-dev-server-has-been-initialized-using-an-options-object)
  
### Module not found: Error: Can't resolve 'zlib'
**Solve:** For some reason, VSCode inserted import e from 'express' at the top of my file in react <br>
```
import { response } from 'express';
```
I delete the above import line and then the problem is resolved, all the errors are gone after the above change. [link](https://stackoverflow.com/questions/67001182/module-not-found-error-cant-resolve-zlib)

### How to fix "Error: listen EADDRINUSE: address already in use :::5000" Unhandled 'error' event 
**Solve:** [link](https://stackoverflow.com/questions/54468097/how-to-fix-error-listen-eaddrinuse-address-already-in-use-5000-unhandled)

### useNavigate() may be used only in the context of a <Router> component
**Solve:** [link](https://stackoverflow.com/questions/70491774/usenavigate-may-be-used-only-in-the-context-of-a-router-component)
