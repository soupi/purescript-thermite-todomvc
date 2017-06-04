A standalone todomvc example cut out of [purescript-thermite](https://github.com/paf31/purescript-thermite) repo by Phil Freeman.

### Prerequisites

- psc-0.11.*
- pulp-10.0.*
- bower
- npm

### Building and Running

```sh
bower i
npm i
pulp browserify --to html/index.js
cd html
python -m SimpleHTTPServer # or any other http server
```

now go to: [localhost:8000](http://localhost:8000) (or using whatever port you used)!
