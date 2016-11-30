<template>
  <div class="markdown-body">
    <p>请用命令行进行单元测试，npm run test</p>
    <pre>
<code class="lang-javascript">
> dme-demos@1.0.0 test /code/project/dme-demos
> mocha test/*.spec.js --compilers js:babel-core/register --reporter spec

  dme-template
    ✓ dev is function
    ✓ dev() result is "Hello World"

  2 passing (19ms)
</code>
</pre>
  </div>
</template>