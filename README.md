# covid-19

https://epassaro.github.io/covid-19 ![publish](https://github.com/epassaro/covid-19/workflows/publish/badge.svg)

Daily graphs of COVID-19 pandemic

- Automatically updated every day at 22:00 (Argentina Standard Time)
- Data downloaded from [John Hopkins University repository](https://github.com/CSSEGISandData/COVID-19)
- Code released under GNU GPLv3 License

---
Automatic graph generation and site deploy also work with forks!

- Fork the repo. Go to 'Actions' and activate. Go to 'Settings' and choose to deploy GitHub pages in `master` branch
- New plots can be generated simply by adding a new key in the `countries` dictionary
- Push your changes and voilà! 
- Tip: comment `[skip-ci]` in the commit message to avoid building the site unnecesarily
