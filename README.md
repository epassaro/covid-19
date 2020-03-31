# covid-19

https://epassaro.github.io/covid-19 ![publish](https://github.com/epassaro/covid-19/workflows/publish/badge.svg)

Daily graphs of COVID-19 pandemic

- Automatically updated every day at 22:00 (Argentina Standard Time)
- Data downloaded from [John Hopkins University repository](https://github.com/CSSEGISandData/COVID-19)
- Code released under GNU GPLv3 License

---
Automatic graph generation and site deploy also work with forks!

1. Fork the repo. 
2. Go to 'Actions' and activate. 
3. Go to 'Settings' and choose to deploy GitHub pages in `master` branch
4. New plots can be generated simply by adding new entries in `plots.yml`. You don't need to run the notebook in your computer!.
5. Push your changes and voilà!
- Tip: comment `[skip-ci]` in the commit message to avoid building the site unnecesarily