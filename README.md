- 👋 Hi, I’m @3023860
- 👀 I’m interested in nothing
- 🌱 I’m currently learning nothing
- 💞️ I’m looking to collaborate on nothing
- 📫 How to reach me ...just don't 

<!---
3023860/3023860 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
)))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))))

var Tabs = require('hypertabs')

var tabs = Tabs()

tabs.add(h('h1', 'foofoo'))
tabs.add(h('h1', 'baz'))

tabs.select(1) //change to the "baz" tab.

document.body.appendChild(tabs)

setTimeout(
  function () { tabs.select(0) },
  2000
)
