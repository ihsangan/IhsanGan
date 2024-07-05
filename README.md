### aboutMe()
```js
async function aboutMe() {
  const name = 'Muhammad Ihsan'
  let age = undefined
  let region = 'Central Borneo, Indonesia'
  let statistics = await fetch('https://github-readme-stats.vercel.app/api?username=IhsanGan&show_icons=true');
  let favLang = await fetch('https://github-readme-stats.vercel.app/api/top-langs/?username=ihsangan&langs_count=6&layout=compact');
  let streak  await fetch('https://github-readme-streak-stats.herokuapp.com/?user=ihsangan&date_format=j%20M%5B%20Y%5D')
```
#### statistics.body
![statistics.body](https://github-readme-stats.vercel.app/api?username=ihsangan&show_icons=true)
#### favLang.body
![Most lang's](https://github-readme-stats.vercel.app/api/top-langs/?username=ihsangan&langs_count=6&layout=compact)
#### streak.body
![Streak](https://github-readme-streak-stats.herokuapp.com/?user=ihsangan&date_format=j%20M%5B%20Y%5D)
```js
  return
};
let socials = new Map([
  ['website', 'https://isan.eu.org/'],
  ['instagram', 'https://instagr.am/i_snsz'],
  ['facebook', 'https://fb.com/isanxyz'],
  ['twitter', 'https://twitter.com/i_sanzz'],
  ['youtube', 'https://youtube.com/c/san03'],
  ['github', 'https://github.com/ihsangan'],
  ['tiktok', 'https://tiktok.com/@i_sanzz'],
  ['linkedin', 'https://linked.com/in/ihsanzz'],
  ['keybase', 'https://keybase.io/ihsangans'],
  ['discord', 'https://discord.com/users/581678592715522055'],
  ['views', 'https://komarev.com/ghpvc/?username=ihsangan&color=brightgreen']
]);

```
#### socials.get('views')
![](https://komarev.com/ghpvc/?username=ihsangan&color=brightgreen)
